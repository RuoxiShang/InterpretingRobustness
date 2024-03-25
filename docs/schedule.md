---
layout: default
title: Schedule
nav_order: 2
---
# Interpreting Robustness - Course Schedule

> Note: All activities and readings are subject to change as we explore this throughout the quarter. Check Canvas for actual due dates.


## Week 1 (3/25/2024) - Introduction
### Topics
- Why interpretability and robustness?

### Discussions and Activities
- Meet your groups

### Required Reading
- [Why Johnny Can't Prompt: How Non-AI Experts Try (and Fail) to Design LLM Prompt](https://dl.acm.org/doi/pdf/10.1145/3544548.3581388) this paper talks about the unique challenges non-AI experts face when trying to design effective prompts for LLMs. It's one of the first HCI papers that systematically studied prompt engineering behaviors from the non-expert users' standpoint

## Week 2 (4/1/2024) - Promise
### Topics
- What new possibilities exist for model intepretability with LLMs?

### Discussions and Activities
- Intro Slides

### Required Reading
- [Rethinking Interpretability in the Era of Large Language Models](https://arxiv.org/abs/2402.01761)

### Additional Resources
- [LLMs are Interpretable](https://timkellogg.me/blog/2023/10/01/interpretability) is a blog post presenting an optimistic view  on the interpretability of LLMs contrasting them with traditional ML models. Kellogg argues that LLMs are more complex but inherently more interpretable because they operate in way closer to human reasoning and communication
- [Look Before You Leap: An Exploratory Study of Uncertainty Measurement for Large Language Models](https://arxiv.org/abs/2307.10236). Measures of trustworthiness for these models are fragile and become more difficult to establish as model capabilities increase.

## Week 3 (4/8/2024) - Inspection
### Topics
- How do users understand LLMs and interpret outputs when using them for specific tasks?

### Discussions and Activities
- Interpret ChatGPT

### Required Reading
- [How Do Analysts Understand and Verify AI-Assisted Data Analyses?](https://arxiv.org/abs/2309.10947)

### Additional Resources
- [Ironies of Generative AI: Understanding and mitigating productivity loss in human-AI interactions](https://arxiv.org/abs/2402.11364) suggests that what we know from human factors research in domains which experienced rapid automation points to reasons for productivity paradoxes with LLMs and Generative AI.
- [A magazine article](https://visualstudiomagazine.com/articles/2024/01/25/copilot-research.aspx) summarizing recent work showing the potentially bad impact of code-assistant tools like CoPilot on code quality. Imagine the net effect of junior developers being unable to interpret code written by an assistant.

## Week 4 (4/15/2024) - Introspection
### Topics
- Can LLMs report when interpretation is dangerous?

### Discussions and Activities
- Test out top-p vs top-k strategies on local LLMs

### Required Reading
- [Still No Lie Detector for Language Models: Probing Empirical and Conceptual Roadblocks](https://arxiv.org/abs/2307.00175)

### Additional Resources
- [The Internal State of an LLM Knows When It's Lying](https://arxiv.org/pdf/2304.13734.pdf) this paper proposes an innovative approach to discern LLMs ability to distinguish true and false statements. Our required reading for this week was written by reserchers who tried to generalize these results and failed, so their work is a valuable read in context.
- [Can Language Models Encode Perceptual Structure Without Grounding? A Case Study in Color](https://arxiv.org/abs/2109.06129), an interesting paper checking alignment of language models to human perceived color spaces despite those models never "seeing" color.

## Week 5 (4/22/2024) - Check-in
### Topics
- Review

### Discussions and Activities
- Turning user questions into research
- Group Notes

## Week 6 (4/29/2024) - Persuasion 
### Topics
- What new possibilities exist for adversarial input?

### Discussions and Activities
- Persuade a GPT

### Required Reading
- [How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to Challenge AI Safety by Humanizing LLMs](https://arxiv.org/abs/2401.06373)

### Additional Resources
- [Why We Should Have Seen That Coming: Comments on Microsoft's Tay "Experiment," and Wider Implications](https://doi.org/10.29297/orbit.v1i2.49), a reflection on problems with chatbots that have an open interface to the public and the additional responsibilities developers of that software have.
- [Extracting Training Data from ChatGPT](https://not-just-memorization.github.io/extracting-training-data-from-chatgpt.html?ref=404media.co), a paper from Google researchers which exfiltrated data from production systems through clever prompting (link goes to a good explanatory blog post)

## Week 7 (5/6/2024) - Defenses
### Topics 
- How do we defend model guardrails and what is at stake?

### Required Reading
- [Summon a Demon and Bind it: A Grounded Theory of LLM Red Teaming in the Wild](https://arxiv.org/abs/2311.06237)

### Additional Resources
- [Jailbroken: How Does LLM Safety Training Fail?](https://arxiv.org/abs/2307.02483), describes two main modes of model safety training failure and designs new attacks based on them.
- [Break it, Imitate it, Fix it: Robustness by Generating Human-Like Attacks](https://arxiv.org/abs/2310.16955), which shows improvements to robustness by generating new automated attacks from samples of human created jailbreaks.

## Week 8 (5/13/2024) - The Wild
### Topics
- What attacks are in the wild?

### Discussions and Activities
- What risks do these methods pose?

### Required Reading
- ["Do Anything Now": Characterizing and Evaluating In-The-Wild Jailbreak Prompts on Large Language Models](https://arxiv.org/abs/2308.03825)

### Additional Resources
- [Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection](https://arxiv.org/abs/2302.12173), a paper showcasing injection of adversarial attacks not into language prompts but other inputs retreived at the time of inference!

## Week 9 (5/20/2024) - Check-In
### Topics
- Review

### Discussions and Activities
- GPT integration and safety 
- Group Notes

## Week 10 (5/27/2024) - Futures
### Topics
- What's next?

### Discussions and Activities
- Outro Slides

### Additional Resources
- [AI Transparency in the Age of LLMs: A Human-Centered Research Roadmap](https://arxiv.org/abs/2306.01941), a roadmap for achieving transparency, which is "fundamentally about supporting appropriate human understanding," in the LLM space.