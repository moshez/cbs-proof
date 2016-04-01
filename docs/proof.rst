Proof
=====

We note CBS is equivalent to the following proposition:

Let :math:`f:A\to\A` is one-to-one, and denote the image
of :math:`f` by :math:`I_f`. If :math:`B` contains
:math:`I_f` and is contained by :math:`A`, it is as big
as :math:`A`

TODO: prove it.

Let us prove this proposition. Let :math:`E` be an equivalence
class of the relation induced by :math:`f`. If :math:`E` is not
a chain, :math:`E` is contained in :math:`B`.
Otherwise, assume :math:`x_0` is the non-image element of :math:`E`.
There are two options: :math:`x_0 \in B` or not. In the former
case, :math:`B` contains :math:`E`.

Now we define a function

:math:`g:A\to B` that is one-to-one and onto:

* If :math:`B` contains the equivalence class of :math:`x`, :math:`g(x) = x`

  * Note that this holds whether the class is a chain or not.
  
* Otherwise, :math:`g(x) = f(x)`

Since :math:`g` is either the identity or :math:`f` on each equivalence class,
and those are closed under :math:`f`, it is one-to-one. It remains to show it is onto.

TODO: prove this.
