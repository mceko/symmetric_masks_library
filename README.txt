Library of symmetric masks used in the work “Symmetric Convolution Masks for In-fill Pixel Interpolation”
by Matthew Ceko under the supervision of Imants Svalbe

Contains all valid symmetric mask solutions, M, for vmax = 4, 8, and 16, p,q <= 11, stored in MATLAB arrays
M is a S x S x N array where S is the size of the mask and N is the number of mask solutions
File naming convention used: p_q_axis.mat where axis = f for fundamental axis and axis = r for rotated axis
Linearly independent basis masks also provided for vmax = 16, denoted with b in filename

1D projections and linearly independent projected masks given for vmax = 16, reduced to smallest integer coefficients such that gcd(M) = 1
For the projected masks, M is an N x S array