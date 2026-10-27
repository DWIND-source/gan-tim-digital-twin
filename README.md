# GaN TIM Digital Twin — interactive demo

Interactive demo of a digital twin for thermal interface material (TIM) selection in a top-side-cooled GaN power package, prepared for the **EPTC 2026 Student Innovation Challenge**.

![Digital twin preview](preview.png)

**Live demo:** https://dwind-source.github.io/gan-tim-digital-twin/

- **The story** (`index.html`): a one-minute animated introduction for non-specialists (auto-plays; SPACE pause, arrows change scene, F fullscreen).
- **The digital twin** (`twin.html`): the interactive tool, also reachable from the story's *Try the digital twin* button.

Choose a commercial thermal pad, its stock thickness and the assembly pressure, then the operating point (power, heat-sink cooling, die power map) and the assembly quality (coverage). The 3-D temperature field, junction temperature, thermal resistance, allowable power and reliability-risk indicators update instantly.

- Simulation-based demo; values are indicative and are not experimental measurements.
- This repository contains only the two compiled demo pages and the open-source plotly.js library (MIT licence) they use. The simulation models, data and methods are not included.

Team **WINDWIN** · Dinh Phong Nguyen, Khanh Linh Truong · VinUniversity, Vietnam

© 2026 Team WINDWIN (Dinh Phong Nguyen, Khanh Linh Truong). All rights reserved. No licence is granted to copy, modify or redistribute this page or its content.
