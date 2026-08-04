---
layout: about
title: about
permalink: /
subtitle: Ph.D. Candidate in Applied Mathematics, Dartmouth College. Game theory, moral alignment, and scalable oversight.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Office 244</p>
    <p>Kemeny Hall, Dartmouth College</p>

selected_papers: False # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: False # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: False
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a Ph.D. candidate in applied mathematics at Dartmouth College, where I study game theory and artificial intelligence (AI). In my game-theory research I model social interactions by reducing complex networks to concise, tractable representations. These models help explain and predict phenomena across political science, AI, evolutionary ecology, and business. My game-theory work focuses on several related themes:

- **Influence and allocation games.** Models of competition for limited resources in which players exert influence to secure them. My thesis introduces the [_influencer's game_](https://markslovett.github.io/InflGame/), in which each player's influence is centered on its position in space, so position itself becomes a strategy. Examples include political campaigns (candidates competing for votes) and platform competition for users; similar dynamics arise in machine-learning settings where agents compete for attention or data.
- **Evolutionary game theory.** The study of how strategies evolve in populations. By reducing complex population dynamics to tractable mathematical models, evolutionary game theory yields accurate predictions of agent behavior and has applications in ecology (for example, [Tilman et al.](https://www.nature.com/articles/s41467-020-14531-6)), cooperation studies (for example, [Traulsen et al.](https://royalsocietypublishing.org/doi/full/10.1098/rstb.2021.0508)), decision making, and AI–human cooperation.

In AI, I study the incentive structures and learning environments that shape agent behavior: essentially, which "games" drive learning and why. I investigate how formally specified objectives influence learning dynamics and emergent strategies in both simulated and real-world settings, with most of my work in large language models and multi-agent reinforcement learning. The reason to characterize these games is safety rather than performance. Failure modes such as collusion, deception, and reward hacking are equilibrium properties rather than accidents of a particular training run, so an incentive-level account tells us which failures a system is being pushed toward before we have to catch them in evaluation.

This runs in two directions. On the reward-design side, I work with Elizaveta Tennant through the [MARS program](https://caish.org/mars) on moral alignment for LLM agents, extending her framework of explicitly specified intrinsic rewards ([paper](https://arxiv.org/abs/2410.01639)). On the oversight side, I work with [Soroush Vosoughi](https://www.cs.dartmouth.edu/~soroush/) on ensemble and router dynamics for language models, using the influencer's game as a lens on scalable oversight. <!-- TODO: link to the ensemble project once public -->

Combining insights from AI and game theory has major applications for AI–AI, human–human, and especially human–AI interactions. I think this matters urgently. As systems become more capable and more autonomous, misalignment becomes harder to catch after the fact, and game theory is unusually well suited to the problem because it reasons about behavior through incentives. That lets us construct the equilibria we want rather than only measure the dispositions a trained model happens to arrive at. Two of my favorite cases for AI safety and game theory: Redwood Research on [the case for ensuring that powerful AIs are controlled](https://blog.redwoodresearch.org/p/the-case-for-ensuring-that-powerful) and the Cooperative AI Foundation's [multi-agent risks report](https://arxiv.org/abs/2502.14143);..

Beyond research, I have thoroughly enjoyed teaching at Dartmouth. I design scalable, technology-enabled course frameworks and curricula that improve delivery and student experience. My teaching emphasizes clear learning objectives, reproducible assignments, and practical tools that make courses easier to run and extend. I have five years of TA experience across 12 courses at two institutions, and I have independently taught two courses on evolutionary game theory.

Outside of academics, I am a senior member of [Amifore Consulting and Management LLC](https://www.amifore.com/), a startup delivering ethical consulting solutions to emerging businesses. I work in AI and innovation consulting for clients internationally, including in Switzerland, implementing strategic project management systems and building AI-assisted workflows. This work has sharpened my sense of how AI research translates into practice, and of what responsible deployment actually asks of a small organization.
