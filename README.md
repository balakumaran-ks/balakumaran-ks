# Hi, I'm Balakumaran K S (Bala) 👋

I build full-stack and AI-powered web apps with **Next.js, TypeScript and MongoDB**, and I solve problems in **Java**. I'm a **LeetCode Guardian with 500+ problems solved**.

I'm studying B.E. Electrical & Electronics Engineering at Nandha Engineering College (Anna University), graduating in **2027**, and I'm looking for **software engineering roles**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-balakumaranks-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/balakumaranks)
[![LeetCode](https://img.shields.io/badge/LeetCode-Guardian%20%C2%B7%20500%2B%20solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/balakumaranks)

## What I'm working on

- **[DocuMind](https://github.com/balakumaran-ks/DocuMind)**: an AI app that answers questions about your PDFs and cites the page ([live demo](https://documind99.vercel.app))
- **Backend system design**: job queues, caching and real-time sync (designs below, implementations in progress)
- **Data structures and algorithms** in Java, every day on LeetCode

## Featured projects

### [DocuMind](https://github.com/balakumaran-ks/DocuMind) · [Live demo](https://documind99.vercel.app)

Chat with your PDFs. Upload a document, ask questions, and get streamed answers that cite the exact page, or a clear "that isn't in this document".

- Retrieval-augmented generation (RAG) with **hybrid search**: MongoDB Atlas Vector Search and keyword search, merged with rank fusion
- Ask across several documents at once, with clickable page-level citations
- Google sign-in, with every query and search filtered by user
- Measured on a hand-written eval set: **96% citation accuracy**, **100% refusal** on questions the documents can't answer, and **100% of prompt-injection attempts resisted**
- 100+ commits, with CI on GitHub Actions running Vitest unit, component and integration tests

`Next.js` `TypeScript` `MongoDB Atlas` `Vercel AI SDK` `Gemini` `Auth.js` `Tailwind CSS` `Vitest`

### [Real-Time Collaborative Task Board](https://github.com/balakumaran-ks/Real-Time-Collabrative-Task-Board)

A Trello-style kanban board where one person's change shows up live for everyone on the board, and two people editing the same card don't silently overwrite each other.

- **Frontend done:** drag-and-drop columns and cards, live presence avatars, in-app notifications, owner/admin/member roles, and a conflict banner when an edit loses a race (`409 version_conflict`)
- **Backend in progress:** REST and WebSocket API on PostgreSQL with Redis pub/sub. The frontend runs on a built-in mock backend until it's ready.

`React 19` `TypeScript` `Vite` `dnd-kit` `PostgreSQL` `Redis` `WebSocket`

### System design (implementation in progress)

| Project | What the design covers |
| --- | --- |
| [Background Job Queue / Scheduler](https://github.com/balakumaran-ks/Background-Job-Queue-Scheduler) | A mini-Celery on Redis: delayed and cron jobs, visibility-timeout leases with fencing tokens, retries with exponential backoff, a dead-letter queue, and idempotent at-least-once delivery |
| [Distributed URL Shortener + Analytics](https://github.com/balakumaran-ks/Distributed-URL-Shortener-Analytics) | Range-leased ID generation, cache-aside redirects on Redis, click events streamed through Redis Streams to an analytics worker, and write-time rollups in PostgreSQL |

Each design comes with architecture diagrams, an OpenAPI spec, the data model, and architecture decision records (ADRs).

## Tech stack

**Languages:** Java · TypeScript · JavaScript · Python · SQL<br>
**Frontend:** React · Next.js · Tailwind CSS<br>
**Backend and data:** Node.js · Express · MongoDB (Atlas Vector Search)<br>
**AI:** RAG · embeddings · Vercel AI SDK · Gemini<br>
**Tools:** Git · GitHub Actions · Vercel · Vitest

[![Tech stack](https://skillicons.dev/icons?i=java,ts,js,py,react,nextjs,tailwind,nodejs,express,mongodb,git,githubactions,vercel)](#tech-stack)

## Problem solving

**LeetCode Guardian** with 500+ problems solved in Java. Every accepted solution is pushed automatically to my [Leetcode](https://github.com/balakumaran-ks/Leetcode) repository.

[![LeetCode stats](https://leetcard.jacoblin.cool/balakumaranks?theme=dark&font=Inter&ext=heatmap)](https://leetcode.com/u/balakumaranks)
