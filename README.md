<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:0ea5e9&height=180&section=header&text=http-abort-playground&fontColor=ffffff&fontSize=38)

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1000&color=38BDF8&center=true&vCenter=true&width=720&lines=Understand%20request%20cancellation%20without%20a%20live%20API" alt="Typing title" />

[![License](https://img.shields.io/github/license/CyberLoop-dev/http-abort-playground)](LICENSE) [![Language](https://img.shields.io/github/languages/top/CyberLoop-dev/http-abort-playground)](https://github.com/CyberLoop-dev/http-abort-playground) [![Stars](https://img.shields.io/github/stars/CyberLoop-dev/http-abort-playground?style=social)](https://github.com/CyberLoop-dev/http-abort-playground/stargazers) [![Last commit](https://img.shields.io/github/last-commit/CyberLoop-dev/http-abort-playground)](https://github.com/CyberLoop-dev/http-abort-playground/commits/main)

<img src="assets/mark.svg" width="112" alt="http-abort-playground illustration" />

</div>

## 🧭 Overview

Explore request cancellation with simulated network work. Start a request, abort it, or let it complete to see how AbortController signals and timeout handling affect asynchronous operations. No external endpoint is contacted.

## ✨ Features

- ✨ Start simulated requests with adjustable latency.
- ✨ Abort an in-flight request with AbortController.
- ✨ Compare completed, aborted, and timed-out outcomes.
- ✨ Inspect a chronological request lifecycle log.

## 🎬 Demo

Run the app locally and use the controls to explore the scenarios. No hosted demo is claimed; the app runs on your machine and makes no external API requests.

## 🚀 Quick Start

```bash
npm start
```

Open **http://127.0.0.1:4173**.

## 🧰 Tech Stack

- 🟦 Node.js built-in HTTP server
- 🌐 Browser JavaScript, HTML, and CSS
- 📦 No third-party runtime dependencies

## 🗂️ Folder Structure

```text
http-abort-playground/
├── assets/mark.svg
├── public/
│   ├── app.js
│   ├── index.html
│   └── styles.css
├── .gitignore
├── LICENSE
├── package.json
├── README.md
└── server.js
```

## 🛣️ Roadmap

- [ ] Add multiple concurrent request lanes.
- [ ] Add an AbortSignal.any demonstration.

## 🤝 Contributing

Issues and pull requests are welcome. Keep changes focused, document behavior, and avoid unnecessary dependencies.

## 📄 License

Released under the [MIT License](LICENSE).

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:0ea5e9&height=100&section=footer)

</div>
