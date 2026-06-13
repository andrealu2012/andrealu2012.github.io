---
layout: project
title: "FUROBOT"
date: 2026-06-14
summary: "面向机器人与参数化设计流程的个人工具与实验记录。"
cover: "/assets/images/furobot/background.png"
tags: ["Robotics", "Grasshopper", "Hardware", "Tooling"]
gallery:
  - image: "/assets/images/furobot/board.jpg"
    caption: "控制板与硬件原型"
  - image: "/assets/images/furobot/grasshopper-tools.png"
    caption: "Grasshopper 工具与组件"
  - image: "/assets/images/furobot/robot-node.png"
    caption: "机器人路径与节点编辑"
  - image: "/assets/images/furobot/grasshopper-udp.png"
    caption: "UDP 通讯和机器人控制实验"
---

FUROBOT 是我围绕机器人、参数化设计和数字制造做的一组工具实验。它不只是一个单独的软件界面，而是一段把 Grasshopper 里的几何逻辑、机器人运动、通讯控制和硬件反馈连接起来的过程。

我希望这些工具能降低机器人实验的门槛：把复杂的路径、姿态、外部轴和通讯命令拆成更直观的组件，让设计和控制之间的距离短一点。

## 我在这个作品里关注的东西

- 在 Grasshopper 中组织机器人运动和路径生成逻辑。
- 将控制命令、UDP 通讯和机器人状态放进可视化流程。
- 结合硬件板卡、传感器和移动平台做实验。
- 让工具既能用于教学演示，也能继续扩展到真实场景。

## 还在继续的问题

这个实验仍然有许多值得整理的部分，例如组件命名、跨机器人品牌的兼容、错误提示、真实设备安全边界，以及更适合长期维护的文档结构。后续我会把这些过程陆续写成笔记。
