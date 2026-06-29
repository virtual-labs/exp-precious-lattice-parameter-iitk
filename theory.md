Errors in measurement of interplanar spacing <i>d</i> and lattice parameter(s) <i>a</i> using modern diffractometers can occur due to : <br><br>
-	Misalignment of the instrument<br>
-	Absorption of X-Rays by the specimen<br>
-	Displacement of the specimen from the diffractometer axis must be minimized (observational error)<br>
-	Vertical divergence of the incident beam<br>
-	Use of a flat specimen instead of a curved one to correspond to the diffractometer circle<br><br>

<!-- <img src="images/figure1.png"><br>
Figure 1: X-Rays Diffractogram for an FCC material<br><br> -->

<img src="images/fig_1.png"><br>

<b>Observational error :</b><br><br>

-	For a cubic material : <br>
<img src="images/image_1.png"><br>

Where the <i>d</i>-spacing is measured from Bragg’s law : <br>
<img src="images/image_test_1.png"><br>
Here, n = 1 which is the first order of diffraction and λ = 1.5406 Å for Cu-K<sub>α</sub> radiation.<br><br>

-	The precision of the calculated interplanar spacing (d) and lattice parameter (a) depends on the accuracy with which the diffraction angle θ is measured, since d is obtained through Bragg's law..<br>
<img src="images/figure2.png"><br>

Figure 2: Error in the measurement of sin θ decreases as the value of θ increases<br><br>

-	Take partial derivative of the Bragg equation : <br><br>
<img src="images/image_2.png"><br><br>

-	For a cubic system : <br><br>
<img src="images/image_4.png"><br><br>

-	As θ reaches 90°, the fractional error (Δa/a) tends towards zero because cot θ approaches zero. Consequently, lattice parameters calculated from high-angle reflections are expected to be closer to the true lattice parameter. <br>

Apart from the reduction in angular measurement error at higher diffraction angles, another important factor contributing to accurate lattice parameter determination is the resolution of the Cu-Kα doublet.The Cu-Kα radiation used in XRD consists of two closely spaced wavelengths, namely Kα₁ (λ=1.54056Å) and Kα₂ (=1.54439 Å). According to Bragg's law, these two wavelengths produce diffraction peaks at slightly different diffraction angles. At lower diffraction angles, the angular separation between the Kα₁ and Kα₂ peaks is very small, causing the peaks to overlap and making the precise determination of the peak position difficult.<br><br>

As the diffraction angle increases, the angular separation between the Kα₁ and Kα₂ components becomes larger and the two peaks become progressively better resolved. Since precise lattice parameter calculations are generally based on the Kα₁ peak position, improved separation of the doublet at higher angles reduces uncertainty in peak-position measurement. Consequently, high-angle reflections provide more reliable values of interplanar spacing and lattice parameter.<br><br>

Therefore, high-angle diffraction peaks are preferred for precise lattice parameter determination because:<br><br>

1.	The fractional error (Δa/a) resulting from an error in θ decreases with increasing diffraction angle, as indicated by Eq. (6). <br>
2.	The Kα₁ and Kα₂ components become better resolved at higher angles, enabling more accurate determination of the Kα₁ peak position. <br>
3.	The effect of systematic errors is minimized through extrapolation using the Nelson–Riley function. <br><br>

<b>Correction of Systematic Errors Using Nelson–Riley Extrapolation</b><br><br>

•	The Nelson-Riley extrapolation function compensates for systematic errors such as specimen displacement, transparency effects, absorption, and residual instrumental errors. By plotting the calculated lattice parameter values against the Nelson–Riley function F(θ) and extrapolating the best-fit line to F(θ)=0 (corresponding to θ=90∘), the influence of systematic errors is minimized and the true lattice parameter can be estimated with higher accuracy.
 <br>

•	For a cubic crystal with a lattice parameter a, a Nelson-Riley extrapolation function is used:<br>

<img src="images/img_10.png"><br><br>

In practice, lattice parameters calculated from different diffraction peaks often show slight variations due to systematic experimental errors. The Nelson–Riley extrapolation method reduces these variations by exploiting the fact that most systematic errors decrease with increasing diffraction angle. Therefore, extrapolation to θ=90∘ provides the most reliable estimate of the true lattice parameter.<br><br>

<b>Steps:</b><br>

1. Obtain the values of 2θ, θ, θ (in radians), sin θ, sin<sup>2</sup> θ, & cos<sup>2</sup> θ from the diffractogram. <br>
2. Index the diffraction peaks by assigning the appropriate (hkl) planes. <br>
3. Calculate the corresponding d-spacings using Bragg's law. <br>
4. Determine the lattice parameter a for each reflection using Eq. (1). <br>
5. Calculate the Nelson–Riley function F(θ) for each reflection. <br>
6. Plot the calculated lattice parameter a against F(θ). <br>
7. Extrapolate the best-fit line to F(θ)=0 to obtain the precise lattice parameter.<br>





<!-- -	The term ∆a⁄a  (or ∆d⁄d) is the fractional error in a (or d) caused by a given error in θ. The fractional error approaches zero as θ approaches 90°.<br><br>

-	Values of a will approach the true value as we approach 2θ = 180° (i.e., θ = 90°). We can’t measure a value at 2θ = 180°. We must plot measured values and extrapolate to 2θ = 180° versus some function of θ.<br><br>

<b>Absorption Error : </b><br><br>

-	For a cubic crystal with a lattice parameter a, a Nelson-Riley extrapolation function is used :<br>
<img src="images/img_10.png"><br><br>

<b>Steps:</b><br>

1.	From the diffractogram, we will obtain the values of all the parameters, viz., 2θ, θ, θ in radians, sin θ, sin2θ, cos2 θ <br>
2.	Calculate the (h k l) planes for each peak using equation (1)<br>
3.	Calculate the corresponding values of a in each case<br>

<b>Procedure of the experiment: </b><br>
• For F(θ) vs a and perform a linear fitting of the data obtained.<br> 
• The line of best fit which will be obtained will be further extrapolated to F(θ) = 0 and the y-intercept will give us the precise lattice parameter for the particular material.<br>

<b>FCC:</b> The above procedure yields a precise lattice parameter for FCC to be 3.631±0.003 Å.<br>
<img src="images/table_1.png"><br><br>
<img src="images/graph_1.png"><br><br>


 -->
