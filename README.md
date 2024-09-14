<div style="background-color: #e0f7fa; border-radius: 10px; width:90%;">
    <h2 style="color: #00796b;">Bercovier-Engelman Test</h2>
</div>
We consider the steady Stokes problem defined by the following equations:
$$
\begin{align}
    - \mu \Delta \mathbf{u} + \nabla p &= \mathbf{f} \quad \text{on} \quad \Omega, \\
    \nabla \cdot \mathbf{u} &= 0 \quad \text{on} \quad \Omega, \\
    \mathbf{u} &= 0 \quad \text{in} \quad \partial \Omega, \\
    %\frac{\partial \mathbf{u}}{\partial n} - p \cdot \mathbf{n} &= \mathbf{g} \quad \text{sur} \quad \Gamma_{\text{in}} \cup \Gamma_{\text{out}} = \{0,1\} \times [0,1].
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
