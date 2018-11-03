+++
title = "Automating Recursive Definitions and Termination Proofs in Higher-Order Logic"
date = 2009-07-09

authors = ["Alexander Krauss"]
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Dissertation. Technische Universität München"
#publication_short = "Automated Reasoning (IJCAR 2006)"

# Abstract and optional shortened version.
abstract = "The aim of this thesis is to provide an infrastructure for general recursive function definitions in a proof assistant based on higher-order logic (HOL) that has no native support for recursion or pattern matching.\n\n In the first part we develop a tool that automates recursive function definitions and provides appropriate proof rules for them. Compared to previous work, our package supports the definition of partial functions, modeling the domain of the function by an inductive domain predicate. An automatically-generated partial induction rule makes partial correctness proofs independent from termination proofs. This modularity considerably facilitates termination arguments for nested recursions.\n\n The second part addresses the problem of automatically solving the termination proof obligations that arise from function definitions. Methods from the literature can be applied, but require significant adaptation to the specific needs of our setting: They must produce full formal proofs and work relative to a rich interactive theory. Our approach encompasses a rule-based selection of measure functions, a simple control-flow analysis inspired by the dependency-pairs approach, and a modified version of the size-change principle based on certificates. A formalization of the full size-change principle is also provided. \n\n In the third part we discuss how pattern matching, which occurs frequently in functional programming, can be supported in HOL function definitions. We present a very general form of pattern matching, where arbitrary expressions can serve as patterns. We show how such patterns can be encoded using a custom matching combinator and how their consistency can be expressed in proof obligations.\n\n We also study the problem of transforming ML-style sequential pattern matching into minimal sets of independent equations, such that they are consistent in HOL. We relate the problem to the minimization problem for propositional DNF formulas and show that it is $\\Sigma_2^P$-complete. We then develop a concrete algorithm that computes minimal patterns.\n\n As another application of the new set of tools, we show how user-specified induction schemes can be generated from simpler properties, which often makes their proofs fully automatic."
abstract_short = ""

# Links (optional).
url_pdf = "papers/krauss-thesis.pdf"

[[url_custom]]
    name = "Official Library Website"
    url = "http://nbn-resolving.de/urn/resolver.pl?urn:nbn:de:bvb:91-diss-20090722-681651-1-1"

+++
