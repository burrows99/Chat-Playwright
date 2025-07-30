<p align="center">
  <a href="https://librechat.ai">
    <img src="client/public/assets/logo.svg" height="256">
  </a>
  <h1 align="center">
    <a href="https://librechat.ai">LibreChat</a>
  </h1>
</p>

<p align="center">
  <a href="https://discord.librechat.ai"> 
    <img
      src="https://img.shields.io/discord/1086345563026489514?label=&logo=discord&style=for-the-badge&logoWidth=20&logoColor=white&labelColor=000000&color=blueviolet">
  </a>
  <a href="https://www.youtube.com/@LibreChat"> 
    <img
      src="https://img.shields.io/badge/YOUTUBE-red.svg?style=for-the-badge&logo=youtube&logoColor=white&labelColor=000000&logoWidth=20">
  </a>
  <a href="https://docs.librechat.ai"> 
    <img
      src="https://img.shields.io/badge/DOCS-blue.svg?style=for-the-badge&logo=read-the-docs&logoColor=white&labelColor=000000&logoWidth=20">
  </a>
  <a aria-label="Sponsors" href="https://github.com/sponsors/danny-avila">
    <img
      src="https://img.shields.io/badge/SPONSORS-brightgreen.svg?style=for-the-badge&logo=github-sponsors&logoColor=white&labelColor=000000&logoWidth=20">
  </a>
</p>

<p align="center">
<a href="https://railway.app/template/b5k2mn?referralCode=HI9hWz">
  <img src="https://railway.app/button.svg" alt="Deploy on Railway" height="30">
</a>
<a href="https://zeabur.com/templates/0X2ZY8">
  <img src="https://zeabur.com/button.svg" alt="Deploy on Zeabur" height="30"/>
</a>
<a href="https://template.cloud.sealos.io/deploy?templateName=librechat">
  <img src="https://raw.githubusercontent.com/labring-actions/templates/main/Deploy-on-Sealos.svg" alt="Deploy on Sealos" height="30">
</a>
</p>

<p align="center">
  <a href="https://www.librechat.ai/docs/translation">
    <img 
      src="https://img.shields.io/badge/dynamic/json.svg?style=for-the-badge&color=2096F3&label=locize&query=%24.translatedPercentage&url=https://api.locize.app/badgedata/4cb2598b-ed4d-469c-9b04-2ed531a8cb45&suffix=%+translated" 
      alt="Translation Progress">
  </a>
</p>


# ✨ Features

- 🖥️ **UI & Experience** inspired by ChatGPT with enhanced design and features

- 🤖 **AI Model Selection**:  
  - Anthropic (Claude), AWS Bedrock, OpenAI, Azure OpenAI, Google, Vertex AI, OpenAI Responses API (incl. Azure)
  - [Custom Endpoints](https://www.librechat.ai/docs/quick_start/custom_endpoints): Use any OpenAI-compatible API with LibreChat, no proxy required
  - Compatible with [Local & Remote AI Providers](https://www.librechat.ai/docs/configuration/librechat_yaml/ai_endpoints):
    - Ollama, groq, Cohere, Mistral AI, Apple MLX, koboldcpp, together.ai,
    - OpenRouter, Perplexity, ShuttleAI, Deepseek, Qwen, and more

- 🔧 **[Code Interpreter API](https://www.librechat.ai/docs/features/code_interpreter)**: 
  - Secure, Sandboxed Execution in Python, Node.js (JS/TS), Go, C/C++, Java, PHP, Rust, and Fortran
  - Seamless File Handling: Upload, process, and download files directly
  - No Privacy Concerns: Fully isolated and secure execution

- 🔦 **Agents & Tools Integration**:  
  - **[LibreChat Agents](https://www.librechat.ai/docs/features/agents)**:
    - No-Code Custom Assistants: Build specialized, AI-driven helpers without coding  
    - Flexible & Extensible: Use MCP Servers, tools, file search, code execution, and more  
    - Compatible with Custom Endpoints, OpenAI, Azure, Anthropic, AWS Bedrock, Google, Vertex AI, Responses API, and more
    - [Model Context Protocol (MCP) Support](https://modelcontextprotocol.io/clients#librechat) for Tools

- 🔍 **Web Search**:  
  - Search the internet and retrieve relevant information to enhance your AI context
  - Combines search providers, content scrapers, and result rerankers for optimal results
  - **[Learn More →](https://www.librechat.ai/docs/features/web_search)**

- 🪄 **Generative UI with Code Artifacts**:  
  - [Code Artifacts](https://youtu.be/GfTj7O4gmd0?si=WJbdnemZpJzBrJo3) allow creation of React, HTML, and Mermaid diagrams directly in chat

- 🎨 **Image Generation & Editing**
  - Text-to-image and image-to-image with [GPT-Image-1](https://www.librechat.ai/docs/features/image_gen#1--openai-image-tools-recommended)
  - Text-to-image with [DALL-E (3/2)](https://www.librechat.ai/docs/features/image_gen#2--dalle-legacy), [Stable Diffusion](https://www.librechat.ai/docs/features/image_gen#3--stable-diffusion-local), [Flux](https://www.librechat.ai/docs/features/image_gen#4--flux), or any [MCP server](https://www.librechat.ai/docs/features/image_gen#5--model-context-protocol-mcp)
  - Produce stunning visuals from prompts or refine existing images with a single instruction

- 💾 **Presets & Context Management**:  
  - Create, Save, & Share Custom Presets  
  - Switch between AI Endpoints and Presets mid-chat
  - Edit, Resubmit, and Continue Messages with Conversation branching  
  - [Fork Messages & Conversations](https://www.librechat.ai/docs/features/fork) for Advanced Context control

- 💬 **Multimodal & File Interactions**:  
  - Upload and analyze images with Claude 3, GPT-4.5, GPT-4o, o1, Llama-Vision, and Gemini 📸  
  - Chat with Files using Custom Endpoints, OpenAI, Azure, Anthropic, AWS Bedrock, & Google 🗃️

- 🌎 **Multilingual UI**:  
  - English, 中文, Deutsch, Español, Français, Italiano, Polski, Português Brasileiro
  - Русский, 日本語, Svenska, 한국어, Tiếng Việt, 繁體中文, العربية, Türkçe, Nederlands, עברית

- 🧠 **Reasoning UI**:  
  - Dynamic Reasoning UI for Chain-of-Thought/Reasoning AI models like DeepSeek-R1

- 🎨 **Customizable Interface**:  
  - Customizable Dropdown & Interface that adapts to both power users and newcomers

- 🗣️ **Speech & Audio**:  
  - Chat hands-free with Speech-to-Text and Text-to-Speech  
  - Automatically send and play Audio  
  - Supports OpenAI, Azure OpenAI, and Elevenlabs

- 📥 **Import & Export Conversations**:  
  - Import Conversations from LibreChat, ChatGPT, Chatbot UI  
  - Export conversations as screenshots, markdown, text, json

- 🔍 **Search & Discovery**:  
  - Search all messages/conversations

- 👥 **Multi-User & Secure Access**:
  - Multi-User, Secure Authentication with OAuth2, LDAP, & Email Login Support
  - Built-in Moderation, and Token spend tools

- ⚙️ **Configuration & Deployment**:  
  - Configure Proxy, Reverse Proxy, Docker, & many Deployment options  
  - Use completely local or deploy on the cloud

- 📖 **Open-Source & Community**:  
  - Completely Open-Source & Built in Public  
  - Community-driven development, support, and feedback

[For a thorough review of our features, see our docs here](https://docs.librechat.ai/) 📚

## 🚀 Quick Setup with Ollama & Playwright MCP

This setup includes:
- **Local Ollama AI models** (llama3.2, llama3, phi3, deepseek-r1)
- **Playwright MCP visual browser automation** (22+ browser tools)
- **OpenRouter integration** for additional AI models

### Prerequisites
- Docker and Docker Compose
- Git

### Setup Steps

1. **Clone and Setup**
   ```bash
   git clone https://github.com/danny-avila/LibreChat.git
   cd LibreChat
   cp .env.example .env
   ```

2. **Configure Environment Variables**
   Edit `.env` file and add:
   ```bash
   # Fix Docker warnings
   UID=1000
   GID=1000
   
   # Essential configuration
   HOST=0.0.0.0
   PORT=3080
   MONGO_URI=mongodb://mongodb:27017/LibreChat
   MEILI_HOST=http://meilisearch:7700
   RAG_PORT=8000
   RAG_API_URL=http://rag_api:8000
   
   # Security keys (generate secure values)
   CREDS_KEY=your_secure_creds_key_here
   CREDS_IV=your_secure_creds_iv_here
   JWT_SECRET=your_secure_jwt_secret_here
   JWT_REFRESH_SECRET=your_secure_jwt_refresh_secret_here
   ```

3. **Ollama Setup (Choose One)**

   **Option A: Ollama Inside Docker (Recommended)**
   - Ollama runs in a Docker container
   - Models are downloaded automatically
   - Uses `http://ollama:11434` as base URL
   
   **Option B: Ollama Outside Docker**
   - Install Ollama on your host system
   - Download models manually: `ollama pull llama3.2:latest`
   - Uses `http://host.docker.internal:11434` as base URL
   - Update `librechat.yaml` baseURL accordingly

4. **Start Services**
   ```bash
   docker-compose up -d
   ```

5. **Access LibreChat**
   - Open http://localhost:3080
   - Create an account
   - Select Ollama models or configure OpenRouter

### 🎭 Playwright MCP Visual Browser Automation

The setup includes a Playwright MCP server with 22+ browser automation tools:

**Available Tools:**
- Navigation: `browser_navigate`, `browser_navigate_back`, `browser_navigate_forward`
- Screenshots: `browser_take_screenshot`, `browser_snapshot`
- Interactions: `browser_click`, `browser_type`, `browser_hover`
- Tab Management: `browser_tab_new`, `browser_tab_select`, `browser_tab_close`
- Advanced: `browser_evaluate`, `browser_file_upload`, `browser_wait_for`

**Example Commands:**
```
"Navigate to google.com and take a screenshot"
"Search for 'LibreChat' on Google and click the first result"
"Go to YouTube and search for 'AI tutorials'"
"Take a screenshot of the current page"
```

**Features:**
- ✅ **Visual Browser**: Runs in headed mode (not headless) for automation visualization
- ✅ **Session Persistence**: Browser state is saved between operations
- ✅ **Trace Logging**: Detailed logs for debugging automation
- ✅ **Stable Connection**: Uses streamable-http for reliable MCP communication

### 🔧 Configuration Files

- `librechat.yaml`: Main configuration for AI models and MCP servers
- `docker-compose.yml`: Docker services including Playwright MCP container
- `.env`: Environment variables and security keys

### 📊 Model Support

---

## 🔧 **Custom Fork Configuration**

> **Note**: This section contains custom configurations specific to this fork. When syncing with upstream, these changes will be preserved separately from the main LibreChat documentation.

### **Automatic Ollama Model Download**

**Default Model Configuration:**
- **Default Model**: `llama3.2:1b` (1.3GB) - Optimized for systems with limited memory
- **Auto-download**: Models are automatically downloaded when Docker Compose starts
- **Memory Optimized**: Selected to work with systems having 3-4GB available RAM

**How to Change the Default Model:**

1. **Edit `.env` file** (create from `.env.example` if needed):
   ```bash
   # Change this line to your preferred model
   DEFAULT_OLLAMA_MODEL=llama3.2:1b
   ```

2. **Recommended Models by Memory:**
   - **Low Memory (2-3GB)**: `tinyllama:latest` (~600MB), `qwen2.5:0.5b` (~400MB)
   - **Medium Memory (3-4GB)**: `llama3.2:1b` (1.3GB), `phi3:mini` (~2.2GB)
   - **High Memory (4GB+)**: `llama3.2:latest` (3.4GB), `phi3:latest` (3.8GB)

3. **Restart Docker Compose**:
   ```bash
   docker-compose down
   docker-compose up -d
   ```

**Available Local Ollama Models:**
- `llama3.2:1b` (1.3GB, fast responses, memory efficient) ⭐ **Default**
- `llama3.2:latest` (3.4GB, better quality, requires more memory)
- `tinyllama:latest` (~600MB, very fast, basic capabilities)
- `phi3:mini` (2.2GB, Microsoft model, good balance)
- `qwen2.5:0.5b` (~400MB, very small, quick responses)

**OpenRouter Integration:**
- Access to 100+ AI models
- Requires OpenRouter API key
- Supports latest models from OpenAI, Anthropic, Google, etc.

### 🛠️ Troubleshooting

**MCP Connection Issues:**
- Check `docker-compose logs playwright-mcp` for container status
- Verify `docker-compose logs api` for MCP initialization
- Ensure containers are on the same Docker network

**Ollama Model Issues:**
- **Memory Errors**: If you see "model requires more system memory", change to a smaller model in `.env`:
  ```bash
  DEFAULT_OLLAMA_MODEL=tinyllama:latest  # Use smaller model
  ```
- **Model Not Found**: Check if model downloaded: `docker exec librechat-ollama-1 ollama list`
- **Auto-download Failed**: Check downloader logs: `docker-compose logs ollama-model-downloader`
- **For external Ollama**: Ensure service is running on port 11434
- **For Docker Ollama**: Check container logs and model downloads
- **Verify baseURL**: Ensure `librechat.yaml` baseURL matches your setup:
  - Docker setup: `http://ollama:11434/v1/`
  - External setup: `http://host.docker.internal:11434/v1/`

**Browser Automation Issues:**
- Playwright MCP runs in headed mode for visual feedback
- Check browser logs with `browser_console_messages` tool
- Use `browser_wait_for` for dynamic content loading

## 🪶 All-In-One AI Conversations with LibreChat

LibreChat brings together the future of assistant AIs with the revolutionary technology of OpenAI's ChatGPT. Celebrating the original styling, LibreChat gives you the ability to integrate multiple AI models. It also integrates and enhances original client features such as conversation and message search, prompt templates and plugins.

With LibreChat, you no longer need to opt for ChatGPT Plus and can instead use free or pay-per-call APIs. We welcome contributions, cloning, and forking to enhance the capabilities of this advanced chatbot platform.

[![Watch the video](https://raw.githubusercontent.com/LibreChat-AI/librechat.ai/main/public/images/changelog/v0.7.6.gif)](https://www.youtube.com/watch?v=ilfwGQtJNlI)

Click on the thumbnail to open the video☝️

---

## 🌐 Resources

**GitHub Repo:**
  - **RAG API:** [github.com/danny-avila/rag_api](https://github.com/danny-avila/rag_api)
  - **Website:** [github.com/LibreChat-AI/librechat.ai](https://github.com/LibreChat-AI/librechat.ai)

**Other:**
  - **Website:** [librechat.ai](https://librechat.ai)
  - **Documentation:** [librechat.ai/docs](https://librechat.ai/docs)
  - **Blog:** [librechat.ai/blog](https://librechat.ai/blog)

---

## 📝 Changelog

Keep up with the latest updates by visiting the releases page and notes:
- [Releases](https://github.com/danny-avila/LibreChat/releases)
- [Changelog](https://www.librechat.ai/changelog) 

**⚠️ Please consult the [changelog](https://www.librechat.ai/changelog) for breaking changes before updating.**

---

## ⭐ Star History

<p align="center">
  <a href="https://star-history.com/#danny-avila/LibreChat&Date">
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=danny-avila/LibreChat&type=Date&theme=dark" onerror="this.src='https://api.star-history.com/svg?repos=danny-avila/LibreChat&type=Date'" />
  </a>
</p>
<p align="center">
  <a href="https://trendshift.io/repositories/4685" target="_blank" style="padding: 10px;">
    <img src="https://trendshift.io/api/badge/repositories/4685" alt="danny-avila%2FLibreChat | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/>
  </a>
  <a href="https://runacap.com/ross-index/q1-24/" target="_blank" rel="noopener" style="margin-left: 20px;">
    <img style="width: 260px; height: 56px" src="https://runacap.com/wp-content/uploads/2024/04/ROSS_badge_white_Q1_2024.svg" alt="ROSS Index - Fastest Growing Open-Source Startups in Q1 2024 | Runa Capital" width="260" height="56"/>
  </a>
</p>

---

## ✨ Contributions

Contributions, suggestions, bug reports and fixes are welcome!

For new features, components, or extensions, please open an issue and discuss before sending a PR.

If you'd like to help translate LibreChat into your language, we'd love your contribution! Improving our translations not only makes LibreChat more accessible to users around the world but also enhances the overall user experience. Please check out our [Translation Guide](https://www.librechat.ai/docs/translation).

---

## 💖 This project exists in its current state thanks to all the people who contribute

<a href="https://github.com/danny-avila/LibreChat/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=danny-avila/LibreChat" />
</a>

---

## 🎉 Special Thanks

We thank [Locize](https://locize.com) for their translation management tools that support multiple languages in LibreChat.

<p align="center">
  <a href="https://locize.com" target="_blank" rel="noopener noreferrer">
    <img src="https://github.com/user-attachments/assets/d6b70894-6064-475e-bb65-92a9e23e0077" alt="Locize Logo" height="50">
  </a>
</p>
