# NSI

Non-standard neutrino interactions.

## Theory

There's a brief theory overview in [Thomas-DRAGON-2021](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006).

A possible [BSM](bsm.md) effect driven by physics at a higher energy scale $\Lambda$ that manifests at lower energies through sixth-order operators in the extended SM field theory ([Ohlsson-nsi-2013](https://iopscience.iop.org/article/10.1088/0034-4885/76/4/044201)) (check).

NC NSI manifests through impacts on the forward scattering between neutrinos and charged fermions in the Earth ([matter effects](matter-effects.md)) ([Bhupal-nsi-2019](https://scipost.org/SciPostPhysProc.2.001/pdf)).

The existence of NSI effects may resolve tensions in the standard [oscillation](oscillation.md) parameters ([Esteban-nsitension-2020](https://arxiv.org/pdf/2004.04745.pdf)). Additionally, detection or exclusions of NSI is relevant for interpretations of measurements of the oscillation parameters ([Bhupal-nsi-2019](https://scipost.org/SciPostPhysProc.2.001/pdf)) (check).

Our approach parametrizes the effect of NSI on the matter potential through six effective coupling parameters:

| Parameter                    | Label                                |
| ---------------------------- | ------------------------------------ |
| $\epsilon_{e\mu}^\oplus$     | "[flavor-violating](flavor-changing-neutral-current.md)"                   |
| $\epsilon_{e\tau}^\oplus$    | "flavor-violating"                   |
| $\epsilon_{\mu\tau}^\oplus$  | "flavor-violating"                   |
| $\epsilon_{ee}^\oplus$       | "[flavor-universal](flavor-universality.md)"/"flavor-diagonal" |
| $\epsilon_{\mu\mu}^\oplus$   | "flavor-universal"/"flavor-diagonal" |
| $\epsilon_{\tau\tau}^\oplus$ | "flavor-universal"/"flavor-diagonal" |

where $\epsilon_{\alpha\beta}^\oplus \approx \epsilon_{\alpha\beta}^e + \epsilon_{\alpha\beta}^p + Y_n^\oplus\epsilon_{\alpha\beta}^n$ ([Thomas-DRAGON-2021](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006)).

All these parameters are potentially complex ([Thomas-DRAGON-2021](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006)):

$$
\begin{align*}
    \epsilon_{\alpha\beta}^\oplus &= |\epsilon_{\alpha\beta}^\oplus|e^{i\delta_{\alpha\beta}}
\end{align*}
$$

For some reason, you can subtract off $\epsilon_{\mu\mu}^\oplus \times \mathbf{1}$ to reduce the parameters to five, and then the Hamiltonian is described by a total of eight real parameters ([Thomas-DRAGON-2021](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006)):

- $\vert\epsilon_{e\mu}^\oplus\vert$
- $\vert\epsilon_{e\tau}^\oplus\vert$
- $\vert\epsilon_{\mu\tau}^\oplus\vert$
- $\epsilon_{ee}^\oplus - \epsilon_{\mu\mu}^\oplus$
- $\epsilon_{\tau\tau}^\oplus - \epsilon_{\mu\mu}^\oplus$
- $\delta_{e\mu}$
- $\delta_{e\tau}$
- $\delta_{\mu\tau}$

The parameters with minus signs in them are called the "[nonuniversality](flavor-universality.md) strengths" ([Thomas-DRAGON-2021](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006)).

This approach is mostly independent of the underlying model and mediator mass ([Farzan-nsi-2018](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006)) (check).

## Analyses

"What sets neutrino oscillation experiments apart from other experiments is their unique capability to probe BSM scenarios responsible for NSI independently of the new physics energy scale $\Lambda$" (– Thomas's paper) ([Farzan-nsi-2018](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006)) (check).

[DeepCore](deepcore.md) is most sensitive to $\epsilon_{\mu\tau}^\oplus$, but can constrain all effective NSI parameters ([Thomas-DRAGON-2021](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006)).

IceCube analyses of NSI are

- [OscNext NSI](oscnext-nsi.md)
- [DRAGON NSI](dragon-nsi.md)

There were also IceCube NSI analyses done in 2017 (IC) ([Salvado-ICnsi-2017](https://link.springer.com/article/10.1007/JHEP01(2017)141)), 2018 (DC) ([IC-ICnsi-2018](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.97.072009)), and 2020 (DC) ([Demidov-ICnsi-2020](https://link.springer.com/article/10.1007/JHEP03(2020)105)) ([Thomas-DRAGON-2021](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006)).

Other experiments that have done NSI analyses are Super-K (2011) ([SuperK-SuperKni-2011](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.84.113008)), MINOS (2013) ([MINOS-MINOSnsi-2013](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.88.072011)), and COHERENT (2018) ([Denton-COHERENTnsi-2018](https://link.springer.com/article/10.1007/JHEP07(2018)037)) ([Thomas-DRAGON-2021](https://journals.aps.org/prd/pdf/10.1103/PhysRevD.104.072006)).
