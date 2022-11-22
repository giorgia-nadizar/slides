class: middle, center

# Voxel-based Soft Robots and other stories

.h10ex[![ERAL Lab logo](images/erallab-logo.png)]
.hspace5[]
.h10ex[![University of Trieste logo](images/sigillo-units.png)]

**Giorgia Nadizar**, giorgia.nadizar@phd.units.it

Evolutionary Robotics and Artificial Life Lab, University of Trieste, Italy

---

# Who am I?

- Computer Engineering background
- PhD student at the Evolutionary Robotics and Artificial Life Lab
(University of Trieste) under the supervision of Eric Medvet and Stefano
Nichele (from Østfold University College)
- Currently, PhD intern at Centrum Wiskunde & Informatica with Marco Virgolin

---

# Bio-inspired Embodied AI

- Why Embodied AI?
  - Intelligence developed within a body
  - Body as a substrate for computation → morphological computation
  - Body as "fuzzy" boundary between environment and brain

- How to achieve it?
  - Take inspiration from the biological world → mimic _evolution_

---

# ...in practice

**Evolutionary Computation** in various flavors

1. Evolutionary Robotics (ER) → our specialty back in Trieste
2. Symbolic Regression & Interpretable AI → currently at CWI

---
class: middle, center
name: ml-definitions

# Evolutionary Robotics

---

# Voxel-based Soft Robots (VSR)

Probably heard _waaaay_ too much about them, but just in case, let's recap

.center[
<video controls>
  <source src="videos/vsr-elephant.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
]

---

# Relevance

- Combination of softness and modularity → vast design freedom
- Reconfigurability, self-assembly → robot factory
- Embodied cognition paradigm → intelligence does not only reside in the brain
- Bio-inspired features → study real world phenomena for ALife

---

# VSRs in simulation

- Rigid bodies → endow with mass, prevent excessive deformation
- Spring → alter the area, mimic softness

.center[![VSR mechanical model](images/voxel-model.png)]

---

# How do they move?

- Contraction and expansion of each voxel → similar to muscles
- Control signal deriving from a controller
  - Open-loop → signal computed from a periodic function
  - Closed-loop → processes sensor readings

---

# Centralized neural controller


---

# Distributed neural controller


---

# Pruning


---

# Development

---

# Spiking Neural Networks


---
class: middle, center
name: ml-definitions

# Interpretability

---

# What does it have to do with Embodied AI?

- AI within a body, e.g., a robot → possibly great impacts on real world
- _Understanding_ how it works is of paramount importance

.center[![Terminator](images/terminator.jpeg)]

---

# Starting simple: interpretable symbolic formulae

- Symbolic Regression to find them → two objectives
  - Accurate → MSE, RMSE, $R^2$
  - Interpretable → ?

---

# Interpretability is subjective

.center[![ML-PIE](images/pie.png)]

---

# Findings

---

# Can we bring this to robotics?

Open question!

---

class: middle, center

# Thanks!

.center.h30ex[![Me as a robot](images/robot.png)]

<i class="fa fa-envelope" aria-hidden="true"></i> [giorgia.nadizar@phd.units.it](mailto:giorgia.nadizar@phd.units.it)
