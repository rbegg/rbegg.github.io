---
layout: post
title: Why I'm Building Max
date: 2025-10-16 15:09:00
description: An Ethical AI Assistant for a Better Quality of Life
tags:
categories: max-project
featured: true
---

My mission is to create 'Max'—a viable, locally-hosted AI assistant—to help seniors who feel left behind by technology.

I've witnessed how quality of life suffers when technology becomes a barrier, preventing them from:
- Operating a smart TV
- Messaging, calling or video-chatting with family and friends
- Managing appointments or navigating their environment

The initial focus/priority is on the seniors struggling with mild to moderate dementia.

## Core Principles

1. Max must be capable of running on locally deployed hardware with all context data and collected data kept locally.
  - This is the best way to keep the user's best interests in mind
  - Secure cloud deployments may be acceptable in some cases, but it must not be dependent on any entity.
  - A working assumption is using current consumer GPUs will be a viable stand-in for the expected availability of more compact HW solutions
2. Max will require a family member, or other trusted support person to configure and manage the deployed solution.
  - This role's main task is to load in relevant context data - daily schedule, personal contacts, family tree, etc., so Max can digest it. 
  - Remote access is required, and must be secure.
  - Passkeys stored locally should help with managing access to various services (streaming, msging, video calling etc.)
  - Summaries of Max's interactions and Audit capabilities should be included and made available.
3. Max must restrict interaction to the provided context, and not expose a general chatbot experience.
  - 