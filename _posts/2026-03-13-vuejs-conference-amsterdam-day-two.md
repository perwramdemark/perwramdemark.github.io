---
layout: post
title: "Vuejs.amsterdam 2026: Key Takeaways from day Two"
date: 2026-03-13
tags: [vue, javascript, conference, local-first, a11y, performance]
---

Day two at [Vuejs.amsterdam](https://vuejs.amsterdam/) continued the momentum with an equally impressive lineup of speakers diving into tooling evolution, accessibility, scaling experiences, and innovative architectural patterns.
Here are the standout insights from day two.

<div style="display: flex; gap: 10px;">
  <img src="/assets/images/20260313-vue-talk-ewan-you.jpeg" style="width: 48%; height: auto;">
  <img src="/assets/images/20260313-ewan-you-talk-viteplus.jpeg" style="width: 48%; height: auto;">
</div>

### 🚀 The Future of Vue Tooling & Build Performance

* [Evan You](https://twitter.com/youyuxi) Creator of Vue.<br/>
Speaking on **Improving Vue Language Tools** and the state of the ecosystem, Evan highlighted the launch of **Vite 8** with significant performance gains. Notably, **Rolldown** (the Rust-based bundler replacement) delivers 5-30% faster build times. Game changer for larger projects.
<br/>He also introduced [**VitePlus**](https://viteplus.dev/), positioning Vue's toolchain as a truly unified solution for modern web development. One tool to rule them all!<br/>
Evan's talk was truly intensive with a lot of releases and new stuff to cover.

* [Dragan Elijas](https://www.linkedin.com/in/draganelijas).<br/>
With 7 years of Vue.js at scale, Dragan brought insights on maintaining large-scale Vue applications, emphasizing architectural patterns and team coordination strategies.

* [Tim Benniks](https://timbenniks.dev/).<br/>
Explored performance optimization strategies, drawing parallels to "Need for Speed Rivals" — the importance of consistent, predictable performance in modern applications.
Presentation-wise, he delivered the A-game but maybe not too many takeaways.

### ♿ Accessibility: A Core Design Principle

* [Julian Burr](https://bsky.app/profile/julianburr.de).<br/>
Focused on **A11Y (Accessibility) as a gateway to Usability**. Julian emphasized Dan Norman's classic "The Design of Everyday Things," arguing that accessibility isn't a feature. Fundamental to great design. When you build for accessibility, you build for everyone.
<br/>I've added the book to my Reading List.

### 🏗️ Learning from Real-World Experience

* [Louella Creemers](https://louella.dev/), Microsoft MVP.<br/>
Shared **"One Year of Vue.js Mistakes"** a look at common pitfalls and lessons learned. Her insights bridged the gap between theory and practical development challenges.

### 📱 Local-First Architecture: The New Paradigm

* [Alexander Opalic](https://alexop.dev/).<br/>
Introduced the concept of **Local-First Software** (based on the influential 2019 paper by Ink & Switch). Alexander explained how modern applications can prioritize offline-first capabilities using **IndexedDB or SQLite** as local data stores, with synchronization strategies like **LWW (Last Write Wins)** ensuring consistency. This shift enables better user experience, privacy, and resilience.
He also made a great pitch for the [Local First Conf 2026](https://www.localfirstconf.com/) in July, Berlin. Would be great to visit!

### 🎯 Bundle Analysis & Tree-Shaking Pitfalls

* [Serko Vincent Ngai](https://serko.dev/), based in Hong Kong.<br/>
Tackled a critical but often overlooked issue: **When Tree-Shaking Fails**. Serko explained how side effects in dependencies (like `z.objects()`) can prevent proper tree-shaking, inflating bundle sizes. He recommended tools like **vite-bundle-analyzer** to visualize and debug these issues before they hit production.
Really enjoyed this talk from this great humble guy and it was his first visit in Europe.

### 🎨 Graphics & Web Interoperability

* [Ramona Schwering](https://www.ramona.codes/).<br/>
Presented **"Let's Draw Security"** bringing attention to security considerations. Her whole presentation she drew with a pencil and gave a great visual representation of the domain and problem to solve.

* [Jakob Schröter and Helian Riviera](https://github.com/jschroeter).<br/>
Showcased **PixiJS** integration with Vue.js, demonstrating how to port a huge legacy app in an agile manner to a future proof Vue.js application  and describing a lot of hurdles they had to overcome.
