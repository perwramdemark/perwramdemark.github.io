---
layout: post
title: "Vuejs.amsterdam 2026: Key Takeaways from day Two"
date: 2026-03-13
tags: [vue, javascript, conference, local-first, a11y, performance]
---

Day two at [Vuejs.amsterdam](https://vuejs.amsterdam/) continued the momentum with an equally impressive lineup of speakers diving into tooling evolution, accessibility, scaling experiences, and innovative architectural patterns.
Here are the standout insights from day two.

### 🚀 The Future of Vue Tooling & Build Performance

* [Evan You](https://twitter.com/youyuxi) Creator of Vue.<br/>
Speaking on **Improving Vue Language Tools** and the state of the ecosystem, Evan highlighted the launch of **Vite 8** with significant performance gains. Notably, **Rolldown** (the Rust-based bundler replacement) delivers 5-30% faster build times—a game changer for larger projects. He also introduced **VitePlus** and **oxlint**, positioning Vue's toolchain as a truly unified solution for modern web development.

* [Dragan Elijas](https://www.linkedin.com/in/draganaelijas/).<br/>
With 7 years of Vue.js at scale, Dragan brought battle-tested insights on maintaining large-scale Vue applications, emphasizing architectural patterns and team coordination strategies.

* [Tim Benniks](https://www.linkedin.com/in/timbenniks/).<br/>
Explored performance optimization strategies, drawing parallels to "Need for Speed Rivals" — the importance of consistent, predictable performance in modern applications.

### ♿ Accessibility: A Core Design Principle

* [Julian Barr](https://www.linkedin.com/in/julian-barr/).<br/>
Focused on **A11Y (Accessibility) as a gateway to Usability**. Julian emphasized Dan Norman's classic "The Design of Everyday Things," arguing that accessibility isn't a feature—it's fundamental to great design. When you build for accessibility, you build for everyone.

### 🏗️ Learning from Real-World Experience

* [Louella Creemers](https://www.linkedin.com/in/louellacreemers/), Microsoft MVP.<br/>
Shared **"One Year of Vue.js Mistakes"**—a candid look at common pitfalls and lessons learned. Her insights bridged the gap between theory and practical development challenges.

### 📱 Local-First Architecture: The New Paradigm

* [Alexander Opalic](https://alexop.dev/).<br/>
Introduced the concept of **Local-First Software** (based on the influential 2019 paper by Ink & Switch). Alexander explained how modern applications can prioritize offline-first capabilities using **IndexedDB or SQLite** as local data stores, with synchronization strategies like **LWW (Last Write Wins)** ensuring consistency. This shift enables better user experience, privacy, and resilience.

### 🎯 Bundle Analysis & Tree-Shaking Pitfalls

* [Serko Vincent Ngai](https://serko.dev/), based in Hong Kong.<br/>
Tackled a critical but often overlooked issue: **When Tree-Shaking Fails**. Serko explained how side effects in dependencies (like `z.objects()`) can prevent proper tree-shaking, inflating bundle sizes. He recommended tools like **vite-bundle-analyzer** to visualize and debug these issues before they hit production.

### 🎨 Graphics & Web Interoperability

* [Ramona Schwering](https://www.linkedin.com/in/ramona-schwering/).<br/>
Presented **"Let's Draw Security"**—bringing attention to security considerations in visual design and component implementation.

* [Jakob Schröter and Helian Riviera](https://www.linkedin.com/in/jakob-schr%C3%B6ter/).<br/>
Showcased **PixiJS** integration with Vue.js, demonstrating how to port desktop graphics libraries to the web. Their session highlighted the power of Vue as a framework for diverse application types, from traditional web apps to graphics-heavy experiences.
