# AI Code Reviewer

An AI-powered tool that reviews source code and returns structured, actionable feedback on bugs, readability, performance and best practices.

![Status](https://img.shields.io/badge/status-in%20development-orange)
![License](https://img.shields.io/badge/license-MIT-blue)

> **Demo:** `[add live link or screenshot here]`

---

## Overview

AI Code Reviewer lets a developer submit a code snippet and get an automated review, so common issues are caught before a human reviewer or a pull request is involved. The project is split into a **Frontend** (user interface) and a **BackEnd** (review logic and AI integration).

## Features

- Submit code through a web interface and receive an AI-generated review
- Feedback on bugs, code quality, readability and performance
- Suggested fixes and improvements
- `[Multi-language support: list languages]`
- `[Add or remove features to match what is actually implemented]`

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | `[e.g. React / HTML-CSS-JS]` |
| Backend | `[e.g. Node.js + Express / Python + Flask]` |
| AI / LLM | `[e.g. Gemini API / OpenAI API / Claude API]` |

## Project Structure

```
AI-CODE-REVIEWER/
├── BackEnd/      # Server, API routes and AI review logic
├── Frontend/     # User interface
└── .gitignore
```

## Getting Started

### Prerequisites

- `[Node.js 18+ / Python 3.10+]`
- An API key for your AI provider
- Git

### 1. Clone the repository

```bash
git clone https://github.com/sriyansh-dev/AI-CODE-REVIEWER.git
cd AI-CODE-REVIEWER
```

### 2. Set up the backend

```bash
cd BackEnd
# install dependencies, e.g. npm install  OR  pip install -r requirements.txt
```

Create a `.env` file in `BackEnd/`:

```env
API_KEY=your_api_key_here
PORT=3000
```

Start the server:

```bash
# e.g. npm start  OR  python app.py
```

### 3. Set up the frontend

```bash
cd ../Frontend
# install dependencies and start, e.g. npm install && npm run dev
```

Open the local URL printed in the terminal.

## Usage

1. Open the app in your browser.
2. Paste your code into the editor.
3. Click **Review**.
4. Read the feedback and apply the suggested changes.

## Environment Variables

| Variable | Description |
|---|---|
| `API_KEY` | API key for the AI provider |
| `PORT` | Port the backend runs on |

Never commit your `.env` file. It is already covered by `.gitignore`.

## Roadmap

- [ ] GitHub pull request integration
- [ ] Review history
- [ ] Support for more languages
- [ ] Severity levels for each finding

## Contributing

Contributions are welcome.

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push the branch: `git push origin feature/your-feature`
5. Open a pull request

## License

Distributed under the MIT License. Add a `LICENSE` file to the repo root to match.

## Author

**Sriyansh Raj**
GitHub: [@sriyansh-dev](https://github.com/sriyansh-dev)
