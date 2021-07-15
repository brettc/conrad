# Conrad: a minimalist simulation of evo-devo

`Conrad` provides a toy world with simple analogs of gene regulation, multicellular development and evolutionary change. You can design experiments that evolve targeted cellular activity or two-dimensional patterns, then examine the resulting gene networks, perform knockouts, or subject the evolved genes to novel environments. `Conrad` saves the entire evolutionary history of an experiment, so you can retrace the precise steps that led to a particular adaptation, or start another experiment from any point in time.

`Conrad` is written in [Python][1] (with an optional C++ module for speed). Experiments and analyses can be easily scripted, and [Jupyter Notebooks][2] can be used to interactively explore ideas and examine results.

## What’s in the box?

`Conrad`’s model of evo-devo includes the following:

* Gene Regulation: A Boolean model of gene regulation that generates a discrete time series of Boolean cellular activity.
* Fitness evaluation: Fitness is measured by exposing genes to a variety of different environments and comparing the resulting cellular activity with a target defined by the user.
* Evolution: `Conrad` has a simple asexual model of evolutionary change, with control over population sizes, mutation rates, and the generation of regulatory binding sites and interactions.
* Multicellular Development: By duplicating the genes across a grid of interacting cells, `Conrad` can evolve a sequence of patterns

`Conrad` also provides tools to help run reproducible experiments and examine the results:

* You can script experiments and run replicates in parallel. Experiments can be stopped and restarted, and any run of an experiment is reproducible (OS specific).
* Generations, individual genomes, or entire lineages can be quickly loaded for examination.
* `Conrad` can automatically draw an annotated gene regulatory network for any genome.
* Ever step of cellular activity during development can be inspected, and multicellular development rendered with a sequences of patterns of cellular activity.
* A variety of metrics can be used to categorise and contrast the role that different genes play during development.
* Any metrics, (including your own) can be generated for an entire evolutionary history, even after the simulation has finished.

## What is it for?

`Conrad` is a cognitive tool to aid thinking about key ideas and concepts in the study of evo-devo. It does this by attempting to replicate analogs of ideas such as genetic causation, robustness, evolvability, developmental drift, master genes, positional information, but with complete access to inspect, measure, and control, every aspect of the world.

## Who am I?

I am a Philosopher of Science with an interest in the evolution of complexity and a background in programming. I currently work for [Dragonfly Data Science][dfly]. I live in New Zealand with my wife and two kids.

## Why “Conrad”?

The name comes from [Conrad H. Waddington][ch], a prominent biologist in the early days of evolutionary developmental biology. He is perhaps well known for his [pictures][pics] of the [epigenetic landscape][epi]. I am no historian, but I find Waddington a fascinating figure. I hope he would have liked this simulation.


[1]:	https://python.org
[2]:	https://jupyter.org
[epi]:	https://embryo.asu.edu/pages/epigenetic-landscape
[pics]: https://www.sciencedirect.com/science/article/abs/pii/S1369848613000897
[dfly]: https://www.dragonfly.co.nz
