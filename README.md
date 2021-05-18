# filter_kit
FIR and IIR Source Code Kit. 

This kit contains the C code necessary to generate both IIR and FIR low pass, high pass, band pass, notch, and all pass filters.

For FIR filters, the kit contains code for both Rectangular Windowed FIR and Parks McClellan FIR. The code will also generate FIR filters with the frequency sampling method. Two frequency sampling methods are given. The first allows the user to define the magnitude response for a linear phase filter. The second uses the magnitude and phase response defined by a low pass prototype filter, such as the Butterworth. The code for several windows such as the Kaiser is given as well as the code for making fractional delay adjustments.

For IIR filters, the kit contains the bilinear transform code and the root finder code needed for band pass and notch filters. The IIR code generates biquad coefficients, but the additional code needed to generate Nth order coefficients is also included.

While previous versions of this kit had the low pass prototype coefficients tabulated, the kit now contains the code to calculate the poles and zeros for, and generate the second order s plane factors for, the following filter polynomials: Butterworth, Chebyshev, Gauss, Bessel, Adjustable Gauss, Papoulis (Classic L), Inverse Chebyshev, and Elliptic. 1 to 20 poles.

The kit also comes with a small utility program that will plot the magnitude response of FIR and IIR filters.


# Credits

All of this code originally is wroten by [Iowa Hills Software](http://www.iowahills.com) all initial credit goes to them. I just uploaded this in to git to ease development and empower it with version control system for future possible improvements for the OSS community 
