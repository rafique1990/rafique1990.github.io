---
title: "Welcome to My Personal Blog"
date: 2026-09-21
layout: post
categories: [General]
tags: [Introduction, Meta]
---

Welcome, and thanks for stopping by. This is where I write about the things I
build and think about as an **AI Engineer**. Most of it is about production LLM
systems, agent architectures, and the cloud infrastructure that keeps them
running.

## What I plan to write about

I want this to be useful, not promotional. Here is the kind of thing you can
expect:

- **Software engineering**: backend design, APIs, testing, and the everyday work
  that keeps systems reliable.
- **AI systems**: LLM orchestration, the Model Context Protocol (MCP), retrieval,
  evaluation, and guardrails, based on real production work.
- **Project updates**: short notes on what I am building and what I learned along
  the way.

I try to write things a working engineer can actually use. That means concrete
examples, honest trade-offs, and code you can run.

## A small demo

Since the blog is new, here is a small piece of CSS I like. It fades a card in
when you hover over it, using a keyframe animation:

```css
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(8px); }
  to   { opacity: 1; transform: translateY(0);   }
}

.card {
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.card:hover {
  animation: fadeIn 0.4s ease both;
  transform: translateY(-4px);
  box-shadow: 0 12px 30px rgba(0, 0, 0, 0.12);
}
```

The `both` fill mode keeps the card at its final state while you hover, so it
does not snap back. It is a small thing, but small things like this are what make
an interface feel finished.

More soon, including a longer post on the Model Context Protocol and how I use it
in production.
