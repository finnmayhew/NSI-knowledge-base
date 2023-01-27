# DRAGON NSI

A 2021 IceCube [NSI](nsi.md) analysis ([wiki](https://wiki.icecube.wisc.edu/index.php/All_flavour_non-standard_interactions), [paper](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006)).

Performed by Thomas Ehrhardt.

Used 3 years of [DeepCore](deepcore.md) data from 5.6 to 100 GeV to search for NC NSI ([source](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006)).

Performed in two parts ([source](https://pos.sissa.it/398/245/pdf)):

1. When testing for any of the five NSI parameters, assume all others are zero (results in model dependence, required computationally).
2. Use a different parameterization with three NSI parameters, allowing some limits to be placed on a fully free NSI hypothesis.

The second parameterization looks like

$$
\begin{align*}
    H_\text{mat}(x) &= Q_\text{rel}U_\text{mat}D_\text{mat}(x)U_\text{mat}^\dagger Q_\text{rel}^\dagger
\end{align*}
$$

It can be approximated and reduced to a version called the "generalized matter potential" that has three parameters:

- $\epsilon_\oplus$
- $\varphi_{12}$
- $\varphi_{13}$

Succeeded by the [OscNext NSI](oscnext-nsi.md) analysis.
