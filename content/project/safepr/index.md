---
title: SafePR

date: 2025-05-14
# external_link: https://github.com/pandas-dev/pandas
# tags:
#   - Hugo
#   - Wowchemy
#   - Markdown

# url_pdf: 'https://arxiv.org/abs/2408.15831'
---

A Unified Framework for Safe Parallel Robots
<!--more-->
SafePR is a unified approach that I develop as part of my PhD at the [Institute of Mechatronic Systems](https://www.imes.uni-hannover.de/en/), Leibniz University Hannover, aiming to enable safe and efficient physical interaction between humans and parallel robots. As robotic systems increasingly operate in environments shared with humans, the ability to combine high-speed motion with reliable contact detection and safe response becomes critical.

SafePR addresses this need by integrating perception, control, and reaction strategies into a unified approach. It ensures that physical interactions remain safe for humans while respecting the mechanical and dynamic constraints of parallel robots.

Beyond safety, the project also focuses on practical implementation. SafePR includes a comprehensive Simulink model that covers not only the algorithmic aspects of contact handling but also the real-time control logic required to operate a custom-built robotic platform reliably. This model allows for repeatable experiments and simplifies system commissioning.

The project can be found [here](https://aranmoha.github.io/SafePR/) and provides open access to the full Simulink environment, source code, and detailed documentation to facilitate adoption and further development by the research community. Additional materials include simulation setups and a breakdown of each functional module within the SafePR workflow.