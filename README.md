java c
EE 113: Digital Signal Processing 
Fall 2024 
Assignment #4 — due Sunday 11:59 PM, November 3, 2024
1. (25 pts) (MATLAB: Working with harmonics)
(a) (3 pts) Create a real periodic signal ˆx[n] with period N = 11, where the one period of the signal is created by using rand() function of MATLAB. Please use the seed 115 i.e. rng(115)
(b) (10 pts) Create two functions that implement DTFS synthesis and analysis equations, one will give you the DTFS coefficients of a given periodic signal and other will reconstruct the signal from the DTFS coefficients.
(c) (2 pts) Calculate DTFS coefficients DTFS{xˆ[n]} = ˆck of the ˆx[n] and show that you can recon-struct ˆx[n] with the functions you implemented
(d) (10 pts) ˆx[n] is real and DTFS coefficients will be conjugate symmetric i.e. ˆc∗k = ˆcN−k.
i. For k = 5 : 1, set the ˆck and its conjugate pair ˆcN−k to zero, i.e first set them zero for k = 5, then for k = 5, 4 and for k = 5, 4, 3 etc. Reconst代 写EE 113: Digital Signal Processing Fall 2024 Assignment #4Matlab
代做程序编程语言ruct and plot the corresponding signals (over 4 period), explain what do you observe.
2. (25 pts) Prove that DTFS coefficients of a real and even periodic signal is purely real and DTFS coef-ficients of a real and odd periodic signal signal is purely imaginary.
3. (25 pts) A triangular pulse is given by

(a) (25 pts) Find the DTFT of the x[n] in its simplest form. (Not as a numerical value or as a sum of exponentials). Hint: You can write x[n] as a convolution of known signals
4. (25 pts) Let y[n] = x[n] ∗ h[n].
(a) (15 pts) Show that y[n] cannot have frequencies that x[n] does not have; hence, if X(Ω)=0, then Y (Ω)=0. This means DTLTI systems cannot create new frequencies.
(b) (10 pts) Using the result of the part (a), comment on whether the following system is DTLTI: y[n] = Sys{x[n]} = x[n]cos(Ω0n). Hint: Think about which DTFT property you can use and what happens in the frequency domain.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
