# CS Learning

这是一个长期、系统化学习计算机科学与人工智能前沿方向的项目。它将围绕计算机视觉、强化学习、具身智能与机器人、扩散模型、VLA、World Model、视频生成等主题建立课程文件夹，持续沉淀学习笔记、代码实现、论文复现、实验记录与阶段性总结。

项目目标不是简单收集资料，而是把学习过程组织成一个可追踪、可复盘、可扩展的知识系统。随着课程、实验和项目逐步推进，这里会成长为一个具有长期影响力的公开学习工程。

## 项目愿景

- 系统学习 AI 与机器人相关核心课程，建立扎实的理论与工程基础。
- 将每门课程的学习材料、笔记、代码、实验和复盘集中管理。
- 通过持续更新日志记录学习路径、关键突破和阶段性成果。
- 最终形成一个高质量、可参考、可复用的 CS/AI 学习仓库。

## 学习方向

计划覆盖的核心方向包括：

- Computer Vision：图像理解、检测、分割、3D 视觉、多模态视觉。
- Reinforcement Learning：MDP、动态规划、策略梯度、Actor-Critic、离线强化学习。
- Embodied AI & Robotics：机器人感知、控制、规划、仿真、现实部署。
- Diffusion Models：生成建模、条件生成、图像与视频扩散模型。
- VLA：视觉-语言-动作模型、机器人基础模型与具身任务执行。
- World Models：环境建模、预测学习、智能体内部表征。
- Video Generation：视频生成、时序一致性、可控生成与多模态生成。

## 推荐目录结构

后续每个课程或专题可以独立建一个文件夹，并保持相似结构：

```text
CS Learning/
├── README.md
├── CHANGELOG.md
├── computer-vision/
│   ├── README.md
│   ├── notes/
│   ├── assignments/
│   ├── papers/
│   └── projects/
├── reinforcement-learning/
│   ├── README.md
│   ├── notes/
│   ├── assignments/
│   ├── papers/
│   └── projects/
├── embodied-ai-robotics/
├── diffusion-models/
├── vla/
├── world-models/
└── video-generation/
```

## 单门课程记录规范

每个课程文件夹建议包含：

- `README.md`：课程目标、资源链接、学习计划和完成状态。
- `notes/`：按章节或周次整理的学习笔记。
- `assignments/`：课程作业、实现代码和实验说明。
- `papers/`：论文阅读笔记与关键引用。
- `projects/`：阶段性项目、复现结果和演示材料。

## 更新日志

项目进展记录在 [CHANGELOG.md](./CHANGELOG.md)。每次新增课程、完成阶段学习、复现实验、整理重要笔记或调整项目结构时，都应记录一条清晰的更新。

## Git 工作流

建议使用简洁稳定的工作流：

```bash
git status
git add README.md CHANGELOG.md .gitignore
git commit -m "Initialize CS learning project"
git remote add origin <github-repository-url>
git push -u origin main
```

## 当前状态

- 项目初始化：已创建根目录说明、更新日志和基础忽略规则。
- 课程目录：待逐步创建。
- GitHub 仓库：待连接远程仓库。

