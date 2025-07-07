# Multi-Hybrid Swarm Optimization

### Piotr Urbańczyk
MEng thesis in computer science -- data science, written under the supervision of Aleksander Byrski

    @phdthesis{urbanczyk2025multihybrid,
	  title={Multi-Hybrid Swarm Optimization},
	  author={Urbańczyk, Piotr},
	  year={2025},
	  school={AGH University of Krakow}
	}


My thesis explores informed diversity-enhancing strategies for Particle Swarm Optimization. To gain a deeper understanding of my research, I invite you to look through the piece or read the [abstract](#Abtract) provided below.

[![github](https://img.shields.io/badge/GitHub-purbancz-181717.svg?style=flat&logo=github)](https://github.com/purbancz) [![twitter](https://img.shields.io/badge/Twitter-@purbancz-00aced.svg?style=flat&logo=twitter)](https://twitter.com/purbancz) [![linkedin](https://img.shields.io/badge/LinkedIn-Piotr_Urbańczyk-00aced.svg?style=flat&logo=linkedin)](https://www.linkedin.com/in/piotr-urba%C5%84czyk-9943ab17a/) [![website](https://img.shields.io/badge/Website-Piotr_Urbańczyk-5087B2.svg?style=flat&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHg9IjBweCIgeT0iMHB4IiB3aWR0aD0iMTAwIiBoZWlnaHQ9IjEwMCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGQ9Ik0gMTIgMi4wOTk2MDk0IEwgMSAxMiBMIDQgMTIgTCA0IDIxIEwgMTAgMjEgTCAxMCAxNCBMIDE0IDE0IEwgMTQgMjEgTCAyMCAyMSBMIDIwIDEyIEwgMjMgMTIgTCAxMiAyLjA5OTYwOTQgeiIgZmlsbD0iI2ZmZiI+PC9wYXRoPgo8L3N2Zz4=)](https://www.copernicuscenter.edu.pl/en/person/urbanczyk-piotr-2/)

#### Abtract

This thesis addresses the premature convergence limitation of Particle Swarm Optimization (PSO), especially in complex, high-dimensional problems. It introduces and evaluates novel informed diversity-enhancing strategies to improve PSO's exploration capabilities. The proposed methodology involves a family of mechanisms based on problem-specific landmarks (best/worst solutions) that apply attraction or repulsion forces within velocity updates. These strategies are categorized into opposing-best (repulsion), attraction-to-worst (negative learning), and opposing-worst (reverse learning) behaviors, forming both single-role algorithms and three multi-hybrid PSO paradigms: disjoint-role, component-specific, and fully flexible. Rigorous empirical testing on diverse benchmark functions up to 1000 dimensions demonstrates that these strategies, particularly multi-hybrid variants like component-specific HybridPartialDisjointPSO, significantly outperform standard PSO and simple perturbation methods in solution quality, convergence, and robustness. Variants employing attraction-to-worst strategies also showed strong, consistent performance. This research establishes that informed, role-based diversity mechanisms are, in most cases, more effective than random perturbations, offering scalable and robust PSO enhancements for complex optimization by better balancing exploration and exploitation.


#### Keywords
evolutionary computation, swarm intelligence, hybrid metaheuristics, Particle Swarm Optimization (PSO)