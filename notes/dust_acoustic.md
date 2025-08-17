+++
title = "DAW"
hascode = true
rss = "DAWs. Last updated: August 17, 2025"
rss_title = "DAW"
rss_pubdate = Date(2025, 8, 17)

tags = ["dusty", "plasma"]
+++

# Dust Acoustic Waves
___

## Overview
When dust particles and plasma merge to form a dusty plasma, the usual plasma wave modes, e.g., ion-acoustic, ion-cyclotron, etc., are modified because a percentage of the electrons become attached to the dust grains so that equilibrium charge neutrality condition becomes

$$
n_{i o}=n_{e o}+Z_d n_{d o}
$$

where $n_{j o}(j=i, e, d)$ are the (ion, electron, dust) zero order densities and $Z_d=Q_d / e$ is the dust charge number. For these plasma modes, the relatively massive dust grains do not participate in the wave dynamics and are treated as an immobile negatively charged background distribution. On the other hand, the dust-acoustic mode frequencies are typically well below the electron and ion plasma frequencies, so that both the electrons and ions can be assumed to be in Boltzmann equilibrium.

## Physics Model
The simplest model of the dust-acoustic wave is to consider the ions, electrons and dust as a multi-component fluid. The ions, electrons and dust are taken to be at rest and homogeneous in zero order, having constant temperatures $T_i, T_e$, and $T_d$, and the dust charge is assumed to be constant. The dust obeys the continuity and momentum equations

$$
\begin{align}
\frac{\partial n_d}{\partial t}+\frac{\partial}{\partial x}\left(n_d u_d\right) &= 0 \\
m_d n_d\left(\frac{\partial u_d}{\partial t}+u_d \frac{\partial u_d}{\partial x}\right) &=-\gamma_d k T_d \frac{\partial n_d}{\partial x}+e n_d Z_d \frac{\partial \varphi}{\partial x}
\end{align}
$$

where $m_d$ is the mass of the dust particles, $u_d$ is the dust fluid velocity, $\gamma_d$ is the ratio of specific heats for the dust fluid, and $\varphi$ is the electrostatic potential. The inertia terms in the electron and ion momentum equations are ignored (Boltzmann)

$$ 
\begin{align} 
0 &=-k T_i \frac{\partial n_i}{\partial x}-e n_i \frac{\partial \varphi}{\partial x} \\
0 &=-k T_e \frac{\partial n_e}{\partial x}+e n_e \frac{\partial \varphi}{\partial x}
\end{align} 
$$

The potential, $\varphi$, is related to the charge densities by Poisson's equation

$$ 
\begin{equation}
\frac{\partial^2 \varphi}{\partial x^2}=-\frac{e}{\varepsilon_0}\left(n_i-n_e-Z_d n_d\right) 
\end{equation}
$$

## Dispersion Relation
Linearizing the previous equations and Fourier transforming along $x$ and $t$ yields the following dispersion relation
$$
\omega^2 / k^2 =\left(\frac{k T_d}{m_d}+\frac{\lambda_D^2 \omega_{p d}^2}{1+k^2 \lambda_D^2}\right)
$$

where $\lambda_D=\left(\lambda_{D e}^{-2}+\lambda_{D i}^{-2}\right)^{-1 / 2}, \lambda_{D j}=\left(\varepsilon_0 k T_j / e^2 n_{j o}\right)^{1 / 2}, \quad$ and $\omega_{p d}=\left(e^2 Z_d^2 n_{d o} / \varepsilon_0 m_d\right)^{1 / 2}$.
For the case of cold dust $(T_d \to 0)$ and in the long wavelength limit $(k^2 \lambda_{D}^2 \ll 1)$, the dispersion relation reduces to $\omega / k = c_{D A}$, where $c_{D A}$ is the dust acoustic speed given by
$$
c_{D A}^2 =\left(\frac{k T_i}{m_d} \frac{n_{d o}}{n_{i o}} Z_d^2\right)
$$