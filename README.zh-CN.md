# HuggingFace_Projects · 深度强化学习项目

简体中文

本仓库收录了基于 Hugging Face 课程完成的项目，目前包含一个**深度强化学习智能体**。

## 内容

| 文件 | 说明 |
| --- | --- |
| `Deep_Reinforcement_Learning_Lunar_Lander.ipynb` | 训练智能体在 Gymnasium 的 **LunarLander（月球着陆器）** 环境中平稳着陆 |

## 项目简介

在 LunarLander 环境中，智能体需要控制着陆器的主引擎和侧向引擎，使其安全降落在两面旗帜之间的着陆点。Notebook 使用 Stable-Baselines3 中的 **PPO（近端策略优化）** 算法在 `LunarLander-v2` 环境中训练智能体，评估其平均奖励，并可将训练好的模型上传到 Hugging Face Hub 分享。

## 使用方法

推荐在 Google Colab 中打开 Notebook（训练需要一定算力），按顺序运行各单元格即可。
