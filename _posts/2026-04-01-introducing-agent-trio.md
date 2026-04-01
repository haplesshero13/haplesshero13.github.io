---
layout: post
title: "Introducing agent trio"
author: Avery Yen
date: 2026-01-21
tags: AI, agents, coding
---
**tl;dr:** Use **agent trio** [https://github.com/haplesshero13/agent-trio](https://github.com/haplesshero13/agent-trio) to introduce natural-language-only, **selective friction** to your agentic activities to *minimize regretted work* and *deliberately promote human understanding*.

## What got us here?
Once upon a time, humans hand-wired computers to program them. Thankfully, someone invented silicon chips.

People started sharing source code libraries, and the programmer became responsible for context-keeping and logical abstractions, not reinventing architectural decisions.

There was, however, a pesky problem. Humans have annoying needs like eating, sleeping, and needing to constantly update their understanding. Along came the agentic coder, promising to remove those pesky bottlenecks. Now, you can shit out as many lines of code per day as you can afford to generate and store on disk, and many people view that as a feature of agentic software engineering.

Back in the before times, I used to write every line of code, by hand, with another human pushing me to be my best. When pairing or ensembling, I came to rely on my colleagues' independent, continuously evolving understanding and judgment, while offloading mechanical verification to machines.

Today, we can produce technical, context, and comprehension debt faster than you can say "Claude Code". The mechanics of the software engineer has been "disrupted", but ultimately, you are responsible for what code/docs/artifacts you (directly or causally via prompting) commit. 

The most important feature of constantly pairing and using autonomous verification via tests and CI was to use _selective friction_ to allow shipping good features and debugging to be painless, while minimizing _regretful, wasteful output_. Agentic coding should be like that, too!
## What is it?

**agent trio** is a tiny, zero-code bootstrap for agentic software work. You (or your agent) copy it into a new or existing repo to get a simple agentic coder loop, centered around a few explicit primitives: file-based handoffs, human-readable artifacts, fresh agent-context reviewer, and resumable state. 

You'll get three (sub)agents, max, this way. Hence the name. You can minimize overhead by using one agent and a subagent, and then you can be the third member of the trio. You can use one model provider for the whole thing, or go rainbow. It's up to you. (Your setup agent will ask you what you want.)

**agent trio** is *not* a swarm framework, and it is *not* trying to maximize output. It is a lightweight way to encourage you to spend your best agentic tokens on reasoning, planning, and verification, while making scoped agent work autonomous and cheap.

The only requirement is one coding agent that can spawn a subagent (Claude, Codex, OpenCode, etc.) and can follow instructions well.

## Why another framework?
Many coding agent skills or harnesses focus on maximizing one thing at the expense of another.

**agent trio** helps you steer your coding agents to reason better, work more independently, _and_ produce less waste at the same time by introducing _principled amounts of autonomy and friction in selective ways_.

Natural language is the best way we know of today to steer agentic behavior, which is why this repo contains zero code. The code will get outdated, anyway.

Rather than introduce bureaucracy into the system, we ask your agent to produce autonomous iterations that are scoped, well-reasoned, reviewed, self-improving, and resumable. The human and head agent spend their precious time and reasoning tokens planning, then agents operate until multiple agents have converged on an outcome, despite their independent contexts: joint approval, or human escalation.

Let us know how [**agent trio**](https://github.com/haplesshero13/agent-trio) works for you!
