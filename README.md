
Code Description for the Paper "**Unveiling the Complex Morphologies of Sessile Droplets on Heterogeneous Surfaces**"

This repository contains the code used in the research paper titled "Unveiling the Complex Morphologies of Sessile Droplets on Heterogeneous Surfaces". Below are descriptions for different substrate patterns implemented in the code:

**1. N-Polygon Substrate Patterns**

For N-polygon substrate patterns, please refer to the square.ipynb file for comprehensive explanations of the code. The implementation for other N-polygon substrates follows a similar structure to the square example but utilizes different equations for the partial derivatives.


**2. Non-Regular Patterns**

For non-regular substrate patterns, such as the flower pattern, detailed code descriptions can be found in the corresponding example named flower_pattern.ipynb.

**3. Square Pattern with Contact Angle Hysteresis Effec**

Code for genetrating morphological diagram via the contour curve method
for equilibrium droplets on a square pattern with different advancing contact angles is named as Advancing_contact_angle-square.ipynb. The base lines of the droplets are depicted by $(y/R_0 - 1)(y/R_0 + 1)(x/R_0 - 1)(x/R_0 + 1) - c_0=0$ with given values of ($R_0,c_0$), which correspond to different advancing contact angles.

**4. Droplet baseline described by Fourier series**

By detecting and fitting the contact line of the simulated droplets and matching the dimensions, we are able to apply the contour curve
method to calculate the corresponding droplet profile, which shows excellent
agreement with the findings from literature. The related codes are  fitting-contour-validation_with_Ref.ipynb and irregular.ipynb.
