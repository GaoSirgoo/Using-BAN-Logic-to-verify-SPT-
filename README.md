<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>

## Ban-Logic for Security-Packet-Transmission
### BAN logical notation
BAN logical notation used in the paper as followed:
1. \\(P\vert^\equiv X\\): *P* believes *X*;
2. \\(P\vert\Rightarrow X\\): *P* controls *X*; 
3. #(X): *X* is fresh;
4. {X}<sub>K: the ciphertext of *X* encrypted by the key *K*.
##  BAN logical postulates
We only need two rules for SPT:
1. Nonce-verification rule:
**R4**: 
\\(\frac{P\vert^\equiv X,P\vert^\equiv Q\vert\backsim X}{P\vert^\equiv Q\vert^\equiv X}\\). States that if P believes that X could have been uttered only recently and that Q once said X, then P believes that Q believes X.
2. Jurisdiction rule:
**R5**:
\\(\frac{P\vert^\equiv Q\vert^\Rightarrow X,P\vert^\equiv Q\vert^\equiv X}{P\vert^\equiv X}\\). States that if P believes that Q has jurisdiction over X and P trusts Q on the truth of X,then P believes X.

## Verifying Authentication process for SPT with BAN logic:





