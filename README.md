# Chat-Playwright

A chat-driven browser automation tool powered by:

* **LibreChat UI** — clean chat interface with built-in MCP server integration
* **Microsoft Playwright MCP Server** — structured browser automation via HTTP streaming
* **Ollama** — local LLM hosting (default: **llama3.2**, 2B parameters, auto-downloaded)

---

## Features

* **No manual model setup** — automatically pulls the `llama3.2` (2B) model on first run
* **One-command start** — clone & `docker-compose up` to launch everything
* **Accessible locally** — chat interface available at [http://localhost:3080](http://localhost:3080)
* **Real-time automation** — powered by HTTP streaming between LibreChat, Ollama, and Playwright MCP

---

## Quick Start

1. **Clone the repository**

   ```bash
   git clone https://github.com/burrows99/Chat-Playwright.git
   cd Chat-Playwright
   ```

2. **Start with Docker Compose**

   ```bash
   docker-compose up
   ```

3. **Open in browser**

   ```
   http://localhost:3080
   ```

4. **Chat and automate**

   * Describe your task in chat (e.g., “Go to example.com and click the About link”)
   * The LLM + Playwright MCP will execute in the browser context

---

## How It Works

```
[LibreChat UI] ↔ HTTP Stream ↔ [Playwright MCP Server] ↔ Browser
           ↕
     Ollama (llama3.2, 2B params)
```

* LibreChat handles the chat UI and MCP server orchestration.
* Ollama serves the LLM locally (auto-pulls llama3.2 2B).
* Playwright MCP executes tool calls in a live browser session.

---

## Requirements

* **Docker** & **Docker Compose** installed

---

## License

MIT License
