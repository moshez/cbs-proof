Equivalence
===========

Relations
---------

Assume :math`A` is a set.
We write :math:`A x A` for the
list of all ordered pairs from :math:`A`.
A relation on :math:`A` is a subset
:math:`R` of :math:`AxA`.

Equivalence Relation
--------------------

We will sometimes write
:math:`x R y` for :math:`(x,y) \in R`.
We name several properties of relations:

Reflexive: a relation is reflexive if
:math:`x R x` for every :math:`x` in :math:`A`.

Symmetric: a relation is symmetric if
:math:`x R y` implies that :math:`y R x`.

Transitive: a relation is transitive if
:math:`x R y` and :math:`y R z` implies that
:math:`x R z`.

A relation which is reflexive, symmetric and transitive
is called an equivalence relation.

Partition
---------

Let :math:`A` be a set, and let :math:`P` be a set
of subsets of :math:`A`. If every element of :math:`A`
belongs to at least one element of :math:`P`, and the
intersection of any two distinct elements of :math:`P`
is empty, :math:`P` is called a partition of :math:`A`.

Relationship between equivalence and partition
----------------------------------------------

If we have a relation, we can define the set of equivalence
classes: :math:`[x] = { y | y R x}`.

TODO: proof that this is a partition.

If we have a partition, we can define a relation:
:math:`x R y` if and only if there exists :math:`p \in P`
such that :math:`x,y\in p`.

TODO: prove that this is an equivalence relation
