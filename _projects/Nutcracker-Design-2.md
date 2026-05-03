---
layout: project
title: Nutcracker Design 2
description: Added information to nutcracker design
technologies: []
image: /assets/images/Nutcracker.png
---

### Assumptions

- Each handle behaves like a cantilever beam.
- Loads act transverse to the beam.
- Ignore axial forces.

Maximum deflection is at the handle tip (where you grip):

- For a cantilever beam, maximum deflection always occurs at the free end.
- Even though the biggest force from the nut is near the pivot, deflection accumulates along the beam. The farther from the fixed end, the more displacement builds up.

### Calculations

- L = 0.088 m
- δ_max = 0.02 L = 0.00176 m
- Cantilever beam: δ_max = F L^3 / 3EI
- F = 2178.84 N
- E I = 0.28 N

To minimize mass:

- Maximize E
- Maximize I

Material: Aluminum — E = 70 GPa

Cross section: Hollow rectangular tube

- Good strength-to-weight ratio
- High I with low mass

### Images

- Main design image: <img src="{{ site.baseurl }}/assets/images/Nutcracker.png" alt="Nutcracker design" />
- Deflection diagram: <img src="{{ site.baseurl }}/assets/images/Deflected.png" alt="Deflection diagram" />

### Collaboration

I use ChatGPT to come up with my image.
