# Avery Yen
Hi, I'm Avery. I'm a software engineer turned AI researcher. I'm a Research Assistant to David Bau, a member of MIT AI Alignment (MAIA), and pursuing my MS in Computer Science at Northeastern University, studying human-AI interaction and AI safety.

Before transitioning to AI research, I spent over 12 years as a software product engineer, with my longest tenure at Pivotal Labs.

## Research Interests

I believe understanding how AI systems behave with and against human interests is the most fundamental and urgent AI research question. I'm particularly interested in studying and evaluating frontier Agentic AI systems to understand capabilities, risks, and shortcomings.

My current work focuses on how AI agents work in multi-agent, multi-human conditions; how model provider values and constraints shape AI behavior; and how to build evaluation infrastructure that reflects actual stakes. 

### Selected Projects
- [Multi-Agent Social Deduction Gaming Arena](https://lmdeceptionarena.averyyen.dev/) (project lead): Live evaluation platform benchmarking frontier LLMs on long-horizon strategic reasoning in multi-agent social environments. Continuous leaderboard tracks GPT, Claude, Gemini, DeepSeek, Kimi, and others. Forthcoming study on sustained goal pursuit, coalition dynamics, social deception and deduction abilities across extended multi-turn interactions using a well-loved social deduction game.
- [Agents of Chaos](https://agentsofchaos.baulab.info/) (core contributor with Shapira, Wendler, Bau et al.) OpenClaw/Agentic AI red-teaming study where we expose and catalog urgent problems with agentic AI, suggesting research directions including better engineering and architecture for the future of multi-human, multi-agent AI systems. Across numerous case studies, we document how agents operating at high autonomy but limited competence produce diverse failures in security, privacy, information integrity, and social understanding — failures that don't appear under standard benchmark evaluation. [arxiv: 2602.20021](https://arxiv.org/abs/2602.20021)
- [Forbidden Topics in LLMs](https://forbidden.baulab.info/) (conference submission refinement in collaboration with Rager, Bau et al.): Empirical mapping of refusal topics across frontier language models including American and Chinese-developed systems. Collaborating to improve Rager's prefill crawling methodology for surfacing undisclosed refusal behavior to dramatically improve elicitation rates and robustness. Forthcoming conference submission.

## Blog Posts

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url | relative_url }})** - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## Other Interests
I've been playing classical cello since I was about 7, having previously subbed with the Boston Philharmonic, and continue to play today as part of the [Mercury Orchestra](https://www.mercuryorchestra.org/) and various other groups.

## Contact

Feel free to find me on [LinkedIn](https://linkedin.com/in/averyyen/).
