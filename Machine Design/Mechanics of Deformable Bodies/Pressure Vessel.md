a closed structure containing fluids under pressure

Key assumptions:
	Pressure inside the vessel is greater than outside pressure
	For thin-walled vessels, stress distribution is uniform or constant
	Note that the pressure is gauge pressure

Classifications based on thickness
I. thin-walled - if $\frac{t}{D_\text{i}} \le 0.7$ 
II. else it's a thick-walled 

Classification based on shape
I. Cylindrical Pressure Vessels - found in industrial settings (e.g. compressed air
tank) 

A. Circumferential(or Tangential) Stress $(\sigma_{\text{T}})$  

Consider cutting a cylindrical pressure vessel(also including the pressure
of the fluid inside) on segments $mn$ and $pq$ perpendicular to the 
longitudinal axis in a length of $b$. 

![[Pasted image 20240924170825.png]]
Then make another cut through the longitudinal axis of the tank, resulting in
![[Pasted image 20240924171127.png]] 
Note that in order to do force balance, we have to represent them as force
vectors. From $\sigma_1 = \frac{F}{A} = \frac{F}{2bt}$ (multiply by two since there are two thickness
in the analysis involved), then $F = \sigma_1\,2bt$. 

Similarly for the inside pressure, $p = \frac{P_1}{2br}$ thus $P_1 = 2pbr$.

Summing all the forces in the horizontal axis we have:
$$ \varSigma F_x = 0 = \sigma_1\,2bt - 2pbr$$
Isolating $\sigma_1$ we have
$$\sigma_1 = \frac{2pbr}{2bt} = \frac{pr}{t}$$
Note that in some books, this tangential stress is denoted as 
$$S_T = \frac{P_i\,Di}{2te}$$
B. Longitudinal Stress $(\sigma_2)$ 
![[Pasted image 20240924172631.png]] 
This time, the cross-sectional area being pressure is the area of the circle
$(A = \pi \,r^2)$ , again we denote the pressure inside as $p$ then we have;
$$\varSigma\,F_x = \sigma_2\,(2\pi\,rt) - p\pi\,r^2  = 0 $$
Isolating $\sigma_2$ results in 
$$\sigma_2 = \frac{pr}{2t}$$ or in some books
$$\\S_L = \frac{P_i\,D_i}{4te}$$
For a thick-walled pressure vessels, formulas are given as
I. wall-thickness
$$t = \frac{D_i}{2}\,\sqrt{\frac{S_T + P_i}{S_T - P_i} - 1} $$
II. Maximum tangential or Hoop Stress in the inside of the cylinder wall $(psi)$ 
$$S_{ti} = \frac{P_i(r^2_o + r^2_i) - 2P_o\,r^2_o}{r^2_o + r^2_i} $$
III. Maximum tangential or Hoop Stress in the outside of the cylinder wall
$$S_{to} = \frac{-Pi(r^2_o + r^2_i) + 2P_i\,r^2_i}{r^2_o + r^2_i}$$Note that formulas like the [[ideal gas law]]  and [[variable stress]](both for the 
ductile and brittle materials) can be used