Download Link: https://assignmentchef.com/product/solved-eece5639-computer-vision-i-homework-3
<br>
<span style="font-size: 2.61792em; letter-spacing: -1px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', sans-serif;">Image Features and Image Segmentation</span>

<ol>

 <li>Consider a 8×8 image f(x,y) such that <em>f</em>(<em>x,y</em>) = |<em>x </em>− <em>y</em>| for <em>x,y </em>= 0<em>,</em>1<em>,…,</em>7 .

  <ul>

   <li>Find the magnitude and orientation of the gradient by using the Prewitt maks. (Disregardboundaries)</li>

   <li>Repeat using the Sobel masks.</li>

  </ul></li>

 <li>Suppose that the intensities of a 3×3 neighborhood are given by the planar equation <em>I</em>(<em>r,c</em>) = <em>pr </em>+ <em>qc </em>+ <em>h</em>, with <em>r,c </em>= −1<em>,</em>0<em>,</em>

  <ul>

   <li>Find the image gradient at (0,0).</li>

   <li>Show that the Prewitt masks compute estimates of p and q .</li>

   <li>Show that the Laplacian mask has zero response:</li>

  </ul></li>

</ol>

<table width="84">

 <tbody>

  <tr>

   <td width="28">0</td>

   <td width="28">-1</td>

   <td width="28">0</td>

  </tr>

  <tr>

   <td width="28">-1</td>

   <td width="28">4</td>

   <td width="28">-1</td>

  </tr>

  <tr>

   <td width="28">0</td>

   <td width="28">-1</td>

   <td width="28">0</td>

  </tr>

 </tbody>

</table>

<ol start="3">

 <li>Compute the C matrix and find its eigenvalues, to detect the corner in the image given in Figure 1,when using a neighborhood of 7 × 7.</li>

 <li>Find the Hough transform (using the normal equation of a line) for the lines enclosing an objectwith vertices A=(2,0), B=(2,2) and C=(0,2). Sketch the modified object enclosed by lines replacing (rho,theta) of the given object lines with (rho*rho,theta + 90). Calculate the area of the modified object.</li>

 <li>The sides of a convex polygon have Hough transform (using the normal equation of a line):</li>

</ol>

<table width="143">

 <tbody>

  <tr>

   <td width="47"><strong>Side</strong></td>

   <td width="61"><em>ρ</em></td>

   <td width="35">Θ</td>

  </tr>

  <tr>

   <td width="47">AB</td>

   <td width="61">3</td>

   <td width="35">90</td>

  </tr>

  <tr>

   <td width="47">BC CD DA</td>

   <td width="61"></td>

   <td width="35">0 60-45</td>

  </tr>

 </tbody>

</table>

1

<table width="584">

 <tbody>

  <tr>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

  </tr>

  <tr>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

  </tr>

  <tr>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

  </tr>

  <tr>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

  </tr>

  <tr>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

  </tr>

  <tr>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

  </tr>

  <tr>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

  </tr>

  <tr>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

  </tr>

  <tr>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

  </tr>

  <tr>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

  </tr>

  <tr>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

  </tr>

  <tr>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

  </tr>

  <tr>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

  </tr>

  <tr>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

  </tr>

  <tr>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

  </tr>

  <tr>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

  </tr>

  <tr>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

  </tr>

  <tr>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

  </tr>

  <tr>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

  </tr>

  <tr>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

  </tr>

  <tr>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">40</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

   <td width="29">0</td>

  </tr>

 </tbody>

</table>

Figure 1: Checkerboard for corner detection

<ul>

 <li>Draw the polygon in image space and indicate the coordinates of the four vertices.</li>

 <li>The polygon is rotated 30 degrees counterclockwise around the image space origin. Find theHough transform for the sides of the rotated polygon.</li>

</ul>

<ol start="6">

 <li>Assume that regions in an image have an intensity distribution that is planar combined with Gaussiannoise. Thus the intensity value at a point (x,y) of the region can be identified as</li>

</ol>

<em>I</em>(<em>x,y</em>) = <em>Ax </em>+ <em>By </em>+ <em>C </em>+ <em>N</em>(0<em>,σ</em>)

Derive the likelihood ratio-based merge criterion under this assumption.

<ol start="7">

 <li>(Old exam problem) An image region has the following histogram:</li>

</ol>

<table width="238">

 <tbody>

  <tr>

   <td width="99"><strong>Gray Value</strong></td>

   <td width="23">1</td>

   <td width="23">2</td>

   <td width="23">3</td>

   <td width="23">4</td>

   <td width="23">5</td>

   <td width="23">6</td>

  </tr>

  <tr>

   <td width="99"><strong>Count</strong></td>

   <td width="23">1</td>

   <td width="23">2</td>

   <td width="23">3</td>

   <td width="23">2</td>

   <td width="23">1</td>

   <td width="23">1</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Show the iterations when the mean shift algorithm is run to find an estimate of the mode (peak) of the histogram, using windows of diameter 4, and with the initial window centered at <em>x </em>= 4</li>

 <li>Let <em>a </em>be the mode found by the mean shift algorithm in the previous part. If the region is approximated by <em>a</em>, how much is the fitting error?</li>

 <li>Assuming that the fitting error is due to additive zero mean uncorrelated Gaussian noise, whatis the likelihood that this model is correct?</li>

</ul>

2