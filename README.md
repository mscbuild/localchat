[repo]: https://github.com/mscbuild/localchat/
[demo]: https://mscbuild.github.io/localchat/
 
 # LocalChat 🌐
 
<a href="https://github.com/mscbuild"><img src="https://img.shields.io/badge/AI-Code%20Assist-EB9FDA"></a>
![](https://komarev.com/ghpvc/?username=mscbuild)
[![Author](https://img.shields.io/badge/Author-Yuri%20Dev-blue.svg)](http://mscbuild.github.io/)
 ![](https://img.shields.io/github/license/mscbuild/localchat) 
 ![](https://img.shields.io/badge/PRs-Welcome-green)
 ![](https://img.shields.io/github/languages/code-size/mscbuild/localchat)
![](https://img.shields.io/badge/code%20style-javascript-green)
![](https://img.shields.io/github/stars/mscbuild)
![](https://img.shields.io/badge/Topic-Github-lighred)
![](https://img.shields.io/website?url=https%3A%2F%2Fgithub.com%2Fmscbuild)


> A private web interface for local LLMs. Works with Ollama, LM Studio, and any OpenAI-compatible API.

##### [ View Live Preview][demo]

 
## ✨ Peculiarities
- 🔒 Complete privacy—everything works locally
- 🎨 Dark/light theme (automatic by system)
- 📝 Markdown and code highlighting support
- 🕒 Chat history (in `localStorage`)
- 🧠 Select a model from the list (Ollama)
- 📱 Responsive design

## 🚀 Installation

### Requirements
- [Node.js 18+](https://nodejs.org/)
- [Ollama](https://ollama.com/) (or another OpenAI-compatible server)

### Local launch
~~~bash
git clone https://github.com/mscbuild/localchat.git
cd localchat
npm install
npm run dev
~~~

Open <a href="http://localhost:5173"></a>

### Docker
~~~bash
docker build -t localchat .
docker run -p 3000:3000 --network host localchat
~~~
## ⚙️ Setting up

**By default, it connects to:**

- API: `http://localhost:11434` (Ollama)
- Model: `llama3`

**You can change it in the interface (drop-down list of models) or through environment variables:**
~~~bash
OLLAMA_BASE_URL=http://192.168.1.100:11434 npm run dev
~~~
## ✅ What's next?

**Run in terminal:**
~~~bash
git init
git add .
git commit -m "feat: initial commit"
git branch -M main
git remote add origin https://github.com/mscbuild/localchat.git
git push -u origin main
~~~
## 📄 MIT License

<!--
keywords: n8n workflows, n8n automation, n8n examples, n8n templates, no-code automation, telegram bot workflows, openai n8n, webhook automation, best proyect, creative repo, awesome, star repo, mscbuild, YuriDev
-->
