
\subsubsection*{Annulus}
Idea:
Some plaintext.\\

Definition:
Some formal foo $y=x^2$ bar.\\

\subsubsection*{Antipodal}
\subsubsection*{Attached along a map}
TODO

\subsubsection*{Boundary}

\subsubsection*{Cantor set}
\subsubsection*{Cartesian space ${\mathbb R}^n$}
The set of all $n$-tuples, $\{ (x_1, x_2, ... , x_n) : x_i \in \mathbb{R} \}$.\\
The number $n$ is called the dimension of $\mathbb{R}^n$, and the $n$-tuples
can be thought of as vectors, since they form a natural vector space.\\
The set is typically augmented with the "Usual Topology", or sometimes the
"Euclidean Topology", whose basis is the set of all balls,
$\{ (x_1, x_2, ..., x_n) : \sqrt{x_1^2 + x_2^2 + ... + x_n^2} < r, r > 0 \}$.
Equivalently, the topology can be defined so that a subset $U$ is open if and only
if for all $u\in U$, there is a ball $B_r$ so that $u \in B_r \subseteq U$.
If no topology on the space is mentioned it is assumed to be the Usual.

\subsubsection*{Cell complex}
\subsubsection*{Cell $e^n$}
\subsubsection*{Cell structure}
\subsubsection*{Component}
\subsubsection*{Compact}
\subsubsection*{Cone} The Cone of a space $X$, is thought of as extending the
space into a cylinder, and then collapsing one end to a point.  So the Cone
is $CX = (X \times I) / (X \times \{0\})$.  



\subsubsection*{Contractible space} A Topological Space is called Contractible
iff the identity map on the space is homotopic to a constant map.  For example,
the Euclidean space of any dimension is Contractible to any point,
the circle is not Contractible, a disconnected set is not Contractible.  

\subsubsection*{CW-pair}
\subsubsection*{CW complex}

\subsubsection*{Deformation retraction}
A homotopy $(I\times X)\to X$
between the identity $\mathrm{id}_X:X\to X$ and a retract $r:X\to A$.

I.e. a deforming of the identity by shrinking its image.

\url{https://en.wikipedia.org/wiki/Retraction_(topology)}

\subsubsection*{Dimension of a CW complex}
\subsubsection*{Disc ${\mathbb D}^n$}
Notes:\\
$I:=D^1$ is the interval used for the definition of a homotopy.

\subsubsection*{Disjoint union}
The Disjoint Union is most properly described in terms of universal properties,
but because of that it has many equivalent concrete descriptions.  So we pick
a totally arbitrary definition, the Disjoint Union of a collection of sets,
$X_i$, indexed by $i\in I$, is just $\bigcup_{i\in I} \bigcup_{x\in X_i} (i, x)$.
This is usually written $\bigsqcup_{i\in I} X_i$, or you could write it as a
binary operation, $A \sqcup B$.\\
Taking a concrete example the disjoint union of $\{a, b\}$ and $\{b, c\}$ is
$\{(0,a), (0,b), (1,b), (1,c)\}$ if the sets are indexed by $0,1$.
This is just a way of forcing sets to be disjoint before we take their unions,
the reason for this is that if an element is in more than one of the sets,
normal unions forget this multiplicity, and so it associates that element to
"connecting" the sets it's in.  This is usually undesirable, so we force the
repeating elements to be different, just by taking ordered pairs with different
first component.\\
In practice you could imagine two different topological spaces, the real line
$\mathbb{R}$ and the unit interval $I$.  The union of these two is just absorbed
by $\mathbb{R}$, but we dont want to forget about the other set we started with
and this is accomplished with the disjoint union.  

\subsubsection*{Equivalence relation}

\subsubsection*{Genus}
\subsubsection*{Graph}
x

\subsubsection*{Homeomorphic}
\subsubsection*{Homotopy}
Continuous $H\colon (I\times X)\to Y$.\\

This can also be expressed as\\
$\bullet$ families into continuous functions $h\colon I\to (X\to Y)$ (such that $H\colon (I\times X)\to Y$ is also continuous.)\\
resp.\\
$\bullet$ neighboring paths of point $p\colon X\to (I\to Y)$ (such that $H\colon (I\times X)\to Y$ is also continuous.)

Here $I=[0,1]$ is the interval and we speak of a homotopy between the functions $h(0)$ and $h(1)$.
Then $h(0)$ and $h(1)$ are homotopic.

\url{https://en.wikipedia.org/wiki/Homotopy}

\subsubsection*{Homotopy equivalence}
A pair $f\colon X\to Y$ and $g\colon Y\to X$ such that \\
$g\circ f$ is homotopic to the identity on $X$ \\
and also $f\circ g$ is homotopic to the identity on $Y$.

I.e. both composition maps are allowed to be continuous deformations of the identity.

In contrast, one gets homeomorphisms (continuous bijections) when one requires the compositions to be exactly identities.

\subsubsection*{Homotopy extension property}
\subsubsection*{Homotopy Type}
\subsubsection*{House with two rooms}

\subsubsection*{Inclusion map}
...

$A\subset X$

$\iota\colon A\to X$

$\iota(x):=x$

Is injective. In a diagram, the arrow is often written with a hook (as in $\hookrightarrow$).

\subsubsection*{Infinite sphere ${\mathbb S}^\infty$}

\subsubsection*{Join}

\subsubsection*{Klein bottle}

\subsubsection*{Möbius band}
\subsubsection*{Mapping cylinder}

\subsubsection*{Neighborhood} A Neighborhood of a point $x$, is just an open set
containing that point $x$ under the given Topology.

\subsubsection*{Null-homotopic}
A function is null-homotopic if it's at an end of a null-homotopy.

\subsubsection*{Null-homotopy}
A homotopy with one end a constant function (mapping everything into a point)

\subsubsection*{Path-component}
\subsubsection*{Product of cell complexes}
\subsubsection*{Projection n-space ${\mathbb C}P^n$}
\subsubsection*{Projection n-space ${\mathbb R}P^n$}

\subsubsection*{Quotient map}
\subsubsection*{Quotient space}
TODO

\subsubsection*{Reduced suspension}
\subsubsection*{Rel}
\subsubsection*{Relation of homotopy among maps $X\to Y$}
\subsubsection*{Retraction}
A left-inverse to an inclusion.

$r\colon X\to A$

$r\circ\iota=\mathrm{id}_A$

Essentially dual to a section.

\url{https://en.wikipedia.org/wiki/Retraction_(topology)}

\subsubsection*{Simplex}
\subsubsection*{Skeleton}
\subsubsection*{Subcomplex}
\subsubsection*{Subspace of ${\mathbb R}^n$}

\subsubsection*{Torus ${\mathbb T}^n$}
TODO


\subsubsection*{Smash product}
\subsubsection*{Sphere ${\mathbb S}^n$}
\subsubsection*{Suspension} The Suspension of a space $X$, can be thought of
like the cone of $X$, but instead of identifying only one end, we identify both.
So the Suspension of $X$ is $SX = ( X \times I ) / \sim$, with $(x_1, 0) \sim (x_2, 0)$
and $(x_1, 1)\sim(x_2, 1)$ for any $x_1, x_2 \in X$.

\subsubsection*{Wedge sum} The Wedge Sum of two spaces $X,Y$ is denoted $X\vee Y$.
It is thought of as the space which contains a copy of $X$ and a copy of $Y$ so
that the copies touch each other at one point.  More formally, given $X,Y$, the
wedge sum is formed by taking two points, one from $X$, one from $Y$, called
$x_0, y_0$ respectively.  And then quotient the disjoint union of $X,Y$ by
identifying the image of $x_0$ and $y_0$.
