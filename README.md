This repository contains a single notebook demonstrating the automatic windowing procedure (also called Gamma method) used to obtain improved error estimates for the integrated autocorrelation time of Markov chain data, introduced in Appendix C of [1] (see also [2] for further details). While the papers can be hard to digest, the method itself boils down to a few simple lines of code, repeatedly computing the autocorrelation time for increasing window sizes until a threshold criterion is reached.

[1] N. Madras and A.D. Sokal, The pivot algorithm: A highly efficient Monte Carlo method for the self-avoiding walk, J.Stat.Phys. 50, 109–186 (1988)

[2] U. Wolff, Monte Carlo errors with less errors, Comput.Phys.Commun. 156, 143-153 (2004)
