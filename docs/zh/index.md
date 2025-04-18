# TorchOptLib 文档

欢迎使用 TorchOptLib 文档！TorchOptLib 是一个基于 PyTorch 的模块化优化库，用于实现和实验各种优化算法。

## 关于 TorchOptLib

TorchOptLib 是一个轻量级、可扩展的框架，提供以下功能：

- 用于测试优化算法的经典基准函数集合
- 易于扩展的基类，方便创建自定义优化算法
- 通过 PyTorch 的设备管理支持 GPU 加速
- 内置的优化过程可视化和跟踪功能

## 目录

- [安装指南](installation.md)
- [快速开始](quick_start.md)
- [基准测试函数](benchmarks.md)
- [优化算法](algorithms.md)
- [扩展 TorchOptLib](extending.md)

## 开发动机

作为一名学习优化算法的普通大学生，我发现现有的优化和基准测试库往往支离破碎、缺乏兼容性，难以有效比较不同的算法。此外，这些算法的并行计算也不够直观。

在学习过程中，我希望创建一个项目，既能帮助我更好地理解这些算法，又能提供一个实用的实验工具。通过利用 PyTorch 强大的张量操作和并行计算能力，我创建了这个统一框架来辅助我的学习过程。

TorchOptLib 的目标是：

- 提供模块化设计，包含能够轻松集成各种测试函数和优化算法的基类
- 启用无缝的 GPU 加速以加快计算速度
- 简化比较和实验不同优化技术的过程
- 作为对优化算法感兴趣的学生的学习工具
