---
layout: post
title: "Vuejs.amsterdam 2026: Key Takeaways from day One"
date: 2026-03-12
tags: [vue, ai, javascript, conference]
---

An intense and inspiring two days at [Vuejs.amsterdam](https://vuejs.amsterdam/). Great venue and awesome people in the midst of Amsterdam!
Here are the top insights from the leading voices from day one.

<div style="display: flex; gap: 10px;">
  <img src="/assets/images/2026-03-12-vuejsamsterdam-welcome.jpeg" style="width: 48%; height: auto;">
  <img src="/assets/images/20260312-amsterdam-dayone-1.jpeg" style="width: 48%; height: auto;">
</div>

### 🚀 Core Vue & Nuxt Evolution
* [Eduardo San Martin Morote](https://x.com/posva) creator of Vue Router, Pinia.<br/>
You should really look into **File-Based Routing:** in [Vue Router](https://router.vuejs.org/file-based-routing/) which I haven't used yet.
Eduardo introduced Type-Safe URL/Paths 💯.

* [Guillaume Chau](https://akryum.dev/) introduced [rstore](https://rstore.dev/).<br/>
Powerful alternative for Pinia with quite a lot of transport protocols already implemented WS and offline-first.

* [Reza Baar](https://rebaar.com/) emphasized "Thinking in Signals."<br />
Pro tip: Use `shallowRef()` for large data lists to optimize reactivity.

* [Daniel Roe](https://roe.dev/) leading Nuxt.<br/>
Me and Daniel have in common having climbed the "mountain" [Arthur's Seat](https://en.wikipedia.org/wiki/Arthur's_Seat).

* [Julien Huang](https://www.julien-huang.dev/) stop making these mistakes in vue.js and Nuxt.<br/>
Issues could be Hydration mismatch or [CLS](https://developer.mozilla.org/en-US/docs/Glossary/CLS) (Cumulative Layout Shift).

### 🤖 The Rise of AI in Vue

* [Elise Patrikainen](https://github.com/ElisePatrikainen) hosting the Paris vue.js meetup.<br/>
Showed how to build an [MCP Sever](https://modelcontextprotocol.io/) for Vue using the **Anthropic SDK**, bridging the gap between LLMs and your local code.
`new McpServer()`

* [Rijk van Zanten](https://rijk.nyc/) Dutch in Brooklyn, NYC.<br/>
Talked about Agentic AI and building a Todo App where the AI agent interacts directly with **Pinia**, either showing the UI or communicating directly with the backend.

* [Jeroen de Kruijf](https://www.linkedin.com/in/jeroen-de-kruijf-9a066310b/) Identity Specialist working for auth0.<br/>
talked about  **HITL (Human in the Loop)** framework for Trustworthy AI.

* [Pooya Parsa](https://pi0.io/) creator of Nitro, h3, and unJS.<br/>
Pooya pushed the boundaries of the web by demonstrating an entire **operating system built in the browser**.

