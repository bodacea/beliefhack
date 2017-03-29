# Analysis of Competing Hypotheses

Analysis of Competing Hypotheses \(ACH\) came out of the CIA in the 1970s. Like abductive reasoning, its purpose is to assign a most probable explanation for a series of observations. ACH has 7 main steps:

* Hypothesis. Create a set of potential hypotheses. This is similar to the hypothesis generation used in hypothesis-driven development \(HDD\), but generally has graver potential consequences than how a system's usrs are likely to respond to a new website, and is generally encouraged to be wilder and more creative \(DHCP theory might come in useful for that\).
* Evidence. List evidence and arguments for each hypothesis.
* Diagnostics. List evidence against each hypothesis; use that evidence to compare the relatively llikelihood of different hypotheses.
* Refinement. Review findings so far, find gaps in knowledge, collect more evidence \(especially evidence that can remove hypotheses\).
* Inconsistency. Estimate the relative likelihood of each hypothesis; remove the weakest hypotheses.
* Sensitivity. Run sensitivity analysis on evidence and arguments.
* Conclusions and evidence. Present most likely explanation, and reasons why other explanations were rejected.

The matrix of evidence vs hypotheses is key in ACH. In real-world situations, this matrix is both large and sparse; other representations of it include belief networks \(Elsaessar\), with bet-like weights assigned to the input evidence \("value of information"\).

ACH can be a useful reasoning framework. Criticisms include biases introduced by misinformation, and by social bias of the person\(s\) constructing the grid. Basically, ACH reflects our own biases about the world, and it's hard work to build counter to those biases. ACH is also flat: it doesn't typically consider the hierarchies of hypotheses that often occur in the real world \(this is however covered in Structural ACH, SACH\); other variants include Collaborative ACH \(CACHE\).

## References

* [https://en.wikipedia.org/wiki/Analysis\\_of\\_competing\\_hypotheses](https://en.wikipedia.org/wiki/Analysis_of_competing_hypotheses)

* [https://cse.sc.edu/~mgv/reports/IA-05.pdf](https://cse.sc.edu/~mgv/reports/IA-05.pdf)



