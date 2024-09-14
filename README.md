## Bercovier-Engelman Test

We consider the steady Stokes problem defined by the following equations:

$$
\begin{align} 
    - \mu \Delta \mathbf{u} + \nabla p &= \mathbf{f} \quad \text{on} \quad \Omega, \\
    \nabla \cdot \mathbf{u} &= 0 \quad \text{on} \quad \Omega, \\
    \mathbf{u} &= 0 \quad \text{in} \quad \partial \Omega.
\end{align}
$$

The exact solution of Bercovier-Engelman is defined on $\Omega=[ 0, 1 ]^2$ by:

$$
\begin{aligned}
    u_1 &= -256y(y - 1)(2y - 1)x^2(x - 1), \\
    u_2 &= 256x(x - 1)(2x - 1)y^2(y - 1), \\
    p &= (x - 0.5)(y - 0.5).
\end{aligned}
$$
<div style="background-color: #e0f7fa; border-radius: 10px; padding: 10px; width:90%;">
    <h2 style="color: #00796b;">Variational Form</h2>
</div>
We set V = [H^1_0(Ω)]^2 and Q = L^2_0(Ω) = { v ∈ L^2(Ω) | ∫_Ω v dx = 0 }.
