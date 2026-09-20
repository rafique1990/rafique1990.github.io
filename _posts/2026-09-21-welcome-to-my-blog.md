---
title: "Welcome to My Personal Blog"
date: 2026-09-21
layout: post
categories: [General]
tags: [Introduction, Meta]
---

Welcome, and thanks for stopping by. This is where I write about the things I
build and think about as an **AI Engineer** — mostly production LLM systems,
agentic architectures, and the cloud infrastructure that keeps them honest.

## What I plan to write about

I want this space to be practical rather than promotional. Expect posts on:

- **Software engineering** — backend design, APIs, testing, and the unglamorous
  work that makes systems reliable.
- **AI systems** — LLM orchestration, the Model Context Protocol (MCP),
  retrieval, evaluation, and guardrails, drawn from real production work.
- **Project updates** — short notes on what I'm currently building and what I
  learned the hard way.

My bias is toward writing that a working engineer can actually use: concrete
examples, honest trade-offs, and code you can run.

## A small demo

Since this blog is freshly set up, here is a tiny bit of CSS I like for making
cards feel alive — a **fade-in on hover** built from a keyframe animation:

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

The `both` fill mode keeps the element at its final state after the animation
finishes, so the card doesn't snap back while you're still hovering. Small
detail, but it's the kind of polish that separates a prototype from a product.

More soon — including a deep dive into the Model Context Protocol and how I use
it in production.
