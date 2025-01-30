# Proposal for a new SMEFT basis

The goal of this proposal is to establish an altenative to the Warsaw basis for the Standard Model Effective Theory (SMEFT), where some of the operators are replaced by others. The proposed changes are the following:

$O_{lequ}^{(3)}$
================

**Proposed alternative:** $O_{\ell uqe}=(\bar \ell^i u)\epsilon_{ij}(\bar q^j e)$

**Reasons:**

- Tensor operators are kwnon to cause problems with $\gamma_5$ in NDR [refs to be added]. While the issue can be solved by using the BHMV scheme, there is no reason a priori to prefer the scalar operator over the tensor. The scalar operator also give simpler Dirac traces, also for BHMV, when performing calculations with this operator.

- There is no Standard Model (SM) extension where this operator is generated at tree-level.[^1] Instead, the operator $O_{luqe}$ is generated at tree-level by the scalar extensions $(\boldsymbol{3},\boldsymbol{2},7/6)$.[^2] When Fierzing $O_{luqe}$ into $O_{lequ}^{(3)}$ one has to introduce an evanescent shifts which are ambigous in NDR [ref to be added]. The ambiguity is further translated to matrix element computations with this operator. 

[^1]: The only exception is the rank-2 antysimmetric Lorentz tensor for which, to the best of my knowledge, a renormalizable Lagrangian is not known.

[^2]: Instead of $O_{\ell uqe}$, one could also use $O_{\ell qeu}=(\bar\ell \epsilon q^{c})(\bar e^c u), which is generated at tree level by the $S_1$ leptoquark.


$O_{\varphi \square}$
======================

**Proposed alternative:** $O_{DH}=(H^\dagger H)[(D_\mu H)^\dagger (D^\mu H)]$

**Reasons:**

- It seems strange to have an operator that is a linear combination with some of the terms proportional to the equations of motion (when expanding the derivatives). It would be preferable to have at most one derivate acting on a field whenever possible.

- This form of the operator aligns better with geometric extensions of the SMEFT.

- Operators such as $O_{\varphi \square}$, involving derivatives on products of fields, are not generating by any existing basis tool.


Operators containing field-strenght tensors
===========================================

**Proposed change:** Include a factor of the gauge coupling per field-strength tensor in the operator.

**Reasons:**

- In any matching and/or running result, field-strength tensors get accompanied by gauge couplings.

- It makes the perturbative couting more transparent. This becomes especially relevant in Monte Carlo tools and in evolution-matrix calculations for Renormalization Group running.


Operators with octet (or triplet) currents
==========================================

**Proposed change:** Remove the generator products in favor of cross-term singlet contractions. E.g. instead of $O_{qq}^{(3)}$ write $O_{qq}^\prime=(\bar q^\alpha \gamma_\mu q^\beta) (\bar q^\beta \gamma^\mu q^\alpha)$ and analogusly for the rest.

**Reasons:**

- It makes color algebra simpler.

- There is no phenomenological reason for prefering one form over the other.
