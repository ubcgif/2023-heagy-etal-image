---
title: 'Accelerating research with community-driven open-source software for geophysical inversions'
abstract: |
    An open-source model of development and dissemination of research facilitates reproducibility and enables research methods to be adapted, extended, and applied to new problems. Within geophysics, SimPEG is one such project for simulations and inversions of geophysical data. In this presentation, we will discuss how a modular, open-source approach to scientific software development is enabling research in applied geophysics, and how building on contributions from a community enables rapid exploration of new ideas.
---

```{image} ./images/pizza-box.png
:alt: Interdisciplinary problems
:width: 50%
:align: center
```

Many of the important geoscientific problems that we face, especially as a result of climate change, require communication of methods, data, and concepts amongst researchers and practitioners with different disciplines, backgrounds and expertise. Even within the discipline of geophysics, there are a spectrum of skills required to solve a problem. This can be facilitated by open-source communities and the tools they develop. Solving a geophysical inverse problem requires that we bring together numerical methods for simulation and optimization and combine those with knowledge of a given geologic context in order to produce a meaningful model of the subsurface. We started the SimPEG project with the aim of accelerating research and enabling researchers to build upon and contribute to a modular, flexible toolbox for solving problems in geophysics. At the core is a framework for finite volume forward simulations and gradient based inversions. It currently supports a range of geophysical data types, including gravity, magnetics, direct current (DC) resistivity, induced polarization, frequency domain and time domain electromagnetics (EM). For the inversion, there is flexibility to define different regularization functions for integrating relevant geologic information or auxiliary data and to choose various strategies for performing the optimization. Each component of the software is modular and accessible to the user which enables exploration and extension of the codebase.


```{image} ./images/framework.png
:alt: SimPEG framework
:width: 100%
:align: center
```

The modular style of development has helped accelerate the exchange of methods and ideas between researchers and disciplines within geophysics. For example, the implementation of sparse norms in SimPEG was first developed and tested with potential fields data. This enables us to recover compact bodies and/or sharp interfaces in the inversion. These sparse norms have since been applied in EM inversions, and even used to regularize time-lapse inversions. Further, having multiple methods in one place has simplified approaches for combining methods, such as in joint inversions.

The community of contributors and users consists of researchers, students, and industry professionals. The code-base is permissively licensed to allow commercial re-use, so companies can incorporate SimPEG code into their own code-bases, provided that it is acknowledged. This has facilitated technology transfer of research to industry, and enabled contributions from industry, such as recent improvements in the efficiency of the codebase. These collaborations have also opened up new areas in which research is required. To facilitate education, we have built educational resources for undergraduate, graduate and professional courses such as the 2017 SEG Distinguished Instructor Short Course. Such resources can serve members of the geophysics community, and importantly can be used to help facilitate conversations with geologists, engineers and others about where geophysics can contribute to societal problems.

Developing solutions to the pressing geoscientific challenges society faces will undoubtedly involve methodological improvements in inversions and machine learning, but importantly will require a more interdisciplinary approach. Adopting open-source practices can be a powerful mechanism for facilitating collaborations across disciplines and enabling new advancements to be used and extended at an accelerated pace.
