---
layout: default
title: Schedule
nav_order: 2
---
# Prompt Surfing DRG - Course Schedule

## Week 1 (1/8/2024) - Introductions

### Topics
- Introduce the course topic and structure as well as some case studies

### Discussions and Activities
- Introductions, expectations, and student projects
- Setting the stage: What is prompt engineering?
- [Introduction to GenAI Applications]
- It's not just ChatGPT: Other LLMs & non-text systems (e.g., audio, text, 3D models) (AH)

### Central Activity
- Playing with an LLM: In groups, get ChatGPT to write a children's story. What do you notice?

### Required Reading
- [All Gas, No Brakes in A.I. + Metaverse Update + Lessons From a Prompt Engineer](https://www.nytimes.com/2023/09/29/podcasts/all-gas-no-brakes-in-ai-metaverse-update-lessons-from-a-prompt-engineer.html?action=click&module=audio-series-bar&region=header&pgtype=Article) (1hr podcast)

### Additional Resources
- [Researchers Gain New Understanding From Simple AI](https://www.quantamagazine.org/researchers-glimpse-how-ai-gets-so-good-at-language-processing-20220414/)(this is a simplified explanation of "Attention is all you need", the transformers paper)
- [Characterizing Emergent Phenomena in Large Language Models](https://blog.research.google/2022/11/characterizing-emergent-phenomena-in.html#:~:text=In%20%E2%80%9CEmergent%20Abilities%20of%20Large,are%20present%20in%20larger%20models.) (a blog post ABOUT some google research, this is a very handy short example of scaling in capabilities merely from increased size. An important thing to get from this is that we aren't sure of the mechanism)
- [On the Opportunities and Risks of Foundation Models](https://arxiv.org/abs/2108.07258) (an absolutely GARGANTUAN guide to foundation models (ie LLMs and the like) in AI. 200 pages so defintely an "optional" read)
- [Awesome-LLM: A curated list of Large Language Model(s)](https://github.com/Hannibal046/Awesome-LLM)(a community generated repository of papers and links to code for large language models)
- [A list of open LLMs available for commercial use](https://github.com/eugeneyan/open-llms)(another list of LLMs, here exclusively those with licenses appropriate for commercial use.)
- [Prompt Engineering blog post from Lillian Weng](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/)
- [Eight Things to Know about Large Language Models](https://arxiv.org/abs/2304.00612) (a high level review from an Anthropic researcher. Very valuable for a broad understanding of some capabilities.)

## Week 2 - HOLIDAY

## Week 3 (1/22/2024) - Text

### Topics
- Explanation of text generation and exploration of an open-source alternative to ChatGPT, including an exercise with model guardrails

### Discussions and Activities
- Reading discussion
- What does it mean to generate text? (AH)
  - What is a token?
  - What is a token window?
  - What is a transformer?
- Intro to "Break a GPT"
  - AS does point of view shifts
  - AH does "I like to pretend"

### Central Activity
- Break a GPT: Working in groups to get ChatGPT to spit out something unexpected or aberrant
  - What do I mean by break?
  - Can we define breakage?

### Required Reading
- [Talking about Large Language Models](https://arxiv.org/abs/2212.03551)(from a researcher at Deepmind, this is useful for terms and concepts as well as a good guide for how to think about these systems as a whole.)

### Additional Resources
- [Chatbots Don't Know What Stuff Isn't](https://www.quantamagazine.org/ai-like-chatgpt-are-no-good-at-not-20230512/)(from Quanta Magazine this article does a good job of illustrating early troubles with handling negation in language models. Pay special attention to some of the proposed reasons AND issues in assessing progress since inspection is so difficult.)
- [Can AI really be protected from text-based attacks?](https://techcrunch.com/2023/02/24/can-language-models-really-be-protected-from-text-based-attacks/)(A short general interest article hinting at problems with safety mechanisms on LLMs introducing a difficult and complex space to protect.)
- [Adversarial Attacks on LLMs](https://lilianweng.github.io/posts/2023-10-25-adv-attack-llm/)(a more technical post from Lillian Weng)
- An illustrated explanation of NLP transformer based models [The Illustrated BERT, ELMo, and co. (How NLP Cracked Transfer Learning](https://jalammar.github.io/illustrated-bert/)
- [Google's attempt to "break GPT" by extracting training data](https://not-just-memorization.github.io/extracting-training-data-from-chatgpt.html?ref=404media.co)
- Breaking a GPT-3 powered Twitter bot by asking it to ["ignore all previous instructions"](https://www.aiweirdness.com/ignore-all-previous-instructions/)
- NIST [research report on adversarial machine learning input](https://csrc.nist.gov/pubs/ai/100/2/e2023/final) input more broadly, not just with Large Language Models.

## Week 4 (1/29/2024) - Images

### Topics
- Discussion of the impact of early image generators (ca 2022-2023)
- Introduction to image generation via Latent Diffusion Models
- Exercise with Stable Diffusion

### Discussions and Activities
- Reading discussion
- Introduction to image generation
- Play with an image generator
- How do we install one of our own?

### Central Activity
- Getting started with a project: Get together to talk about project ideas

### Required Reading
- [The art of text-to-image generative AI](https://networkcultures.org/blog/2023/05/17/bruce-sterling-on-the-art-of-text-to-image-generative-ai/) (a transcript of a talk by Bruce Sterling on Dall-E Mini)

### Additional Resources
- [Hands Are Hard: Unlearning How We Talk About Machine Learning in the Arts](https://digitalscholarship.unlv.edu/tradition_innovations/vol1/iss1/4/)
- [Looking for Meaning in all the Wrong Places](https://www.youtube.com/watch?v=r-V-qqLJLF8&t=3s)
- [One Vision of Machine Art](https://docs.google.com/document/d/1Fuvf2imJJyEWXb22OezkpOMsFacesETIIZYi1GIPkQc/edit?usp=sharing) (a short prompt looking at two passages in an H.P. Lovecraft story from the 1930s with eerie parallels to generative art)
- [The Illustrated Stable Diffusion](https://jalammar.github.io/illustrated-stable-diffusion/)
- [GitHub page for the Latent Diffusion model paper](https://github.com/CompVis/latent-diffusion) (formed the kernel of what has become Stable Diffusion)

## Week 5 (2/5/2024) - Interpretation

### Topics
- Discussion of means and methods of interpretation of model output, including recent research on LLMs and a design case study of image classification

### Discussions and Activities
- Do we know what's happening in these systems? [Interpreting LLMs]
- What are some means/methods of interpretability? (transition to the reading)
- How do we think about interpretability when we can't see what's going on?
- Introduce image generator (Again, AH)

### Central Activity
- Play with an image generator

### Required Reading
- [Objective Portrait: A practice-based inquiry to explore AI as a reflective design partner](https://dl.acm.org/doi/abs/10.1145/3563657.3595974)

### Additional Resources
- [AI Transparency in the Age of LLMs: A Human-Centered Research Roadmap](https://arxiv.org/pdf/2306.01941.pdf)
- [Building A Virtual Machine inside ChatGPT](https://www.engraved.blog/building-a-virtual-machine-inside/)
- [The debate over understanding in AI's large language models](https://www.pnas.org/doi/full/10.1073/pnas.2215907120)
- [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)
- [Large Language Models are Zero-Shot Reasoners](https://proceedings.neurips.cc/paper_files/paper/2022/file/8bb0d291acd4acf06ef112099c16f326-Paper-Conference.pdf) (the genesis of "let's think step by step" LLM prompting research)
- [Large Language Models Cannot Self-Correct Reasoning](https://huggingface.co/papers/2310.01798) (a technical but critical look at the problem of correction, specifically the problem of self-correction)
- [The Internal State of an LLM Knows When It's Lying](https://arxiv.org/pdf/2304.13734.pdf) (an attempt to inspect internal states about the information produced by the model)
- [Can Language Models Encode Perceptual Structure Without Grounding? A Case Study in Color](https://arxiv.org/pdf/2109.06129.pdf)

## Week 6 (2/12/2024) - Change

### Topics
- Discussion of community impact on model development and the impact/import of biases in model output

### Discussions and Activities
- How do communities change model outputs?
- WHO IS US?!

### Central Activity
- Consultation (AH, AS, BC): 3 groups (4 people per group), 15 min per person

### Required Reading
- ['Person' == Light-skinned, Western Man, and Sexualization of Women of Color: Stereotypes in Stable Diffusion](https://aclanthology.org/2023.findings-emnlp.465.pdf) (a paper from UW researchers on stereotypes in Stable Diffusion)

### Additional Resources
- [Robust fine-tuning of zero-shot models](https://arxiv.org/abs/2109.01903) (demonstrates that making a weighted sum of the matrix of model weights of two LLMs produces a merged model with a weighted sum of the concept understandings of the two)
- [An Image is Worth One Word: Personalizing Text-to-Image Generation using Textual Inversion](https://arxiv.org/abs/2208.01618) (the first research paper to demonstrate that lightweight collections of tokens could be built by training images and be used to stand in for a complex prompt)
- [Local Large Language Models](https://int8.io/local-large-language-models-beginners-guide/) (A highly technical but not academic guide to Local LLMs and fine-tuning. It also includes and explanation of how LoRAs work.)
- [A GitHub Next project evaluating GPT-4 performance with calculation](https://github.com/githubnext/gpt4-with-calc/blob/main/docs/eval.md) (spoiler: not great!)
- [ChatGPT math performance over time](https://arxiv.org/abs/2307.09009) (A more detailed demonstration by researchers at Stanford)

## Week 7 - HOLIDAY

## Week 8 (2/26/2024) - Project

### Topics
- Collaborative critique of in-progress work

### Discussions and Activities
- What have you been working on? (start with original groups, then do a rotation)
- Collaborative critique

### Central Activity
- Collaborative critique

### Required Reading
- No reading for this week. Focus on your collaborative critique submission and your project.

### Additional Resources
- [Vanderbilt University apologizes for using ChatGPT to write mass-shooting email](https://www.cnn.com/2023/02/22/tech/vanderbilt-chatgpt-shooting-email/index.html)
- [Temporary policy: Generative AI (e.g., ChatGPT) is banned](https://meta.stackoverflow.com/questions/421831/temporary-policy-generative-ai-e-g-chatgpt-is-banned)
- [ChatGPT use shows that the grant-application system is broken](https://www.nature.com/articles/d41586-023-03238-5)
- A [good debate](https://julianmichael.org/blog/2020/07/23/to-dissect-an-octopus.html) from two linguist/philosophers on how to think about meaning and chatbots. Rather than John Searle's Chinese room they think about...an octopus!
- A [magazine article](https://visualstudiomagazine.com/articles/2024/01/25/copilot-research.aspx) summarizing recent work showing the potentially bad impact of code-assistant tools like CoPilot on code quality

## Week 9 (3/4/2024) - Testing

### Topics
- Testing and review of work by peers and the teaching team

### Discussions and Activities
- Test out what you have been making/writing/breaking
- Returning to a reading (the class picks a reading for today that we all promise to (re)read heavily and discuss)
- How do these systems impact humans?

### Central Activity
- Have students prepare ONE question for the class on what is blocking them or troubling them

### Required Reading
- No reading for this week. Focus on your project.

### Additional Resources
- [Why Meta's latest large language model survived only three days online](https://www.technologyreview.com/2022/11/18/1063487/meta-large-language-model-ai-only-survived-three-days-gpt-3-science/)

## Week 10 (3/11/2024) - Feedback

### Discussions and Activities
- Demo what you've been making/writing/breaking


[Introduction to GenAI Applications]: https://RuoxiShang.github.io/PromptSurfing/data/week1-applications.pdf
[Interpreting LLMs]: https://RuoxiShang.github.io/PromptSurfing/data/week5-interpretability.pdf