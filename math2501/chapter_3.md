# ***3.1*** 

> A ***set*** is a collection of objects called ***elements***. The ***universal set*** $U$ is a special set containing all elements under a particular discussion. The ***null set*** $\empty$ is the empty set (has no elements). The ***complement*** of a set is a set that contains elements within $U$ that lie outside of the set in question; for instance $\bar{A}$ is the set containing elements that are not in $A$.

> A ***subset*** is a set whose elements are found in another set. Formally, $A \subseteq B$; $A$ is a *subset* of $B$. A ***proper subset*** is the same as a subset but with additional elements; $A \subset B$ means that $A$ is a subset of $B$, but $B$ has additional elements. If a set is a *subset* of another set, then one of two things can occur: $A \subset B$ or $A = B$. 

> The ***union*** of two sets is the collection of elements in either or both; $A \cup B$. The ***intersection*** of two sets is the collection of elements that both sets have in common; $A \cap B$.  

|                      Important Set Laws                      |
| :----------------------------------------------------------: |
|                   $A \cap \empty = \empty$                   |
|                        $A \cup U = U$                        |
|                        $A \cap U = A$                        |
|                     $A \cup \bar{A} = U$                     |
|                   $A \cap \bar{A}= \empty$                   |
|                        $A \cup A = A$                        |
|                        $A \cap A = A$                        |
|                     $A \cup \empty = A$                      |
| DeMorgan's Union: $\bar{A} \cup \bar{B} = \bar{A} \cap \bar{B}$ |
| DeMorgan's Intersect: $\bar{A} \cap \bar{B} = \bar{A} \cup \bar{B}$ |

> The *difference* of two sets $A$ and $B$ ($A - B$) is a set containing only the elements in $A$ that are not in $B$. Another way to express this using set notation is $A - B = A \cap \bar{B}$.

> Two sets are ***mutually exclusive*** or ***disjoint*** if they have *no elements* in common. In set notation, $A \cap B = \empty$.

> A ***partition*** of the universal set $U$ is formed when any two sets from a collection of sets $S_{1}, S_{2}, ..., S_{n}$ yields the null set $\empty$ (***pairwise disjoint***) and their union $\cup$ is $U$. Formally, $A_{i} \cap A_{j} = \empty$ for $i \neq j$ and $U = A_{1} \cup ... \cup A_{n}$. In other words, sets are 'broken up' into pieces.

# ***3.2***

> An ***experiment*** is any procedure that can be repeated indefinitely and has a set of ***outcomes*** known as the ***sample space***. A ***random experiment*** is one that has more than one outcome; a ***deterministic experiment*** is one that has only one outcome.

> A ***sample space*** is the collection of *all* outcomes of an experiment and is often denoted by $S$. $S$ will be our universal set $U$.

| Experiment         | Sample Space                                            |
| ------------------ | ------------------------------------------------------- |
| Rolling one die    | $S = \{1, 2, 3, 4, 5, 6\}$                              |
| Flipping a coin    | $S = \{H, T\}$                                          |
| Rolling *two* dice | $S = \{(1,1) (1,2), ... (1,6), ..., (6,1), ... (6,6)\}$ |

> An ***event*** is a subset of the sample space $S$ (an outcome) and is denoted by $E$.

| Experiment   | Possible Events                                              |
| ------------ | ------------------------------------------------------------ |
| Roll one die | Let $E_{1} = $ even number is called -- $\therefore$ $E_{1} = \{2, 4, 6\}$. |

# ***3.3***

> A ***probability measure*** is a set-to-point function $P$ from the sample space to the unit interval $[0, 1]$. Essentially, it assigns each event $A \subseteq S$ a real number between $0$ and $1$ inclusive known as **probability of occurrence** (the probability the event will occur). If event $A$ does not occur, $P(A) = 0$; if event $A$ is a *certain event*, $P(A) = 1$.

> If $P(A)$ is close to $1$, $A$ is very likely to occur; if $P(A)$ is closer to 0, $A$ is very unlikely to occur.

> An ***axiom*** is an accepted or established principle (it's simply taken as given and requires no formal proof of its legitimacy).

| Probability Axioms                                      | Explanation                                                  |
| ------------------------------------------------------- | ------------------------------------------------------------ |
| *AXIOM 1.* $P(A)$ is defined for every $A \subseteq S$. |                                                              |
| *AXIOM 2.* $P(A) \geq 0$ for any event $A \subseteq S$. | $P(A)$ cannot be negative -- the smallest value for $P(A)$ is $0$ (it will never occur). |
| *AXIOM 3.* $P(S) = 1$.                                  | Since the sample space $S$ contains all possible outcomes, $S$ always occurs. Considering the experiment of rolling a die, the probability of the sample space $S = \{1, 2, 3, 4, 5, 6\}$ is $P(S) = 1$ since the outcome will be 1-6. |

