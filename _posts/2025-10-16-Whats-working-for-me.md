---
layout: post
title: "Beyond the Hype: What's Working for Me in AI Pairing"
date: 2025-10-16 16:00:00
description: How pairing with Google Gemini has supercharged my learning
tags:
categories: ai-pairing
featured: true
---

[//]: # "Suggested Titles:"
[//]: # "AI Pairing: A Better Way to Learn"
[//]: #
[//]: # "How I Use AI Pairing to Accelerate My Learning"
[//]: #
[//]: # "Beyond the Hype: What's Working for Me in AI Pairing"

A couple of months ago, I set out to build Max, an AI assistant for seniors. I consciously decided to ignore both the
hype and the doom surrounding AI coding agents and simply get to work. Along the way, I discovered what, for me, is a
key to success.

I've had all kinds of interactions. I have chat responses that were amazing, and others that were clearly wrong. But the
real insight and progress came from all the interactions that happened in between those two extremes.

## The Knowledge Challenge

The project itself is complex, requiring me to learn about:

- Capturing audio and voice detection
- Converting that speech to text
- Analyzing the text with an LLM
- Determining appropriate responses
- Converting the text response back into speech

Each of these topics involves researching tools, choosing between robust, complex solutions and simpler,
build-it-yourself approaches, creating a proof of concept, and integrating it into the larger project.

## How We Used to Learn

In software, new tools and frameworks constantly promise to improve efficiency, but that gain is often diminished by the
steep learning curve required to pick a solution you can rely on long-term.

Typically, you find tutorials that walk you through a manageable example. If you're lucky, you find a complete project
that's close enough to your own to bootstrap from. After a few refactoring loops, you either have a workable baseline or
you've learned enough to abandon that approach and start over.

On the flip side, I've seen many teams fall into the Custom Code Trap. They decide their use case is simpler and a
custom solution will be faster. While this sometimes works, in my experience, new requirements inevitably appear, and
the custom solution grows in complexity until it's obvious the existing framework would have been the better choice.

## What Changes with an AI Agent

AI agents are clearly a great replacement for simple internet searches, and they can process large logs far faster than
a human. There's no surprising insight there.

Where I found a lot of success was in asking the agent to generate a workable baseline, but only after I had done a
quick tutorial. That initial bit of learning allowed me to provide much better context for my request.

What really drove my productivity was this rhythm: I could stand up a baseline solution for one of the many components,
and then refactor it as I shifted my focus to understanding and improving that specific piece.

For example, I used a generated Nginx reverse proxy configuration to enable HTTPS connections. This got me up and
running quickly. Later, as I refactored and iterated, I learned the details of the configuration attributes and how to
properly manage it for production.

## The Key to Success

My key takeaway wasn't about the tools or even how to craft good prompts. Rather, it was realizing my productivity was
driven by my intent to learn. I wasn't just trying to complete an assignment or get code working to meet a deadline.

The more I learned and mastered the subjects:

- The more able I was to determine when to reject a solution from the AI.
- It became more obvious what needed refactoring.
- I was aware of better follow-up questions to ask.

It was amusing and insightful to realize how the agent would readily agree the code it just wrote wasn't very good and
would suggest improvements—but only once I started asking more informed questions.

Approaching the AI as a partner for my own learning, rather than just an answer-generator, made all the difference. It
didn't just help me build the project; it made me a better developer in the process.
