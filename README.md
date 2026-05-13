# 🚀 Open WebUI Docker Setup

<div align="center">

![Open WebUI](https://img.shields.io/badge/Open%20WebUI-Enabled-blue?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AI](https://img.shields.io/badge/AI-Powered-FF6B6B?style=for-the-badge)

**Your personal AI chat interface - All models, One unified experience** ✨

</div>

---

## 📖 What is This?

This project provides a simple **Docker Compose** setup to run [Open WebUI](https://github.com/open-webui/open-webui) - a powerful, self-hosted platform that lets you chat with any LLM (Large Language Model) through a beautiful, unified interface.

Think of it as your personal ChatGPT interface, but you're in control! 🎮

## Important!!

Shortly will be updated to deploy in a Cloudfoundry environment especially on BTP

---

## ✨ Features

- 🤖 **Connect to any LLM** - OpenAI, Anthropic, Local models, and more
- 🎨 **Beautiful UI** - Clean, modern chat interface
- 🔒 **Self-hosted** - Your data stays on your machine
- 🚀 **Easy deployment** - Just one Docker Compose command
- 💬 **Unified experience** - Switch between models seamlessly

---

## 🛠️ Prerequisites

Before you begin, make sure you have:

- ✅ [Docker](https://docs.docker.com/get-docker/) installed
- ✅ [Docker Compose](https://docs.docker.com/compose/install/) installed

---

## 🚀 Quick Start

Getting started is super easy! Just follow these steps:

### 1️⃣ Clone this repository

```bash
git clone https://github.com/matepca55/Open-WebUI
cd Open-WebUI
```

### 2️⃣ Launch Open WebUI

```bash
docker-compose up -d
```

### 3️⃣ Access the interface

Open your browser and navigate to:

```
http://localhost:3000
```

🎉 **That's it!** You're ready to chat with your favorite LLMs!

---

## 🎯 Usage

1. **First time setup**: Create your account on the web interface
2. **Connect your models**: Go to settings and add your API keys or local model endpoints
3. **Start chatting**: Select a model and start your conversation!

---

## 🛑 Stopping the Service

To stop Open WebUI:

```bash
docker-compose down
```

To stop and remove all data:

```bash
docker-compose down -v
```

---

## 🔧 Configuration

You can customize your Open WebUI instance by editing the `docker-compose.yml` file. Common configurations include:

- 🔌 **Port changes**: Modify the port mapping
- 💾 **Volume paths**: Change where data is stored
- 🌐 **Environment variables**: Add API keys, custom settings, etc.

---

## 📚 Supported Models

Open WebUI supports a wide range of LLM providers:

| Provider | Type |
|----------|------|
| 🤖 OpenAI | API |
| 🧠 Anthropic (Claude) | API |
| 🦙 Ollama | Local |
| 🤗 HuggingFace | API/Local |
| 🌟 Google (Gemini) | API |
| And many more! | - |

---

## 🐛 Troubleshooting

**Container won't start?**
```bash
docker-compose logs
```

**Port already in use?**
- Edit the `docker-compose.yml` and change the port mapping

**Need to reset everything?**
```bash
docker-compose down -v
docker-compose up -d
```

---

## 🤝 Contributing

Found a bug or have a suggestion? Feel free to:

- 🐛 Open an issue
- 🔧 Submit a pull request
- ⭐ Star this repository

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🔗 Useful Links

- 📖 [Open WebUI Documentation](https://docs.openwebui.com/)
- 💬 [Open WebUI GitHub](https://github.com/open-webui/open-webui)
- 🐳 [Docker Documentation](https://docs.docker.com/)

---

### Made with 💜 and 🎶 

**If this project helped you, consider giving it a ⭐!**

---
