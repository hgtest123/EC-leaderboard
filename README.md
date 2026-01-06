# 🏆 Embodied AI Leaderboard (Powered by RC)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Data Update](https://img.shields.io/badge/Data-Updated_Weekly-blue)](https://github.com/your-org/leaderboard)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

> **全球首个基于真实物理环境数据（Real-World Data）的具身智能模型排行榜。**
> 
> 这里的每一个分数，都来自 RC 平台上的真实机器人运行数据，而非单纯的仿真模拟。我们致力于连接算法与物理世界，帮助开发者找到最适合真实场景的具身大模型。

---

## 📊 Leaderboard (Top Tier)

*最后更新时间: 2026-01-06 | [查看完整榜单及详细数据 >>](./FULL_LEADERBOARD.md)*

| Rank | Model Name | Backbone | Body (本体) | Success Rate (SR) | Tasks Completed | License |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 🥇 1 | **Galbot-7B-Plus** | Llama-3 | Unitree H1 | **88.5%** | 1,240 | Apache 2.0 |
| 🥈 2 | RT-X-Open | ViT-L | Fourier GR-1 | 82.1% | 980 | MIT |
| 🥉 3 | Octo-Base | Transformer | WidowX | 79.4% | 1,500 | MIT |
| 4 | RC-Internal-V2 | Proprietary | Agile X | 76.2% | 3,000 | Closed |
| 5 | ... | ... | ... | ... | ... | ... |

💡 **指标说明：**
* **SR (Success Rate):** 在 RC 平台上执行标准任务集（抓取、移动、规划等）的端到端成功率。
* **Body:** 该模型主要评测的机器人本体硬件。

---

## 🗳️ Community & Requests (你以此为荣，也由你决定)

我们是一个社区驱动的项目。你的反馈决定了我们下一个评测什么模型，以及榜单的进化方向。

### 🔥 **[点击这里投票 / 提名新模型 (Vote for Models)](https://github.com/your-org/leaderboard/issues)**

请通过 **GitHub Issues** 参与互动：

* **[Request Model Evaluation]**: 发现了一个很酷的新开源模型？提交 Issue 告诉我们要测哪个！（点赞数最高的模型我们将优先在 RC 平台上进行实机部署评测）。
* **[Feature Request]**: 想要看新的评测维度（如：推理延时、显存占用、泛化能力）？
* **[Feedback]**: 觉得目前的评分标准有问题？欢迎并在 Issue 中由社区公开讨论。

---

## 🛠️ How We Eval (评测方法论)

为了保证榜单的公信力，我们采用 RC 平台标准化的评测流：

1.  **Model Integration**: 将开源模型接入 RC 具身智能操作系统。
2.  **Sim-to-Real Check**: 进行基础的仿真环境对齐。
3.  **Real-World Testing**: **这是我们的核心**。我们在标准化的物理实验室中，使用真实的机器人本体（如 Unitree, Fourier, Agile X 等）进行不少于 50 次的任务尝试。
4.  **Scoring**: 基于任务完成度、耗时、平稳度进行综合打分。

*想了解详细的评测 Case 和任务定义？请查看 [Doxbotic 文档](https://doxbotic.com/eval-standards).*

---

## 🤝 Ecosystem & Partners

我们致力于构建开放的具身智能生态。

### 🚀 成为合作伙伴 (For Enterprise/Labs)
如果您是机器人硬件厂商或模型研发机构，希望您的产品出现在榜单前列或接入 RC 生态：
* **提交评测**: [点击查看提交指南](./SUBMISSION.md)
* **商务合作**: 请联系 partnership@rc-platform.com

### 📚 相关资源
* **[Doxbotic]**: 我们的核心文档库与知识库。
* **[RC Platform SDK]**: 快速将你的模型部署到真实机器人上。

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=your-org/leaderboard&type=Date)](https://star-history.com/#your-org/leaderboard&Date)

---

**Disclaimer**: 
This leaderboard is based on data collected via the RC Platform. While we strive for objectivity, real-world performance varies based on hardware condition, lighting, and other factors.
