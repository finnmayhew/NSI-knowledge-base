# OscNext NSI

An ongoing IceCube [NSI](nsi.md) analysis ([wiki](https://wiki.icecube.wisc.edu/index.php/OscNext_NSI)).

Follows the precedent of the [DRAGON NSI](dragon-nsi.md) analysis.

Performed by Elisa Lohfink (see [Elisa-thesis-2023](https://seafile.rlp.net/f/f660b4d52dc04953bb36/)).

Uses 8 years of [DeepCore](deepcore.md) data from 5.6 to 100 GeV ([Elisa-thesis-2023](https://seafile.rlp.net/f/f660b4d52dc04953bb36/)).

[[PISA]] on its own cannot handle the NSI parameter space for a few reasons. [MCMC](mcmc.md) is used in place of minimization via [emcee](emcee.md). This will allow simultaneous evaluation of all NSI parameters ([Elisa-thesis-2023](https://seafile.rlp.net/f/f660b4d52dc04953bb36/)).

Uses
$$
TS = \chi^2_\text{mod} = \sum_{i \in \text{bins}}\frac{(n_i^\text{exp} - n_i^\text{obs})^2}{n_i^\text{exp} + (\sigma_i^\text{exp})^2} + \sum_{j \in \text{prior}}\frac{(\Delta s_j)^2}{\sigma_{s_j}^2}
$$
([Elisa-thesis-2023](https://seafile.rlp.net/f/f660b4d52dc04953bb36/))

## Status of the analysis when I received it

Frequentist:

- Blind fit p-values:
  
Parameter | p-value
-|-
$\epsilon_{e\mu}^\oplus$ | 4.4%
$\epsilon_{e\tau}^\oplus$ | 4.6%
$\epsilon_{\mu\tau}^\oplus$ | 5.4%
$\epsilon_{ee}^\oplus - \epsilon_{\mu\mu}^\oplus$ | not fit
$\epsilon_{\tau\tau}^\oplus - \epsilon_{\mu\mu}^\oplus$ | 4.8%

Bayesian:

- Performed MCMC with all magnitudes free, but not phases, on highstats

## Steps forward

Frequentist:

- Switch to using dedicated systematic sets for each NSI parameters
- Test minimizer configuration
  - Shiqi: talk to astronomer postdocs on the third floor
- Improve FC computation
  - See work by Elisa and Alex
- Find a way to include $\epsilon_{ee}^\oplus - \epsilon_{\mu\mu}^\oplus$? (see Elisa 7.6.2)

Bayesian:

- Improve sensitivity to complex phases somehow
- Test ultrasurfaces
- Determine relevant checks on result
  - Shiqi suggests inject/recover, pre-fit data/MC, sensitivity

General:

- Point to FLERCNN sample
- Extend energy range if feasible (up to 300 GeV?)
- Switch to SPice-BFRv2 (see Elisa 7.4.2)
  - from SPice 3.2.1
  - requires new MC sets (do these exist yet?)
  - Would obsolete the $N_\text{brf}$ parameter
- Reevaluate energy binning
- Check whether or not cutting at the horizon makes a difference for NSI
- Check flux binning (low priority)
  - Shiqi: after doing this, try doubling true flux and oscillations binning and check sensitivity (need to figure out what this means)
- Check PID binning (low priority)
- Make sure ultrasurfaces are up to date
