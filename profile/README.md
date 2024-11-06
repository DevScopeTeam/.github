# DevScope

Dev：代表“Developer”，指代开发者。

Scope：意指应用的核心功能——全面、深入地分析和评估开发者的技术能力、活跃度以及协作网络。

## 前言

DevScope 是一款基于 GitHub 开源数据的开发者评估平台，旨在对开发者的技能、贡献和协作网络进行深入评估。通过 TalentRank 指标对开发者进行排名，DevScope 提供开发者技术影响力、推测地理位置和主要领域的深入洞察。支持按领域进行搜索，并对推测数据提供置信度评分，DevScope 为招聘人员、项目负责人及技术社区提供数据驱动的决策支持，帮助识别特定技术领域的优秀人才并促进协作。

## 立即体验

[https://devscope.search.ren](https://devscope.search.ren)

## 视频演示

[->点击这里<-](https://www.bilibili.com/video/)

## 技术栈

为了实现这些功能，我们采用了以下技术栈：

- 前端：我们使用 Vue3.js + TypeScript 进行前端开发，以构建出色的用户界面和用户体验。

- 中间件：我们选择了 Golang 作为后端开发语言，结合 Fiber Web Framework 来构建强大而高效的后端服务，以支持平台的数据管理。同时，整体采用云原生微服务架构，提高系统的可维护性，提供了快速响应和可扩展性，满足用户的需求并确保平台的可靠性。

- 数据库：我们使用 MySQL 作为主要的数据库，以存储用户的数据。

## 架构图

![架构图]([https://bucket.devscope.doyi.online/imgs/platform.png](https://devscope.search.ren/imgs/platform.png))

## 仓库

整个项目的仓库分为两个部分：

[DevScope](https://github.com/DevScopeTeam/DevScope): 项目的前端部分，使用 Vue3.js + TypeScript 开发。

[DevScope-Middleware](https://github.com/DevScopeTeam/DevScope-Middleware): 项目的后端部分，使用 Golang + Go Fiber 开发，承载DevScope所有服务接口的实现，同时与Github的API进行对接。

## 团队分工

- [东南dnf（zjy2414）](https://github.com/zjy2414)

  - 负责中间件的开发，包括服务接口的实现和优化。
  - 负责前端开发，包括接口统一请求体封装和性能优化。

- [Yiqian Zhang（morri3）](https://github.com/morri3)
  
  - 负责前端开发，包括整体设计和用户体验优化。
  - 负责协调前后端开发，确保项目按时交付和质量标准。
