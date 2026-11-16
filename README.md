# Personality of Large Language Models: A Comprehensive Survey of Assessment, Manipulation and Applications

Yutong Yang, Houxin Lao, Yiwei Gao, Weikang Li, and Yunfang Wu  
Peking University

**Paper:** [Read the paper (PDF)](<./llm-personality-survey-preprint.pdf>)  
**Slides:** [中文讲解幻灯片](<./人格综述.pptx>)

## Overview

How can we tell whether an LLM expresses a target personality? What can existing methods control, and how do those changes affect interaction and task performance?

Our survey reviews personality assessment, control, and applications in large language models. We distinguish the evidence provided by self-reports, generated text, and behavioral decisions. We compare control methods by whether they can set traits, adjust their intensity, or combine multiple traits, and by what model access and training they require. We also review how personality is used in human behavior simulation, human–AI collaboration, and multi-agent collaboration.

## Choosing a benchmark

These examples are adapted from Table 2 of the survey. Start with what you want to observe.

| Research goal | Benchmark or resource | What it evaluates |
| --- | --- | --- |
| Check whether questionnaire scores are stable | [MODEL-PERSONAS](https://aclanthology.org/2024.blackboxnlp-1.20/) | How self-report scores change when prompts, option order, or item wording vary |
| Assess trait expression in generated text | [PersonaLLM](https://aclanthology.org/2024.findings-naacl.229/) | Whether assigned Big Five traits are recognizable in generated stories |
| Compare trait expression on situational choices | [TRAIT](https://aclanthology.org/2025.findings-naacl.469/) | How models respond to multiple-choice scenarios covering the Big Five and Dark Triad |
| Assess fidelity to a target character’s personality | [InCharacter](https://aclanthology.org/2024.acl-long.102/) | How closely interview-based personality assessments match reference character profiles |
| Compare self-reports with behavioral decisions | [ActTraitBench](https://aclanthology.org/2026.findings-emnlp.2068/) | How consistently assigned traits appear in self-reports and scenario-based decisions |
| Study personality in multi-turn interaction | [KODIS / L2L](https://arxiv.org/abs/2602.07414) · [Persona-Evolve](https://arxiv.org/abs/2602.15669) | Negotiation strategies relative to human dialogues, or trait expression as a scenario evolves, respectively |

## Citation

If you use this survey or its taxonomy in your research, please cite the paper. The BibTeX entry will be added when the arXiv record is public.

## Corrections and suggestions

If you spot an error or know of a relevant resource, please open a GitHub issue with a link to the original paper or repository.
