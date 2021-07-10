# Conrad: a minimalist simulation of evo-devo

`Conrad` provides a toy world with simple analogs of gene regulation, multicellular development and evolutionary change. You can design experiments that evolve targeted cellular activity or two-dimensional patterns, then examine the resulting gene interactions, perform knockouts, or expose the evolved genes to novel environments. `Conrad` saves the entire evolutionary history of an experiment, so you can retrace the precise steps that led to a particular adaptation, or restart another experiment from any point.

`Conrad` is written in [Python][1] (with an optional C++ module for speed). Experiments and analysis can be scripted, and [Jupyter Notebooks][2] can be used to interactively explore ideas and examine results.

## What’s in the box?

`Conrad` provides the following:

* Gene Regulation: A Boolean model of gene regulation that generates a discrete time series of Boolean cellular activity.
* Fitness evaluation: Fitness is measure by exposing genes to a variety of different environments and comparing the resulting cellular activity with a specified target.
* Evolution: `Conrad` has a simple asexual model of evolutionary change, with control over population sizes, mutation rates, and the generation of regulatory binding sites and interactions.
* 2D Multicellular Development: `Conrad` developmental system the same developmental system By embedding into the same genes regulatory control in the form of a simple 2D cellular automaton. `Conrad`Gene regulatory models are wired together, using several signalling models.

Tools:
* Parallel replicates.
* Automatic visualisation of gene networks and diffs
* Visual representations of developmental stage, and their evolutionary xxx
* Tracking of metrics over evo
* Information measures of causal xxxx.

## What is it for?

Despite the relatively simple combination of features, `Conrad` can be used to generate a wide variety of XXXX: 

* Plasticity. 
* Automatic generation of many genetic interactions.
* Knockouts can be performed on different 
* Transplanted 
* New populations can be generated

Plasticity, Robustness, Genetic Drift, Evolvability. 

`Conrad` attempts to provide a cognitive tool to aid thinking 

The evolution and development of multicellular form is one of the most striking processes in the biological world. Understanding the complex interaction between these empirical 

Conrad aim is provides just enough complexity to surface some of the same conceptual problems, but without the same problems of empirical 

My aim in creating `Conrad` were foremost to provide the means to explore conceptual stuff. My main aim is to provide a simulation that is powerful enough to *pose the same conceptual difficulties* in attempting to analyse or explain what is going on.

* One reason (but not the only) that the two first features are so simple, is that it enables relatively rapid evolution (on the order of 100,000s of generations), and does so in parallel.

No doubt there are those who think the simulation could have even less in it; there are certainly simpler attempts to capture evo-devo. Any thoughts or discussions about what could be taken would be great.

## Why does/doesn’t Conrad include *FEATURE X*

Not only are the implementations of these features vastly simplified, there is a great deal that has been left out. There are two reasons for that. The first is pragmatic: more complex models take more time.

## Who am I?

I am a philosopher of biology, not a biologist. 

Tools to control and interact with simulations.
* Control

The environment provides constraints.

`Conrad` provides an elementary evolvable world,. is to provide a evolutionary simulation 

Despite the simple implementation, the cells 

Things it has:
* There is not meant for cooperation or any interaction between the organisms..

## Answers to Questions.

* **Why “Conrad”?** The name comes from [Conrad H. Waddington][ch] , a biologist that layed the foundations for many evolutionary developmental biology. He is perhaps well known for the epigenetic landscape. I find Waddington a fascinating figure, XXXX. I hope he would have liked this simulation.

* **This isn’t really a minimalist simulation**. That isn’t a really a question. But yes, you are right. There are far simpler models that capture interesting.

* There

[1]:	https://python.org
[2]:	https://jupyter.org
