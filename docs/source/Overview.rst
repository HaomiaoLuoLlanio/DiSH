
Overview
========

Modeling aids scientists in understanding system behavior and predicting future states via expert knowledge, literature, and experimental data. Large biological networks may pose challenges in determining all kinetic parameters, leading to qualitative, logical, and discrete modeling approaches. Logical models utilize Boolean variables with two discrete levels (1 for high concentration/active and 0 for low concentration/inactive) and logic operators to represent element concentration or activity. However, this restricts scenarios involving diverse effects, such as multiple drug doses or protein activity levels. Discrete models with more than two distinct levels address this limitation while avoiding the need for all kinetic parameters found in continuous models. In discrete models, the change in an element's value is determined by the difference between its positive and negative regulation scores. If the difference is non-zero, the element's value changes in the same direction as the difference, typically by one level.

Model introduction
===================

The DiSH2.0 (Discrete, Stochastic, Heterogeneous) modeling and simulation framework integrates both logical and algebraic update functions, enabling flexible modeling based on available qualitative and quantitative information. Unlike previous approaches, DiSH2.0 employs discrete variables to represent element values, facilitating the incorporation of any necessary number of discrete levels within a single model. The framework introduces features like memory in element update rules and regulation weights to account for varying effects across regulators and levels, enhancing model accuracy and flexibility. A compatible simulator supports deterministic and stochastic simulation schemes, expanding the applicability of hybrid models to both logical and discrete modeling contexts.

DiSH2.0's compatibility with various tools enables seamless integration into existing workflows for interaction extraction, filtering, network assembly, model verification, and validation, streamlining the modeling process in biological research.

Simulation features
====================

- DiSH2.0 employs discrete variables to represent element values.
- Features memory in element update rules.
- Supports regulation weights to account for varying effects across regulators and levels.
- Compatible with deterministic and stochastic simulation schemes.
- Seamless integration into existing workflows for interaction extraction, filtering, network assembly, model verification, and validation.

