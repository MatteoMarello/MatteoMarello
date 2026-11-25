# Matteo Marello

I am an MSc student in Data Science and Engineering at Politecnico di Torino. I study how to evaluate the reliability of machine learning systems when a small edit changes the evidence, the deployment dynamics shift, or an anonymizer must preserve information needed for a downstream task.

## Selected research and engineering projects

**[ClauseShift](https://github.com/MatteoMarello/ClauseShift) · Evidence-grounded inference**  
I use single-edit counterfactual pairs to test whether NLI models respond to decisive exceptions, thresholds, dates, and cross-references. On 1,280 held-out synthetic pairs, the strongest zero-shot baseline in the original input format reached **53.1% item accuracy** and **31.6% pair accuracy** (both sides correct). The project includes hypothesis-only controls, analysis by edit type, and generator-derived labels. [Results](https://github.com/MatteoMarello/ClauseShift/blob/main/results/RESULTS.md) · [Preregistration](https://github.com/MatteoMarello/ClauseShift/blob/main/docs/PREREGISTRATION.md) · [Independent LLM annotation audit](https://github.com/MatteoMarello/ClauseShift/blob/main/review/clauseshift_llm_audit.md)

**[Reinforcement Learning](https://github.com/MatteoMarello/Reinforcement_Learning) · Robust robotic control**  
Four-author course project on policy gradients and sim-to-sim transfer in PandaPush. I wrote the report, integrated the experimental code, checked consistency across phases, and added a post-submission analysis of the logged evaluations. At 500k steps, pooled target-domain success was **52.7%** for source-only SAC, **99.3%** with uniform randomization, and **56.7%** with automatic randomization across three batches under a single recorded training seed. [Evaluation analysis](https://github.com/MatteoMarello/Reinforcement_Learning/tree/main/followup)

**[Semantic Privacy Lab](https://github.com/MatteoMarello/Semantic-Privacy-Lab) · Privacy–utility trade-offs**  
I compare text anonymization strategies using synthetic support tickets with known identity spans and disjoint train and test authors. In the preregistered run, masking every direct identifier still left **42.9% top-1 linkage** in a 5,000-person synthetic register. In a post-hoc test on unseen phrasings, the trained detector kept linkage low while missing **50.7% of age spans**. [Technical report](https://github.com/MatteoMarello/Semantic-Privacy-Lab/blob/main/docs/REPORT.md)

**[MedAnon](https://github.com/neural-wave/2026-Fuma-c-anduma) · Clinical NLP**  
Team project for the Bosch challenge at Neural Wave Hackathon 2026. We combined transformer NER, contextual rules, and entity propagation across dialogue and notes, then evaluated residual linkage risk alongside clinical information preservation. I contributed to the team release. [Release commit](https://github.com/neural-wave/2026-Fuma-c-anduma/commit/2672fb8) · [Jury report](https://github.com/neural-wave/2026-Fuma-c-anduma/blob/main/report/JURY_REPORT.md)

## Research interests

Deep NLP, evidence-grounded inference, counterfactual evaluation, robustness under distribution shift, and privacy-preserving machine learning.
