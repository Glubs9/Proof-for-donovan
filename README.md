I'm trying to prove Lemma 2 from the previous problems with non-termination.

We are going to be working on a system with at least the following rule $$
\frac{e_1 : A \rightarrow B , \text{ } e_2 : A}{e_1 \text{ } e_2 : B} $$
Assume a consistent system, i.e: one in which there is no x : $\bot$ . $$
\displaylines{
\text{theorem}  \\
(f : P \rightarrow \bot) \rightarrow (\text{P is uninhabited}) \\\\
\text{proof by contradiction: } \\
\text{assume P is inhabited. this means that there is at least one } p : P \\
\text{we can now construct} \\
\frac{f : P \rightarrow \bot, \text{ } p : P}{f \text{ } p : \bot} \\
\text{we now have an element of } \bot \text{ thus the system is inconsistent. } \\
\text{this is a contradiction with the assumption that we are working in a consistent system.} \\
\text{as we have reached a contradiction with the assumption that P is inhabiated,} \\
\text{p must be uninhabited } \square
} $$
