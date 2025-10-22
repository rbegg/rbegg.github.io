---
layout: post
title: "AI Pair Coding: What's Working for Me"
date: 2025-10-16 16:00:00
description: How Google Gemini has supercharged my learning
tags:
categories: ai-pairing
featured: true
---

A couple of months ago, I set out to build Max, an AI assistant for seniors. I explicitly decided to ignore both the
hype and the doom surrounding AI coding agents and simply get to work. Along the way, I discovered what, for me, is a
key to success.

My many interactions with Gemini 2.5 Pro range from amazing to clearly wrong and disappointing. But the real insight
and progress came from all the interactions that happened in between those two extremes, and no small amount of
perseverance.

## The Knowledge Challenge

The project itself is complex, requiring me to learn hands-on details about:

- Capturing audio, voice detection, speech-to-text, text-to-speech
- Managing the interaction with LLMs using Langchain Langgraph
- RAG (Retrieval-Augmented Generation) and MCP (Model Context Protocol) to add customized data and robust skills
- Docker's ecosystem and best practices to manage a flexible locally deployed solution composed of task specific
  services
- Infrastructure as code to effectively manage the build/test/deploy tasks to allow the project to evolve.

Each of these topics involves researching various tools and technologies. Often choosing between robust, complex
solutions vs. simpler, build-it-yourself approaches. Typically, this means creating a proof of concept and
integrating it into the larger project.

The journey has triggered me to reflect on how I, and teams I have worked with in the past, learn.

## How We Used to Learn

I have observed many cycles of new tools and technologies (packages, frameworks, etc.) promising to improve
**efficiency** and reduce maintenance costs. However, that gain is often diminished by the steep **learning curve**
and ongoing complexity.
It is also daunting to pick a stable solution you can rely on long-term and does not cause excessive bloat.

The core challenge is tackling the learning curve without getting side-tracked with a recursive list of issues with
dependencies. It often feels like you are trying to get out of a hole by digging deeper.

In order to get started, it is typical to find **tutorials** that walk you through a manageable (i.e. trivial) example.
If you're lucky, you can then find an example use case that's close enough to your own goals that it can bootstrap
your project. After a _few_ refactoring loops, you either have a workable **baseline** or you've learned enough to
abandon that approach and start over.

On the flip side, I've seen many teams fall into the _custom solution trap_. They decide their use case is simpler
and a custom solution will be faster. While this sometimes works, in my experience, additional requirements are
discovered and the custom solution grows in complexity until it's obvious the existing tools or technologies would
have been the better choice.

The root issue is the tools and technologies have evolved to handle a broad set of complex issues that are hard to
appreciate without the knowledge gained from experience. We learn best when we start with simple solutions, and then iterate
through a series of improvements. Over time, this knowledge evolves into best practices, design guidelines or
other terms meant to captured generalized knowledge.

## What Changes with an AI Agent

AI agents are clearly a great replacement for internet searches, summarizing topics or helping to debug
specific problems. Troubleshooting in general is a fantastic application of AI tools, as they can
process logs far faster than a human. There's no surprising insight here.

Where I found initial success was asking the agent to generate a **workable baseline**, but only after I had done a
quick tutorial. That initial bit of learning allowed me to provide much better context for my request.

What really drove my productivity was this cycle:

- Generate and stand-up a baseline solution for one of the many project components (grab a chunk of audio in a browser)
- Resolve blocking issues and achieve some early success (send audio over websocket)
- Prioritize the next area to focus on **understanding** (websockets vs http requests, binary vs text)
- Use insight to prioritize what to **refactor** now and what to defer for later (using a queue here may trigger
  refactoring elsewhere)
- Repeat for the next feature (send audio to speech-to-text service)

In other words, iterative development, balancing feature progress with good design refactoring, while pair coding
with an AI agent.

## The Key to Success

My key takeaway wasn't about the tools or even how to craft good prompts. Rather, it was realizing my productivity
and project success was driven by my **intent to learn**.
I wasn't just trying to complete an assignment or get code working to meet a deadline.

The more I learned and mastered the subjects:

- The more able I was to determine when to accept and when to reject a solution from the agent.
- It became more obvious what needed refactoring.
- I was aware of better follow-up questions to ask.

It was amusing and insightful to realize how the agent would readily agree the code it just wrote wasn't very good and
would suggest improvements—but only once I started asking more informed questions.
Gemini reminded me of a very confident senior developer, who always had an answer ready, but was not always
right. However, Gemini also has a lot more patience than most senior developers.

To get a more realistic experience, I may try setting a system prompt along the lines of: 🙂

```markdown
You are a grumpy experienced senior developer, who just wants to get back to writing their own code.
Be stingy with your compliments so they mean more.
```

Overall, approaching the AI agent as a partner for my own learning, rather than just a code-generator, made all the
difference. It is not just helping develop the project; it is supercharging my own capacity to learn and deliver.
