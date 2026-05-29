# Pub/Sub Best Practices — A Beginner's Tutorial

> A plain-English, visual guide to Google Cloud Pub/Sub best practices — with diagrams, console mockups, and copy-pasteable Python snippets.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Made with HTML](https://img.shields.io/badge/built%20with-HTML%20%2B%20CSS-orange.svg)](index.html)
[![GitHub Pages](https://img.shields.io/badge/demo-GitHub%20Pages-brightgreen.svg)](https://mdhabibi.github.io/pubsub-best-practices-tutorial/)

A single, self-contained webpage that teaches Pub/Sub best practices to developers who are new to messaging systems. No build step, no dependencies — just open it in a browser.

## 🔗 Live demo

Once GitHub Pages is enabled (see below), the tutorial is served at:

```
https://mdhabibi.github.io/pubsub-best-practices-tutorial/
```

## ✨ What's inside

- **Plain-English explanations** of every best practice, with real-world analogies
- **Custom SVG diagrams** for visual learners (batching, pull vs. push, regional isolation, dead-letter flow, IAM, and more)
- **GCP console mockups** showing the screen you'd land on for each step
- **Python code snippets** (using `google-cloud-pubsub`) for the items where code helps
- A **glossary** and a **one-page checklist**

### Topics covered

| Section | Focus |
| --- | --- |
| What is Pub/Sub? | Core concepts: topics, messages, publishers, subscribers |
| Publishing | Batching, ordering keys, regional endpoints, flow control, retries |
| Subscribing | Pull vs. push, process-before-ack, StreamingPull, flow control |
| Latency & Reliability | Disabling batching, regions, isolation, monitoring, quota alerts |
| Client Library | Reusing clients, staying updated, async, lease management |
| Features | Push subscriptions, seek, retention, dead-letter topics, regions |
| Patterns & Testing | Naming, IAM, the emulator, labels, retention duration |

## 🚀 View it locally

Clone the repo and open the file — that's it:

```bash
git clone https://github.com/mdhabibi/pubsub-best-practices-tutorial.git
cd pubsub-best-practices-tutorial
open index.html        # macOS  (use "start" on Windows, "xdg-open" on Linux)
```

## 📂 Repository structure

```
pubsub-best-practices-tutorial/
├── index.html      # the tutorial (entry point for GitHub Pages)
├── README.md
├── LICENSE
└── .gitignore
```

## 🙏 Acknowledgements

This guide summarizes publicly available best practices for Google Cloud Pub/Sub.
Pub/Sub is a product of Google Cloud. Diagrams and console views are original
illustrations created for educational purposes and are not official Google assets.

## 📄 License

Released under the [MIT License](LICENSE).
