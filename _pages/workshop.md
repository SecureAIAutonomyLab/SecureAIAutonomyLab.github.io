---
# layout: archive
title: "Workshop Page Hello World"
permalink: /workshop/
author_profile: true
# <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
---
### Hello World ###
##### Workshop Lead: Mazal Bethany #####
•Presenters: Emet Bethany, Mohammad Bahrami Karkevandi
•Day 1: High Performance Computing
 This workshop covers the fundamentals of running jobs on UTSA’s ARC HPC systems that offer GPU computing capabilities to students. Attendees were introduced to networking, storage, job submission, and best practices for using common software with LLMs. With assistance from ARC's administrative staff, students were given access to GPUs on ARC. During the workshop, attendees connected to ARC and ran commands to ensure everyone could access and use ARC. Utilizing GPU access, attendees participated in a hands-on assignment to fine-tune a small LLM, Microsoft Phi-2, on an instruction-based dataset.
•(Link to workshop materials)
•Day 2: HuggingFace Workshop
 This workshop covers leveraging the Hugging Face platform for machine learning tasks. Attendees learn the basics of getting started with Hugging Face, exploring the Model and Dataset Hub, and selecting appropriate models, particularly Large Language Models. The workshop includes fine-tuning techniques and provides code examples for loading models/datasets, creating training scripts, and utilizing other useful functions. Attendees also participate in a practical demonstration, creating a simple chatbot using an LLM (Llama3) from Hugging Face, complete with chat history functionality.
•(Link to workshop materials)
•Day 3: Prompt Engineering Workshop
 This workshop covers mastering prompt engineering techniques for various Large Language Models, including open-source models and LLM APIs like OpenAI's GPT. Attendees learn about chat templates, effective prompting strategies, and core principles of prompt engineering. The session also includes LLM sampling hyperparameters crucial for model inference. To reinforce learning, attendees engage in hands-on assignments, applying prompt engineering techniques using an API and experimenting with different sampling parameters to observe their effects firsthand.
•(Link to workshop materials)
•Day 4: Agent Roles Workshop
 This workshop covers exploring and implementing various agent roles in AI systems. Attendees learn to define and assign distinct roles to understand how agents can perform different tasks. The session emphasizes practical applications and hands-on learning, including the validation of multi-lingual capabilities to ensure robust performance across languages. Attendees have the opportunity to create prompts and roles based on their unique interests or areas of expertise, making the learning experience highly personalized and engaging.
•(Link to workshop materials)
•Day 5: Incorporating External Information to LLMs Workshop
 This workshop covers enhancing Large Language Models with external information using Retrieval-Augmented Generation (RAG) techniques. Attendees learn about vector databases for efficient data retrieval and explore semantic similarity searching to improve the relevance of retrieved information. The session includes a comprehensive example of implementing a complete RAG system that can be used with any LLM to enhance its generations. Attendees also benefit from a full code walkthrough, learning how to implement a simple RAG system for LLMs, providing them with practical, hands-on experience.
•(Link to workshop materials)

{% if site.author.googlescholar %}
   
{% endif %}

{% include base_path %}

{% for post in site.workshop reversed %}
  {% include archive-single.html %}
{% endfor %}
