# Transfer-Function-Calculator
You will write code to
• Calculate the magnitude and phase response of a third-order system
o The numerator of the transfer function will be 2nd order
o The denominator of the transfer function will be 3rd order
o Your code must accommodate a step function, i.e., u(t), as the input excitation
• Graph the output of your code as a fully labeled Bode plot
• Magnitude plot on top, phase plot on bottom
Thus the output is a Bode Plot, fully labeled and scaled, depicting the system’s response.
Inputs
• Radian frequencies of poles p1, p2, p3, and zeros z1, z2
o These frequencies can be complex!
o Your code must accept complex frequencies
• Frequency range of s
o Input start frequency (minimum 1 rad/s)
o Input stop frequency (maximum 1E9 rad/s)
Outputs
• Table depicting
o Radian frequency in left column
▪ Note that frequencies must be output as a log sweep, e.g., 1, 2, 3, 4, 5, 6, 7, 8, 9,
10, 20, 30, 40, 50, 60, 70, 80, 90, 100, 200, 300, 400, 500... etc. o Magnitude in middle column
o Phase in right column
Your code must
• Be able to accept any complex values for the poles and zeros between 0 and 1E8 rad/s
• Output the table as described above and display a fully labeled Bode Plot
• Ask the User to
o Input another case? or o Exit (gracefully!)
Transfer function and system response
C ( s ) = R ( s ) G ( s ) = 1 ( s + z1 ) ( s + z 2 )
s (s + p1 )(s + p2 )(s + p3 )
Where
C(s) is the output response (which your code will plot)
R(s) is the input excitation (which for u(t) is 1/s)
G(s) is the system transfer function (for which the user will specify poles & zeros)
Format
Upload your code to the associated Assignments folder as a text file (or .py).
I will run a couple of test cases. It will be wise to check the numerical results of your code before submitting!!
