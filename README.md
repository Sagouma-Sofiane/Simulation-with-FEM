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


## Variational Form

We set \( V = [H^{1}_{0}(\Omega)]^2 \) and \( Q = L^{2}_{0}(\Omega) = \{ \mathbf{v} \in L^2(\Omega) \, | \, \int_{\Omega} \mathbf{v} \, dx = 0 \} \).

We then multiply equation (1) by \( \mathbf{v} \in V \) and equation (2) by \( \mathbf{q} \in Q \), and integrate the equations over \( \Omega \). By applying Green's formula, we get:

Find \( (\mathbf{u}, \mathbf{p}) \in \mathcal{W} = \mathcal{V} \times \mathcal{Q} \) such that:
