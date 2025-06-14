## 项目概述

[![English Docs](https://img.shields.io/badge/Docs-English-green?style=flat-square)](README.md)

这是一个基于 Flutter 框架，运用 ProxyProvider 进行状态管理的简单购物车项目。

### 技术栈
- **Flutter**：实现跨平台移动应用界面的构建。
- **ProxyProvider**：负责高效管理项目中的状态。

### 核心目的
本项目旨在展示如何巧妙利用 ProxyProvider 实现购物车的状态管理，为开发者提供相关实践参考。

### 功能特性
- **用户登录与购物车区分**：支持用户选择 "Mike" 或 "Alice" 登录。系统可通过唯一标识（用户 ID）关联不同用户与各自的购物车，使得登录不同用户账号时，可往对应的购物车内添加条目，以此区分不同用户的购物车内容。
- **退出登录处理**：在退出登录操作时，系统会正确更新内存中的购物车状态，确保不会出现退出登录后，购物车仍保留原用户数据的情况，保证了用户数据的独立性与安全性。