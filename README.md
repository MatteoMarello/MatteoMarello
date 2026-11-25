### Matteo Marello

MSc student in Data Science and Engineering at Politecnico di Torino.
I work on the experimental side of machine learning: how models behave when the input distribution shifts,
when a small edit changes the meaning of a text, and when a system has to protect information without destroying it.
Current focus: deep NLP, model robustness, and evaluation methodology.

#### Selected work

**[Reinforcement Learning under sim-to-sim domain shift](https://github.com/MatteoMarello/Reinforcement_Learning)** · team course project, 4 authors  
Policy-gradient methods from scratch (Hopper) and SAC with uniform / automatic domain randomization on a
PandaPush task whose cube mass changes between training and deployment. Uniform randomization closes the transfer gap
(success 0.53 → 0.99, pooled over three logged evaluation batches); a post-hoc variability analysis shows the
automatic-randomization gain reported in the course is within evaluation noise.
My role: report, code integration, consistency checks, and the follow-up analysis.

**[MedAnon](https://github.com/neural-wave/2026-Fuma-c-anduma)** · team project, Neural Wave Hackathon 2026, Bosch challenge  
Context-aware de-identification of doctor–patient dialogues and clinical notes: span detectors (rules, spaCy,
Presidio, transformer NER) with a clinical veto, encounter-level entity propagation, generalization policies, and
adversarial evaluation with a synthetic record-linkage attack. Results are team-reported on synthetic data; see the
repository for scope and limitations. I was one of the contributors.

#### Interests

Natural language inference and evidence-grounded reasoning · counterfactual and contrast-set evaluation ·
robustness under distribution shift · privacy-preserving NLP · reproducible experimentation.

<sub>Other public repositories are coursework exercises kept for reference.</sub>
