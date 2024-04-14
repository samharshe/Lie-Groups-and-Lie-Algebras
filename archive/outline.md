- basic definitions.
  - MANIFOLDS.
    - neighborhood.
    - topology.
    - open.
    - basis of a topology.
    - second countable.
    - Hausdorff.
    - open cover.
    - locally Euclidean.
  - MATRIX GROUPS.
    - GL(n).
    - SL(n).
    - SO(n, R).
    - SU(n, C).
    - Sp(n).

- manifolds.
  - definitions of smooth manifolds.
    - examples:
      - R^n.
      - smooth functions.
      - S^1.
      - non-manifold: cross.

- matrix groups.
  - GL(n) is the maximal matrix group.
  - prove that the following are matrix subgroups
    of GL(n):
    - SL(R) and SL(C).
    - SO(R) and SU(C).
    - Sp(2n).

- matrix Lie groups.
  - naive definition 1: matrix groups and Lie group. 
  - naive definition 2: subgroup of a Lie group
    and an open subset of smooth manifold
    group. (subgroup implies group. inherits
    smooth inversion and composition maps from
    supergroup. open subset of smooth manifold
    implies smooth manifold.)
  - definition 3: closed under nonsingular limits.
    (deferring proof that this coincides with our
      other definition of Lie groups until the
      end.)
  - GL(n) is a def1 matrix Lie group: manifold structure.
  - examples: classical Lie matrix groups are
    groups and also open subsets of GL(n) (using def2).
  - Lie group homeomorphisms.


- matrix exponential & matrix logarithm.
  - matrix exponential.
    - Hilbert-Schmidt norm.
    - convergence of matrix exponential.
  - convergence of complex logarithm function.
  - convergence of complex matrix logarithm function.
  - every invertible matrix can be written as e^X
    for a matrix X in M(n, C).
  - matrix exponential commutative diagram.
   
- Lie algebras.
  - bracket defined as commutator.
  - proof: properties of Lie bracket.
  - Lie algebra homomorphism.
  - Lie subalgebra.
  - homomorphism between Lie groups induces a
    homomorphism between Lie algebras.
  - not v.v.
  - limitations of Lie algebras: when we lose
    information.
      - exp is a bijection for G compact.
      - every Lie algebra is given by a Lie group.
      - the exponential map for a matrix Lie group
        G does not necessarily map g onto G.
        Furthermore, the exponential map may not
        be one-to- one on g, as may be seen, for
        example, from the case g = su(2) (Hall
        67).
      - simply connected Lie groups are
        completel:Y determined (up to isomorphism)
        by their Lie algebras (Foundations of
        Differentiable Manifolds and Lie Groups 84)
  - Cartan's theorem: any closed subgroup H of a
    Lie group G is a Lie subgroup (and thus a
    submanifold) of G.
  - proof of Campbell-Baker-Hausdorff.

- special results.
  - not all Lie groups are matrix Lie groups:
    Heisenberg group quotiented out by a certain
    discrete group. (https://bit.ly/43ycG6P)
  - however, it is true that all compact Lie groups
    are matrix groups, as a consequence of the
    Peter-Weyl theorem.
  - it is also true that every finite-dimensional
    Lie group has a finite-dimensional Lie algebra
    𝔤 which is a matrix algebra. (this is Ado's
    theorem.)
  - not all topological groups are Lie groups:
    rationals.
  - not all smooth manifolds that are groups are
    Lie groups: S^2.
