![动手学Ollama](images/header.svg)

# 🦙💻 handy-ollama

Learning to deploy Ollama with hands-on practice, making the deployment of large language models accessible to everyone!

## 项目简介

动手学Ollama，实现大模型本地化部署，快速在本地管理以及运行大模型，让CPU也可以玩转大模型部署！

## 立项理由

随着大模型的飞速发展，市面上出现了越来越多的开源大模型，但是许多模型的部署需要利用GPU资源，如何让大模型时代的红利普惠到每一个人，让每一个人都可以部署属于自己的大模型。Ollama是一个开源的大语言部署服务工具，只需CPU即可部署大模型。我们希望通过动手学Ollama这一开源教程，帮助学习者快速上手Ollama，让每一位大模型爱好者、学习者以及开发者都能在本地部署自己的大模型，进而开发一些大模型应用，让大模型赋能千行百业！

## 项目受众

- 希望不受GPU资源限制，在本地运行大模型；
- 希望在消费级硬件上进行大模型有效的推理；
- 希望在本地部署大模型，开发大模型应用；
- 希望在本地管理大模型，让本地模型安全可靠。

## 项目亮点

本项目旨在使用CPU部署本地大模型，虽然目前已经有很多LLM相关的教程，但是这些教程中模型基本上都需要GPU资源，这对于很多资源受限的学习者不是很友好。因此，本项目通过动手学Ollama，帮助学习者快速上手本地CPU部署大模型。

## 项目规划

### 目录（持续更新中...）

- [X] 1 [Ollama 介绍](docs/C1/1.%20Ollama介绍.md) @[友东](https://github.com/AXYZdong)
- [ ] 2 Ollama 安装与配置
  - [ ] macOS
  - [X] [Windows](docs\C2\2.%20Ollama在Windows下的安装与配置.md) @[Yuki](https://github.com/fuyueagain)
  - [X] [Linux](docs\C2\3.%20Ollama在Linux下的安装与配置.md) @[Yuki](https://github.com/fuyueagain)
  - [X] [Docker](docs\C2\4.%20Ollama在Docker下的安装与配置.md) @[Yuki](https://github.com/fuyueagain)
- [X] 3 [自定义导入模型](docs/C3/1.%20自定义导入模型.md) @[杨卓](https://github.com/little1d)
- [ ] 4 Ollama REST API @[]()
  - [ ] Ollama API 使用指南
  - [ ] 在 Python 中使用 Ollama API
  - [ ] 在 Java 中使用 Ollama API
- [X] 5 Ollama 在 LangChain 中的使用
  - [X] [在 Python 中的集成](docs/C5/1.%20Ollama在LangChain中的使用%20-%20Python集成.md) @[鑫民](https://github.com/fancyboi999)
  - [X] [在 JavaScript 中的集成](docs/C5/2.%20Ollama在LangChain中的使用%20-%20JavaScript集成.md) @[鑫民](https://github.com/fancyboi999)
- [X] 6 Ollama 可视化界面部署
  - [X] [使用 FastAPI 部署 Ollama 可视化对话界面](docs/C6/1.%20使用%20FastAPI%20部署%20Ollama%20可视化对话界面.md) @[友东](https://github.com/AXYZdong)
  - [X] [使用 WebUI 部署 Ollama 可视化对话界面](docs/C6/2.%20使用%20WebUI%20部署%20Ollama%20可视化对话界面.md) @[友东](https://github.com/AXYZdong)
- [ ] 7 应用案例
  - [ ] 搭建本地的 AI Copilot 编程助手
  - [ ] Dify 接入 Ollama 部署的本地模型
  - [X] 使用 LangChain 搭建本地 RAG 应用 @[舒凡](https://github.com/Tsumugii24)

## 致谢特别感谢以下为教程做出贡献的同学！

<a href="https://github.com/AXYZdong/handy-ollama/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=AXYZdong/handy-ollama" />
</a>
