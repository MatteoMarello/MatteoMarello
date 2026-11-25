# Matteo Marello

I am an MSc student in Data Science and Engineering at Politecnico di Torino. I study how to evaluate the reliability of machine learning systems when a small edit changes the evidence, the deployment dynamics shift, or an anonymizer must preserve information needed for a downstream task.

## Selected research and engineering projects

**[ClauseShift](https://github.com/MatteoMarello/ClauseShift) · Evidence-grounded inference**  
Independent, AI-assisted project on whether NLI models respond to decisive edits in synthetic rule documents. The released results cover **15 fine-tuning runs** and **1,280 held-out minimal pairs**. With NLI initialization, paired and unpaired training reached **81.5% and 79.5% flip-pair accuracy** across three seeds. The seed-level interval for the difference crossed zero, and the no-NLI ablation favored unpaired training on average with substantial seed variation. A blinded single-LLM audit matched **112/112** generator labels. Independent human validation is pending. [Technical report](https://github.com/MatteoMarello/ClauseShift/blob/main/docs/REPORT.md) · [Results and ablations](https://github.com/MatteoMarello/ClauseShift/blob/main/results/EXTENDED_ANALYSIS.md) · [LLM annotation audit](https://github.com/MatteoMarello/ClauseShift/blob/main/review/clauseshift_llm_audit.md)

**[Semantic Privacy Lab](https://github.com/MatteoMarello/Semantic-Privacy-Lab) · Privacy–utility trade-offs**  
Independent, AI-assisted study on synthetic support tickets. In Run 1, top-1 linkage in a 5,000-person synthetic register was **42.9%** after oracle masking of direct identifiers, **19.0%** after also generalizing quasi-identifiers and **1.3%** after also suppressing contextual clues. In a separate post-hoc test on unseen phrasings, the trained detector left **50.7% of age spans** unmasked despite low aggregate linkage. [Technical report](https://github.com/MatteoMarello/Semantic-Privacy-Lab/blob/main/docs/REPORT.md) · [Research protocol](https://github.com/MatteoMarello/Semantic-Privacy-Lab/blob/main/docs/PREREGISTRATION.md)

**[Reinforcement Learning](https://github.com/MatteoMarello/Reinforcement_Learning) · Robust robotic control**  
Four-author course project on policy gradients and sim-to-sim transfer in PandaPush. I wrote the report, integrated the experimental code, checked consistency across phases, and added a post-submission analysis of the logged evaluations. At 500k steps, pooled target-domain success was **52.7%** for source-only SAC, **99.3%** with uniform randomization, and **56.7%** with automatic randomization across three batches under a single recorded training seed. [Evaluation analysis](https://github.com/MatteoMarello/Reinforcement_Learning/tree/main/followup)

**[MedAnon](https://github.com/neural-wave/2026-Fuma-c-anduma) · Clinical NLP**  
Team project for the Bosch challenge at Neural Wave Hackathon 2026. We combined transformer NER, contextual rules, and entity propagation across dialogue and notes, then evaluated residual linkage risk alongside clinical information preservation. I contributed to the team release. [Release commit](https://github.com/neural-wave/2026-Fuma-c-anduma/commit/2672fb8) · [Jury report](https://github.com/neural-wave/2026-Fuma-c-anduma/blob/main/report/JURY_REPORT.md)

## Research interests

Deep NLP, evidence-grounded inference, counterfactual evaluation, robustness under distribution shift, and privacy-preserving machine learning.
