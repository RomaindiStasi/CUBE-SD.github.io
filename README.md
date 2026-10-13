# CUBE-SD

**Curiosity, Uncertainty, and their Biological & Emotional mechanisms: investigating how uncertainty drives curiosity across animal Species and human Development.**

CUBE-SD investigates how uncertainty, surprise, physiological arousal, and attention shape curiosity and exploration–exploitation decisions across human development and non-human primate species.

This repository hosts the [project website](https://romaindistasi.github.io/CUBE-SD.github.io/), research updates, and methodological resources.

## Work packages

### WP1 — Human development

WP1 builds on research with 18–24-month-old infants and plans to extend the paradigm to school-aged children (6–11 years) and young adults (18–35 years).

Participants observe eight button presses on each of four interactive cubes, with sound probabilities of **0/8, 1/8, 4/8, and 8/8**, before interacting with each cube in silent mode. Measures distinguish **exploration** (switching between buttons) from **exploitation** (repeated presses on the same button).

The multimodal approach combines behavioural and gaze coding, electrodermal activity (EDA), heart-rate variability (HRV), and automated facial-expression analysis to examine the contributions of surprise, arousal, and attention. Planned physiological recordings use Empatica EmbracePlus.

### WP2 — Non-human primates

WP2 will test whether the uncertainty–exploration relationship, including a possible preference for intermediate uncertainty, is shared across primate species.

A first primate-adapted cube prototype has been developed. The planned procedure involves voluntary interaction without a human demonstrator, using the same four sound probabilities. The cube will remain active for 20 seconds after the first press, then become silent. Video coding will assess exploration and exploitation using behavioural categories shared with WP1; WP2 will collect behavioural data only.

A collaboration with **Pairi Daiza Zoo is in development**. Primate studies remain planned and subject to the zoo's Animal Welfare Body review.

### WP3 — Modelling

WP3 will use WP1 and WP2 data to formalise and simulate curiosity:

- **Multi-group structural equation modelling (SEM)** will examine relationships between uncertainty, surprise, arousal, attention, and exploration–exploitation across human age groups.
- **Reinforcement-learning models** will test whether these mechanisms can reproduce developmental and cross-species patterns of exploration.

These models are planned research outputs.

## Findings and current status

**Findings reported so far.** Preliminary infant results presented at ICIS 2026 suggest that intermediate uncertainty (4/8) promotes exploratory button switching, reduces repeated pressing, and increases visual attention towards the cube compared with the other conditions. A manuscript is in preparation. These findings do not yet establish developmental or evolutionary continuity.

**Tools already implemented.** [i-FACE](I-FACE_project/iface.html) has an infant facial-expression classification pipeline based on a fine-tuned ResNet18 convolutional neural network, with preliminary evaluations. It remains under refinement and validation; facial-landmark and geometric extensions are exploratory. Its source code is not yet publicly available.

**Further development.** Priorities include child- and adult-adapted cube paradigms, physiological analyses, further validation of i-FACE, planned c-FACE and a-FACE extensions, primate protocols and partnerships, and SEM and reinforcement-learning models.

## Resources

- [Project website](https://romaindistasi.github.io/CUBE-SD.github.io/)
- [i-FACE methods and preliminary evaluations](I-FACE_project/iface.html)
- [Cube hardware, code, and technical documentation](https://github.com/parastuffs/cube-neuro)
- [ICIS 2026 poster — di Stasi, Kabdebon, Delhaye, & de Heering](https://hal.science/hal-05690026)
