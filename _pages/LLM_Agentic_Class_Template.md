---
#layout: archive
#title: "Large Language Model Agent Workshop"
#permalink: /teachingLLM/
#author_profile: true
#<div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
---

Large Language Model Agents llm-agents-mooc

# Large Language Model Agents

## MOOC, Fall 2024

Announcement:

Sign up and learn more about the LLM Agents Hackathon [here](https://rdi.berkeley.edu/llm-agents-hackathon/)!

### Prospective Students

- This course has completed. Video lectures can still be found in the syllabus below. Please sign up for the [Spring 2025 iteration](https://llmagents-learning.org/sp25) today!
- All certificates have been released! Thank you for a great semester.

## Course Staff

Instructor

Co-instructor

![](assets/dawn-berkeley.jpg)

![](assets/XinyunChen.jpg)

[Dawn Song](https://people.eecs.berkeley.edu/~dawnsong/)

Xinyun Chen

Professor, UC Berkeley

Research Scientist,  
Google DeepMind

## Guest Speakers

.table { width: 100%; table-layout: fixed; border-collapse: collapse; } .table td { width: 25%; text-align: center; vertical-align: top; padding: 10px; }

![](assets/Denny Zhou.jpeg)

![](assets/Shunyu Yao.jpeg)

![](assets/Chi Wang.jpg)

![](assets/Jerry Liu.jpg)

Denny Zhou

Shunyu Yao

Chi Wang

Jerry Liu

![](assets/Google Deepmind.png)

![](assets/openai.png)

![](assets/Google Deepmind.png)

![](assets/LlamaIndex.png)

![](assets/Burak Gokturk.png)

![](assets/Omar Khattab.jpg)

![](assets/Graham Neubig.jpg)

![](assets/Nicolas Chapados.jpg)

Burak Gokturk

Omar Khattab

Graham Neubig

Nicolas Chapados

![](assets/Google.jpg)

![](assets/databricks.png)

![](assets/CMU.png)

![](assets/servicenow.png)

![](assets/Yuandong Tian.png)

![](assets/Jim Fan.jpeg)

![](assets/Percy Liang.jpeg)

![](assets/Ben Mann.jpeg)

Yuandong Tian

Jim Fan

Percy Liang

Ben Mann

![](assets/meta ai.jpeg)

![](assets/nvidia.png)

![](assets/stanford.png)

![](assets/Anthropic.png)

## Course Description

Large language models (LLMs) have revolutionized a wide range of domains. In particular, LLMs have been developed as agents to interact with the world and handle various tasks. With the continuous advancement of LLM techniques, LLM agents are set to be the upcoming breakthrough in AI, and they are going to transform the future of our daily life with the support of intelligent task automation and personalization. In this course, we will first discuss fundamental concepts that are essential for LLM agents, including the foundation of LLMs, essential LLM abilities required for task automation, as well as infrastructures for agent development. We will also cover representative agent applications, including code generation, robotics, web automation, medical applications, and scientific discovery. Meanwhile, we will discuss limitations and potential risks of current LLM agents, and share insights into directions for further improvement. Specifically, this course will include the following topics:

- Foundation of LLMs
- Reasoning
- Planning, tool use
- LLM agent infrastructure
- Retrieval-augmented generation
- Code generation, data science
- Multimodal agents, robotics
- Evaluation and benchmarking on agent applications
- Privacy, safety and ethics
- Human-agent interaction, personalization, alignment
- Multi-agent collaboration

## Syllabus

Date

Guest Lecture  
(3:00PM-5:00PM PST)

Supplemental Readings

Sept 9

**LLM Reasoning**  
Denny Zhou, Google DeepMind  
[Livestream](https://www.youtube.com/live/QL-FS_Zcmyo) [Intro](https://rdi.berkeley.edu/llm-agents-mooc/slides/intro.pdf) [Slides](https://rdi.berkeley.edu/llm-agents-mooc/slides/llm-reasoning.pdf) [Quiz 1](https://forms.gle/1pb6nkwZPyUqvFPe6)

\- [Chain-of-Thought Reasoning Without Prompting](https://arxiv.org/abs/2402.10200)  
\- [Large Language Models Cannot Self-Correct Reasoning Yet](https://arxiv.org/abs/2310.01798)  
\- [Premise Order Matters in Reasoning with Large Language Models](https://arxiv.org/abs/2402.08939)  
\- [Chain-of-Thought Empowers Transformers to Solve Inherently Serial Problems](https://arxiv.org/abs/2402.12875)

Sept 16

**LLM agents: brief history and overview**  
Shunyu Yao, OpenAI  
[Livestream](https://www.youtube.com/watch?v=RM6ZArd2nVc) [Slides](https://rdi.berkeley.edu/llm-agents-mooc/slides/llm_agent_history.pdf) [Quiz 2](https://forms.gle/t9ictrAjxTrWd9tr6)

\- [WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents](https://arxiv.org/abs/2207.01206)  
\- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)

Sept 23

**Agentic AI Frameworks & AutoGen**  
Chi Wang, AutoGen-AI  
**Building a Multimodal Knowledge Assistant**  
Jerry Liu, LlamaIndex  
[Livestream](https://www.youtube.com/live/OOdtmCMSOo4) [Chi’s Slides](https://rdi.berkeley.edu/llm-agents-mooc/slides/autogen.pdf) [Jerry’s Slides](https://rdi.berkeley.edu/llm-agents-mooc/slides/MKA.pdf) [Quiz 3](https://forms.gle/osuDEXRmDHJvLi1T7)

\- [AutoGen: Enabling Next-Gen LLM Applications via Multi-Agent Conversation](https://arxiv.org/abs/2308.08155)  
\- [StateFlow: Enhancing LLM Task-Solving through State-Driven Workflows](https://arxiv.org/abs/2403.11322)

Sept 30

**Enterprise trends for generative AI, and key components of building successful agents/applications**  
Burak Gokturk, Google  
[Livestream](https://www.youtube.com/live/Sy1psHS3w3I) [Slides](https://rdi.berkeley.edu/llm-agents-mooc/slides/Burak_slides.pdf) [Quiz 4](https://forms.gle/gcoo9HWGdF3xVAPGA)

\- [Google Cloud expands grounding capabilities on Vertex AI](https://cloud.google.com/blog/products/ai-machine-learning/rag-and-grounding-on-vertex-ai?e=48754805)  
\- [The Needle In a Haystack Test: Evaluating the performance of RAG systems](https://towardsdatascience.com/the-needle-in-a-haystack-test-a94974c1ad38)  
\- [The AI detective: The Needle in a Haystack test and how Gemini 1.5 Pro solves it](https://cloud.google.com/blog/products/ai-machine-learning/the-needle-in-the-haystack-test-and-how-gemini-pro-solves-it?e=48754805)

Oct 7

**Compound AI Systems & the DSPy Framework**  
Omar Khattab, Databricks  
[Livestream](https://www.youtube.com/live/JEMYuzrKLUw) [Slides](https://rdi.berkeley.edu/llm-agents-mooc/slides/dspy_lec.pdf) [Quiz 5](https://forms.gle/tXzmfgTsdYW5XjLL6)

\- [Optimizing Instructions and Demonstrations for Multi-Stage Language Model Programs](https://arxiv.org/abs/2406.11695)  
\- [Fine-Tuning and Prompt Optimization: Two Great Steps that Work Better Together](https://arxiv.org/abs/2407.10930)

Oct 14

**Agents for Software Development**  
Graham Neubig, Carnegie Mellon University  
[Livestream](https://www.youtube.com/live/f9L9Fkq-8K4) [Slides](https://rdi.berkeley.edu/llm-agents-mooc/slides/neubig24softwareagents.pdf) [Quiz 6](https://forms.gle/v4AD4vFYCjdK9qeDA)

\- [SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering](https://arxiv.org/abs/2405.15793)  
\- [OpenHands: An Open Platform for AI Software Developers as Generalist Agents](https://arxiv.org/abs/2407.16741)

Oct 21

**AI Agents for Enterprise Workflows**  
Nicolas Chapados, ServiceNow  
[Livestream](https://www.youtube.com/live/-yf-e-9FvOc) [Slides](https://rdi.berkeley.edu/llm-agents-mooc/slides/agentworkflows.pdf) [Quiz 7](https://forms.gle/VWpd1q23PBFptVCe8)

\- [WorkArena: How Capable Are Web Agents at Solving Common Knowledge Work Tasks?](https://arxiv.org/abs/2403.07718)  
\- [WorkArena++: Towards Compositional Planning and Reasoning-based Common Knowledge Work Tasks](https://arxiv.org/abs/2407.05291)  
\- [TapeAgents: a Holistic Framework for Agent Development and Optimization](https://rdi.berkeley.edu/llm-agents-mooc/assets/tapeagents.pdf)

Oct 28

**Towards a unified framework of Neural and Symbolic Decision Making**  
Yuandong Tian, Meta AI (FAIR)  
[Livestream](https://www.youtube.com/live/wm9-7VBpdEo) [Slides](https://rdi.berkeley.edu/llm-agents-mooc/slides/102824-yuandongtian.pdf) [Quiz 8](https://forms.gle/MLZy2czaMtJYhTSD7)

\- [Beyond A\*: Better Planning with Transformers via Search Dynamics Bootstrapping](https://arxiv.org/abs/2402.14083)  
\- [Dualformer: Controllable Fast and Slow Thinking by Learning with Randomized Reasoning Traces](https://arxiv.org/abs/2410.09918v1)  
\- [Composing Global Optimizers to Reasoning Tasks via Algebraic Objects in Neural Nets](https://arxiv.org/abs/2410.01779)  
\- [SurCo: Learning Linear Surrogates For Combinatorial Nonlinear Optimization Problems](https://arxiv.org/abs/2210.12547)

Nov 4

**Project GR00T: A Blueprint for Generalist Robotics**  
Jim Fan, NVIDIA  
[Livestream](https://www.youtube.com/live/Qhxr0uVT2zs) [Slides](https://rdi.berkeley.edu/llm-agents/assets/jimfangr00t.pdf) [Quiz 9](https://forms.gle/SsvzxWugqJD2VB2FA)

\- [Voyager: An Open-Ended Embodied Agent with Large Language Models](https://voyager.minedojo.org/)  
\- [Eureka: Human-Level Reward Design via Coding Large Language Models](https://eureka-research.github.io/)  
\- [DrEureka: Language Model Guided Sim-To-Real Transfer](https://eureka-research.github.io/dr-eureka/)

Nov 11

**No Class - Veterans Day**

Nov 18

**Open-Source and Science in the Era of Foundation Models**  
Percy Liang, Stanford University  
[Livestream](https://www.youtube.com/live/f3KKx9LWntQ) [Slides](https://rdi.berkeley.edu/llm-agents-mooc/slides/percyliang.pdf) [Quiz 10](https://forms.gle/VMu6XGEWHhW1xvij6)

\- [Cybench: A Framework for Evaluating Cybersecurity Capabilities and Risks of Language Models](https://arxiv.org/abs/2408.08926)

Nov 25

**Measuring Agent capabilities and Anthropic’s RSP**  
Ben Mann, Anthropic  
[Livestream](https://www.youtube.com/live/6y2AnWol7oo) [Slides](https://rdi.berkeley.edu/llm-agents-mooc/slides/antrsp.pdf) [Quiz 11](https://forms.gle/QU9EyEyeWP5sjPAu7)

\- [Announcing our updated Responsible Scaling Policy](https://www.anthropic.com/news/announcing-our-updated-responsible-scaling-policy)  
\- [Developing a computer use model](https://www.anthropic.com/news/developing-computer-use)

Dec 2

**Towards Building Safe & Trustworthy AI Agents and A Path for Science‑ and Evidence‑based AI Policy**  
Dawn Song, UC Berkeley  
[Livestream](https://www.youtube.com/live/QAgR4uQ15rc) [Slides](https://rdi.berkeley.edu/llm-agents/assets/dawn-agent-safety.pdf) [Quiz 12](https://forms.gle/EHwL4Jb3LZzNDw7w7)

\- [A Path for Science‑ and Evidence‑based AI Policy](https://understanding-ai-safety.org/)  
\- [DecodingTrust: A Comprehensive Assessment of Trustworthiness in GPT Models](https://arxiv.org/abs//2306.11698)  
\- [Representation Engineering: A Top-Down Approach to AI Transparency](https://arxiv.org/abs/2310.01405)  
\- [Extracting Training Data from Large Language Models](https://www.usenix.org/system/files/sec21-carlini-extracting.pdf)  
\- [The Secret Sharer: Evaluating and Testing Unintended Memorization in Neural Networks](https://www.usenix.org/system/files/sec19-carlini.pdf)

## Completion Certificate

LLM Agent course completion certificates will be awarded to students based on the rules of the following tiers. All assignments are due December 12th, 2024 at 11:59PM PST. To recieve your certificate please complete the [Certificate Declaration Form](https://forms.gle/nYGJLPTdb7af2Dq59) by December 17th, 2024 at 11:59PM PST.

**Trailblazer Tier:**

- Complete all 12 quizzes associated with each lecture
- Pass the written article assignment

**Mastery Tier:**

- Complete all 12 quizzes associated with each lecture
- Pass the written article assignment
- Pass all 3 lab assignments

**Ninja Tier:**

- Complete all 12 quizzes associated with each lecture
- Pass the written article assignment
- Submit a project to the [LLM Agents Hackathon](https://rdi.berkeley.edu/llm-agents-hackathon/)

**Legendary Tier:**

- Complete all 12 quizzes associated with each lecture
- Pass the written article assignment
- Become a prize winner or finalist at the [LLM Agents Hackathon](https://rdi.berkeley.edu/llm-agents-hackathon/)

**Honorary Tier:**

- For the most helpful/supportive students in discord!
- Meets coursework requirements of Ninja OR Mastery Tier

_NOTE: completing the assignments associated with this course in order to earn a Completion Certificate is completely optional. You are more than welcome to just watch the lectures and audit the course!_

## Coursework

All coursework will be released and submitted through the course website.

### Quizzes

All quizzes are released in parallel with (or shortly after) the corresponding lecture. Please remember to complete the quiz each week. Although it’s graded on completion, we encourage you to do your best. The questions are all multiple-choice and there are usually at most 5 per quiz. The quizzes will be posted in the Syllabus section.

An archive of all of the quizzes can be found [here](https://docs.google.com/document/d/1pYvOxt2UWwc3z4QlW2Di5LQT-FJPWZ419mxJT7pFPsU/edit?usp=sharing).

### Written Article

Create a twitter post, linkedin post, or medium article to post on Twitter of roughly 500 words. Include the link to our MOOC website in the article and tweet.

- Students in the Trailblazer or Mastery Tier should either summarize information from one of the lecture(s) or write a postmortem on their learning experience during our MOOC
- Students in the Ninja or Lengendary Tier should write about their hackathon submission

The written article is an effort-based assignment that will be graded as pass or no pass (P/NP). Submit your written article assignment [HERE](https://forms.gle/7ekobPNSWDLBWnDT6).

### Labs

There will be 3 lab assignments to give students some hands-on experience with building agents. Students must pass all 3 lab assignments. All labs are due December 12th, 2024 at 11:59pm PST. Please read the instructions carefully [here](https://rdi.berkeley.edu/llm-agents-mooc/assets/instructions.pdf). Please read the FAQs [here](https://docs.google.com/document/d/12MHAbLh86kGDuc2ddOmLHwjAuHh_rHiuAf_UiFuYcvE/edit?usp=sharing) before asking questions in Discord.

Assignment

Submission Form

[Lab 1](https://drive.google.com/drive/folders/1mOisEUkoLBcIcdkdGDiftq4IFAJ3xpzJ?usp=sharing)

[Submission 1](https://forms.gle/kTXzpaJqh3d4BvEWA)

[Lab 2](https://drive.google.com/file/d/1GOd6miwZ_PzcqubPt8dNLfbq_9X5TUHf/view?usp=sharing)

[Submission 2](https://forms.gle/5J7ZM1DvmP4TfiAG8)

[Lab 3](https://drive.google.com/file/d/1QW3YpNJQdYaIavexlQ9YVsiW7kgT6VOg/view?usp=sharing)

[Submission 3](https://forms.gle/9zEpec81YVr2LUzt7)

### Hackathon

Check out our hackathon website [here](https://rdi.berkeley.edu/llm-agents-hackathon/). Sign up for the hackathon [here](https://docs.google.com/forms/d/e/1FAIpQLSevYR6VaYK5FkilTKwwlsnzsn8yI_rRLLqDZj0NH7ZL_sCs_g/viewform) — every member of the team should signup individually. Then, complete the team creation form [here](https://docs.google.com/forms/d/e/1FAIpQLSdKesnu7G_7M1dR-Uhb07ubvyZxcw6_jcl8klt-HuvahZvpvA/viewform). There are no limits to team sizes.

For any questions, please visit our Hackathon FAQ [here](https://docs.google.com/document/d/1P4OBOXuHRJYU9tf1KH_NQWvaZQ1_8wCfNi3MOnCw6RI/edit?usp=sharing). You can also ask questions and find potential team members in our [LLM Agents Discord](https://discord.gg/NWVpQ9rBvd).

Submit your final hackathon project [here](https://forms.gle/jNr8nSH9Cy9qpYcu5) before December 17th, 2024 @11:59PM PST.

This page was generated by [GitHub Pages](https://pages.github.com).
