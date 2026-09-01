<div align='center'>
    <img src="./images/header.svg" alt="alt text" width="100%">
    <h1>💻 handy-ollama 🦙</h1>
</div>

<div align="center">
  <img src="https://img.shields.io/github/stars/datawhalechina/handy-ollama?style=flat&logo=github" alt="GitHub stars"/>
  <img src="https://img.shields.io/github/forks/datawhalechina/handy-ollama?style=flat&logo=github" alt="GitHub forks"/>
  <img src="https://img.shields.io/github/issues/datawhalechina/handy-ollama?style=flat&logo=github" alt="GitHub issues"/>
  <img src="https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-brighgreen?style=flat&logo=github" alt="GitHub license"/>
  <a href="https://datawhalechina.github.io/handy-ollama/"><img src="https://img.shields.io/badge/Online%20Reading-green?style=flat&logo=gitbook" alt="Online Reading"></a>
</div>

<div align="center">
  <h3>📚 Master Large Model Deployment on CPU from Scratch!</h3>
  <p><em>Learn Ollama Hands-On: Fast Local Deployment of Large Language Models</em></p>
</div>

[简体中文](README.md) | English

🎉 Officially Featured

**Nov. 6, 2025, This project is now featured in the official Ollama repository and is currently the only Tutorial : https://github.com/ollama/ollama#tutorial**

## 🚀 Introduction
A hands-on tutorial series for Ollama, designed to simplify the process of deploying large language models locally. With this guide, you'll be able to manage and run powerful LLMs right on your CPU, making advanced AI accessible without GPU dependencies!

Our comprehensive tutorial covers everything from beginner basics to advanced usage, complete with real-world examples that demonstrate practical applications of LLM deployment. Whether you're a complete novice or an experienced developer, our step-by-step instructions and practical tips will help you master Ollama and start building your own LLM-powered applications.

### Key Topics Covered:
1. **Introduction, Installation & Configuration**: 
   - macOS, Windows, Linux, and Docker deployment guides.
2. **Custom Model Integration**:
   - Import from GGUF, PyTorch, Safetensors, and custom prompt engineering.
3. **Ollama REST API**:
   - Comprehensive usage guide with examples in Python, Java, JavaScript, and C++.
4. **LangChain Integration**:
   - Seamless integration with Python and JavaScript workflows.
5. **Visual Interfaces & Use Cases**:
   - Build interactive chat UIs with FastAPI and WebUI, plus practical RAG and Agent applications.

**We warmly welcome contributions!** Submit issues or pull requests to help improve this project. Let's make advanced AI accessible to everyone!

**Our Mission**: Empower every LLM enthusiast to explore and experiment, regardless of programming background or computational resources. We're breaking down technical barriers to make LLM deployment achievable on personal computers. Join us on this exciting journey!


### Directory Structure:

```
docs ---------------------- Markdown documentation files
notebook ------------------ Notebook source code and Python/Java/JavaScript examples
images -------------------- Image assets
```

📖 **Read Online**: https://datawhalechina.github.io/handy-ollama/  


## 💡 Motivation
The rapid growth of open-source LLMs has democratized AI, but many require GPU resources for deployment. Our goal is to make LLM technology accessible to everyone—regardless of hardware limitations—using Ollama, an open-source tool that enables CPU-based deployment of powerful language models.

This tutorial series empowers learners, hobbyists, and developers to deploy and experiment with LLMs locally, fostering innovation across industries.


## 🎯 Target Audience
- **Resource-Constrained Users**: Run LLMs locally without GPU dependencies.
- **Developers**: Build and test LLM-powered applications on consumer hardware.
- **AI Enthusiasts**: Experiment with state-of-the-art models without cloud costs.
- **Privacy-Conscious Users**: Keep sensitive data and model operations local.


## ✨ Highlights
While many LLM tutorials rely on GPU acceleration, this project focuses exclusively on **CPU-based deployment**, making advanced AI accessible to anyone with a modern computer. Through hands-on examples and clear explanations, we bridge the gap between theory and practice.


## 📖 Roadmap
### Table of Contents (Work in Progress)
- [x] 1 [Ollama Introduction](docs/C1/1.%20Ollama%20介绍.md) @[Youdon](https://github.com/AXYZdong)
- [x] 2 Ollama Installation & Configuration 
  - [x] [macOS](docs/C2/1.%20Ollama%20在%20macOS%20下的安装与配置.md) @[天奥](https://github.com/lta155)
  - [x] [Windows](docs/C2/2.%20Ollama%20在%20Windows%20下的安装与配置.md) @[Yuki](https://github.com/fuyueagain)
  - [x] [Linux](docs/C2/3.%20Ollama%20在%20Linux%20下的安装与配置.md) @[Yuki](https://github.com/fuyueagain)
  - [x] [Docker](docs/C2/4.%20Ollama%20在%20Docker%20下的安装与配置.md) @[Yuki](https://github.com/fuyueagain)
- [x] 3 Custom Ollama Usage
  - [x] [Custom Model Import](docs/C3/1.%20自定义导入模型.md) @[杨卓](https://github.com/little1d)
  - [x] [Custom Model Storage](docs/C3/2.%20自定义模型存储位置.md) @[Yuki](https://github.com/fuyueagain) @[林通](https://github.com/kjlintong) @[天奥](https://github.com/lta155)
  - [x] [GPU Configuration](docs/C3/3.%20自定义在%20GPU%20中运行.md) @[Youdon](https://github.com/AXYZdong)
- [x] 4 Ollama REST API
  - [x] [API Guide](docs/C4/1.%20Ollama%20API%20使用指南.md) @[林通](https://github.com/kjlintong) @[春阳](https://github.com/Springff)
  - [x] [Python Integration](docs/C4/2.%20在%20Python%20中使用%20Ollama%20API.md) @[春阳](https://github.com/Springff)
  - [x] [Java Integration](docs/C4/3.%20在%20Java%20中使用%20Ollama%20API.md) @[林通](https://github.com/kjlintong)
  - [x] [JavaScript Integration](docs/C4/4.%20在%20JavaScript%20中使用%20Ollama%20API.md) @[春阳](https://github.com/Springff)
  - [x] [C++ Integration](docs/C4/5.%20在%20C++%20中使用%20Ollama%20API.md) @[林通](https://github.com/kjlintong)
  - [x] [Golang Integration](docs/C4/6.%20在%20Golang%20中使用%20Ollama%20API.md) @[tomowang](https://github.com/tomowang)
  - [ ] C# Integration (To be updated)
  - [ ] Rust Integration (To be updated)
  - [ ] Ruby Integration (To be updated)
  - [ ] R Integration (To be updated)
- [x] 5 Ollama with LangChain
    - [x] [Python Integration](docs/C5/1.%20Ollama%20在%20LangChain%20中的使用%20-%20Python%20集成.md) @[鑫民](https://github.com/fancyboi999)
    - [x] [JavaScript Integration](docs/C5/2.%20Ollama%20在%20LangChain%20中的使用%20-%20JavaScript%20集成.md) @[鑫民](https://github.com/fancyboi999)
- [x] 6 Ollama Visual Interfaces
    - [x] [FastAPI-based Chat UI](docs/C6/1.%20使用%20FastAPI%20部署%20Ollama%20可视化对话界面.md) @[Youdon](https://github.com/AXYZdong)
    - [x] [WebUI-based Chat UI](docs/C6/2.%20使用%20WebUI%20部署%20Ollama%20可视化对话界面.md) @[Youdon](https://github.com/AXYZdong)
- [ ] 7 Use Cases
    - [x] [Local AI Copilot](docs/C7/1.%20搭建本地的%20AI%20Copilot%20编程助手.md) @[越](https://github.com/rainsubtime)
    - [x] [Dify Integration](docs/C7/2.%20Dify%20接入%20Ollama%20部署的本地模型.md) @[春阳](https://github.com/Springff)
    - [x] [LangChain RAG App](docs/C7/3.%20使用%20LangChain%20搭建本地%20RAG%20应用.md) @[舒凡](https://github.com/Tsumugii24)
    - [x] [LlamaIndex RAG App](docs/C7/4.%20使用%20LlamaIndex%20搭建本地%20RAG%20应用.md) @[Youdon](https://github.com/AXYZdong)
    - [x] [LangChain Agent](docs/C7/5.%20使用%20LangChain%20实现本地%20Agent.md) @[Youdon](https://github.com/AXYZdong)
    - [x] [LlamaIndex Agent](docs/C7/6.%20使用%20LlamaIndex%20实现本地%20Agent.md) @[Youdon](https://github.com/AXYZdong)
    - [x] [DeepSeek R1 RAG App](docs/C7/7.%20使用%20DeepSeek%20R1%20和%20Ollama%20实现本地%20RAG%20应用.md) @[Youdon](https://github.com/AXYZdong)
    - [ ] English translations for chapters 7.8 and 7.9 (available in the Chinese navigation)
    - [ ] More to come...


**Note**: We welcome contributions to complete the pending sections! Submit issues or pull requests to help expand this project.

**Interested in becoming a maintainer?** Contact us to join our core team!


## 🙏 Acknowledgments

Official Ollama Repository: https://github.com/ollama/ollama  

Special thanks to our contributors!

<a href="https://github.com/AXYZdong/handy-ollama/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=AXYZdong/handy-ollama" />
</a>

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=datawhalechina/handy-ollama&type=Date)](https://star-history.com/#datawhalechina/handy-ollama&Date)

## LICENSE

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://img.shields.io/badge/license-CC%20BY--NC--SA%204.0-lightgrey" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
