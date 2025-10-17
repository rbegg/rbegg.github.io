---
layout: post
title: "AI Pairing: What's Working for Me"
date: 2025-10-16 16:00:00
description: How pairing with Google Gemini has supercharged my learning
tags:
categories: ai-pairing
featured: true
---

A couple of months ago I set out to build Max, an AI assistant for seniors struggling with technology.
I consciously ignored both the hype and the doom around using AI coding agents and got to work,
and along the way discovered a key to success.

I have chat responses that amazed me and could be used to support the hype,
and others that could prove AI's generate crap!
The real insight and progress came from all the interactions that
that happened in between those two extremes.

## The Knowledge Challenge

The project itself is complex and requires learning about:

- capturing audio and voice detection
- converting the speech to text
- analyzing the text with an llm
- determining appropriate responses
- converting the text response back into speech

Each of these topics requires:

- researching available tools and services
- choosing between existing robust/complex solutions and basic build it yourself approaches
- a proof of concept
- integration into the larger project with iterative refactoring

## How did we learn before AI Coding Agents

The software industry is constantly producing tools and frameworks to improve developer
efficiency. Typically, the gain is diminished by all the extra learning curve and initial
research require to pick a solution you can rely on long term.

For each tool/library/framework, you can find many tutorials that walk you through to success in a
manageable/trivial example.  
If you are lucky, you can find a deeper complete example scenario/project that is close enough to
yours to bootstrap your own project.

Just a few more than expected refactoring loops later you have a workable baseline,
... or you have learned enough to abandon that approach and look for another!

As you approached productivity:

- you would have a workable baseline
- you became familiar with the extensive reference documentation
- internet searches would typically find others struggling with a similar enough problem to provide some clues

## The Custom Code Trap

On the flip side, I have observed many teams decide their use case is far simpler, and a custom solution
will be faster to implement and avoid the bloat of the existing tool/library/framework.

Sometimes this works out. However, in my experience, the team usually discovers new requirements, and their
custom solution has to continually grow in complexity. Even when it is obvious the existing solution would
have been the better choice, the cost of switching is deemed higher.

## What Changes with an AI Coding Agent

It is clear that AI Agents are great replacement over simple internet searches for researching solutions
to problems, given the probability that someone else has experienced the same issue. They can also process
large logs far faster than humans. No surprising insight here.

I found a lot of success with asking the agent to generate a workable baseline **after** a quick tutorial
which allowed me to learn enough to provide better context to my request.

What drove my productivity was standing up a baseline solution for the many components, and then refactoring
each in turn as I shifted my focus to understanding and improving each.

For example, I could use a generated Nginx reverse proxy configuration for dev and production to enable
https connections from outside my dev environment. Later, refactoring led to understanding in greater
detail the attributes of the configuration, and how to manage production.

## The Key to Success

My key takeaway was not about the tools or the AI Agent. It was not about how to craft good prompts.

Rather it was realizing my productivity was driven by my intent to learn. I was not tyring to complete
an assignment for marks, or only focused on code that worked to meet a deadline.

The more I learned and mastered:

- The more able I was to determine when to reject a solution by the AI agent
- It became more obvious what needed refactoring
- I was aware of better follow-up questions to ask

It was amusing and insightful to realize how the Agent would readily agree the code they wrote was not very
good, and suggest improvements once I started asking more questions.
