# NSI

Non-standard neutrino interactions.

## Theory

There's a brief theory overview in the [DRAGON NSI paper](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006).

If they exist, driven by [BSM](bsm.md).

NSI manifests through NC forward scattering between neutrinos and charged fermions in the Earth, assuming a new heavy mediator particle ([source](https://pos.sissa.it/398/245/pdf)).

The existence of NSI effects may resolve tensions in the standard [oscillation](oscillation.md) parameters ([source](https://pos.sissa.it/398/245/pdf)).

Our approach parametrizes the effect of NSI on the matter potential through six effective coupling parameters:

| Parameter                    | Label                                |
| ---------------------------- | ------------------------------------ |
| $\epsilon_{e\mu}^\oplus$     | "flavor-violating"                   |
| $\epsilon_{e\tau}^\oplus$    | "flavor-violating"                   |
| $\epsilon_{\mu\tau}^\oplus$  | "flavor-violating"                   |
| $\epsilon_{ee}^\oplus$       | "flavor-universal"/"flavor-diagonal" |
| $\epsilon_{\mu\mu}^\oplus$   | "flavor-universal"/"flavor-diagonal" |
| $\epsilon_{\tau\tau}^\oplus$ | "flavor-universal"/"flavor-diagonal" |

where $\epsilon_{\alpha\beta}^\oplus \approx \epsilon_{\alpha\beta}^e + \epsilon_{\alpha\beta}^p + Y_n^\oplus\epsilon_{\alpha\beta}^n$ ([source](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006)).

ALl these parameters are potentially complex ([source](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006)):

$$
\begin{align*}
    \epsilon_{\alpha\beta}^\oplus &= |\epsilon_{\alpha\beta}^\oplus|e^{i\delta_{\alpha\beta}}
\end{align*}
$$

For some reason, you can subtract off $\epsilon_{\mu\mu}^\oplus \times \mathbf{1}$ to reduce the parameters to five, and then the Hamiltonian is described by a total of eight real parameters ([source](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006)):

- $\vert\epsilon_{e\mu}^\oplus\vert$
- $\vert\epsilon_{e\tau}^\oplus\vert$
- $\vert\epsilon_{\mu\tau}^\oplus\vert$
- $\epsilon_{ee}^\oplus - \epsilon_{\mu\mu}^\oplus$
- $\epsilon_{\tau\tau}^\oplus - \epsilon_{\mu\mu}^\oplus$
- $\delta_{e\mu}$
- $\delta_{e\tau}$
- $\delta_{\mu\tau}$

This approach is mostly independent of the underlying model and mediator mass ([source](https://pos.sissa.it/398/245/pdf)).

## Analyses

"What sets neutrino oscillation experiments apart from
other experiments is their unique capability to probe BSM
scenarios responsible for NSI independently of the new
physics energy scale $\Lambda$" ([source](https://pos.sissa.it/398/245/pdf)).

[DeepCore](deepcore.md) is most sensitive to $\epsilon_{\mu\tau}^\oplus$, but can constrain all effective NSI parameters ([source](https://pos.sissa.it/398/245/pdf)).

IceCube analyses of NSI are

- [OscNext NSI](oscnext-nsi.md)
- [DRAGON NSI](dragon-nsi.md)

There were also IceCube NSI analyses done in 2017 (IC) ([paper](https://link.springer.com/article/10.1007/JHEP01(2017)141)), 2018 (DC) ([paper](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.97.072009)), and 2020 (DC) ([paper](https://link.springer.com/article/10.1007/JHEP03(2020)105)) ([source](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006)).

Other experiments that have done NSI analyses are Super-K (2011) ([paper](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.84.113008)), MINOS (2013) ([paper](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.88.072011)), and COHERENT (2018) ([paper](https://link.springer.com/article/10.1007/JHEP07(2018)037)) ([source](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006)).
