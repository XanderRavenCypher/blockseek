---
layout: default
title: Home
nav_order: 1
permalink: /
---

<div align="center">
<img src="logo.png" alt="BlockSeek Logo" width="200"/>
</div>

# Welcome to BlockSeek

BlockSeek combines state-of-the-art AI with blockchain technology to revolutionize cryptocurrency trading and analysis. For comprehensive documentation, please refer to our [README](./README.md).

## 🎮 Interactive Demo

Experience BlockSeek's capabilities firsthand through our interactive demo platform:

<div class="demo-features">
  <div class="demo-card">
    <h3>🤖 AI Trading Assistant</h3>
    <p>Test our AI-powered trading recommendations and market analysis in real-time.</p>
    <a href="https://www.blockseek.ai" class="demo-button">Try Assistant</a>
  </div>
</div>

> **Note**: The demo environment uses simulated data and paper trading. No real funds are involved.

## Quick Navigation

- [Architecture Overview](./architecture/overview.md)
- [Getting Started](./getting-started.md)
- [Dataset](./technical/dataset.md)
- [Contributing](./contributing.md)
- [Roadmap](./roadmap.md)

## Connect With Us

- [GitHub Repository](https://github.com/smashound/blockseek.ai)
- [Twitter](https://twitter.com/blockseekai)
- [Telegram](https://t.me/blockseekai)

<style>
.demo-features {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.demo-card {
  padding: 1.5rem;
  border: 1px solid var(--border-color);
  border-radius: 8px;
  background: var(--background-secondary);
  transition: transform 0.2s ease;
}

.demo-card:hover {
  transform: translateY(-4px);
}

.demo-card h3 {
  margin-top: 0;
  color: var(--heading-color);
}

.demo-button {
  display: inline-block;
  padding: 0.5rem 1rem;
  margin-top: 1rem;
  background: var(--link-color);
  color: white;
  text-decoration: none;
  border-radius: 4px;
  transition: background 0.2s ease;
}

.demo-button:hover {
  background: var(--link-hover-color);
  text-decoration: none;
}
</style>
