# Learning pronoun case from distributional cues

## What is this project?

Case is an abstract grammatical feature that indicates the argument relationship in a sentence. There are three cases in English pronouns: nominative ('I', 'he', 'she', 'they'...) which is used as the subject, accusative ('me', 'him', 'her', 'them'...) which is used as the object, and genitive ('my', 'his', 'her', 'their'...) which is used before a noun. Young children are able to use different cased pronouns correctly at a very young age (before age of 2). The question is: How did they learn when to use which pronoun? 

One possible answer is that, they might learn it from the context of different pronouns. For example, "Let X go", X is likely to be an accusative pronoun ('me'), whereas in "Can X go", X is likely to be a nominative pronoun ('I'). This project tested if the "a X b" frame can effectively distinguish three cases of English pronoun. 

## Overview
### data: 
6 parents' corpora data from CHILDES

### input: 
"a X b", (e.g. "let _ go")

### output: 
the case of X (e.g. accusative)

### model: 
simple feedforward neural network

## Publication
Ma, X.,Chodorow, M., Valian, V. (2020). Learning Pronoun Case from Distributional Cues: Flexible Frames for Case Acquisition. In Proceedings of the Workshop on Cognitive Modeling and Computational Linguistics, (pp. 66-74) <a href = "https://xiaomeng-ma.github.io/13_Paper.pdf" target = "_blank" style = "color: red"> Download</a>
