# 🧠 DSA Visualizer

> An interactive data structure analyzer and algorithm visualizer — built to sharpen DSA skills and crack top tech interviews.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![Built With](https://img.shields.io/badge/built%20with-React%20%2B%20TypeScript-61DAFB)
![Goal](https://img.shields.io/badge/goal-Microsoft%20SWE-0078D4)

---

## 📌 Overview

**DSA Visualizer** is a web-based tool that lets you explore, simulate, and analyze classic data structures and algorithms in real time. Designed for learners and engineers who want to see the *why* behind the *how*.

Built by **Abhishek Kumar** as a personal project to master DSA concepts and prepare for software engineering interviews at top product companies.

---

## ✨ Features

- 🌳 **Tree Visualizer** — Binary Trees, AVL Trees, BSTs with step-by-step traversal
- 🔗 **Linked List Explorer** — Singly, doubly, and circular lists with pointer animations
- 📊 **Sorting Algorithms** — Bubble, Merge, Quick, Heap sort with live comparisons
- 🗺️ **Graph Algorithms** — BFS, DFS, Dijkstra's, and A* on custom graphs
- 📦 **Stack & Queue** — Push/pop/enqueue/dequeue with memory visualization
- 📈 **Complexity Analyzer** — Live Big-O estimation as you build inputs
- 🔁 **Step-Through Mode** — Pause, rewind, and inspect any algorithm state

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React 18 + TypeScript |
| Visualization | D3.js / Canvas API |
| Styling | Tailwind CSS |
| Build Tool | Vite |
| Testing | Vitest + React Testing Library |
| Deployment | GitHub Pages / Vercel |

---

## 🚀 Getting Started

### Prerequisites

- Node.js `v18+`
- npm or pnpm

### Installation

```bash
# Clone the repo
git clone https://github.com/Abhis1905/dsa-visualizer.git
cd dsa-visualizer

# Install dependencies
npm install

# Start the dev server
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 📁 Project Structure

```
dsa-visualizer/
├── public/                  # Static assets
├── src/
│   ├── components/          # Reusable UI components
│   │   ├── Canvas/          # Visualization canvas wrappers
│   │   ├── Controls/        # Playback & input controls
│   │   └── Panels/          # Info & complexity panels
│   ├── algorithms/          # Core algorithm implementations
│   │   ├── sorting/
│   │   ├── graphs/
│   │   └── trees/
│   ├── utils/               # Helpers, animators, generators
│   ├── styles/              # Global CSS / Tailwind config
│   └── main.tsx             # Entry point
├── docs/                    # Architecture & design notes
├── .github/
│   └── workflows/           # CI/CD pipelines
├── package.json
├── tsconfig.json
├── vite.config.ts
└── README.md
```

---

## 🧪 Running Tests

```bash
npm run test         # Run all unit tests
npm run test:watch   # Watch mode
npm run coverage     # Coverage report
```

---

## 📸 Screenshots

> *(Add screenshots or a GIF of the app in action here)*

---

## 🗺️ Roadmap

- [ ] Hash table visualizer
- [ ] Trie and suffix tree support
- [ ] Collaborative mode (multi-user)
- [ ] Export animations as GIF/MP4
- [ ] Embed mode for docs/blogs

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or PR.

1. Fork the repo
2. Create your branch: `git checkout -b feature/my-feature`
3. Commit: `git commit -m 'Add my feature'`
4. Push: `git push origin feature/my-feature`
5. Open a Pull Request

---

## 👨‍💻 Author

**Abhishek Kumar**
- GitHub: [@Abhis1905](https://github.com/Abhis1905)

---

## 📄 License

MIT © [Abhishek Kumar](https://github.com/Abhis1905)

---

> Built with 💙 by [Abhishek](https://www.linkedin.com/in/1905-abhishek/)
