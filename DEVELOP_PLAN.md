# 开发规划

-    核心功能：5-6人日
-    练习内容：3-4人日
-    AI集成：2-3人日
-    测试与文档：2人日
-    总计：12-15人日 (3人×5天可完成核心功能)


## 第一阶段--项目骨架和架构核心开发

- 配置poetry
- 搭建基本cli框架(至少是函数框架)
- git操作封装(基于dulwich/GitPython双后端)
- 设计练习内容和toml元数据规范以及commit-msg规范

## 第二阶段--完成核心模块并交付MVP

- 内置在gitlings命令行中的的vim模块
- 提交信息交互
- 用户配置管理
- 彩色以及unicode输出和格式化以及练习进度方案
- 验证系统
- rich终端ui实现
- 留出ai引导功能接口

## 第三阶段--AI引导功能

- 提示缓存系统
- 历史记录功能
- 个性化即时提示
- LLM API集成
- 上下文感知实现
- 提示分级系统和静态提示

## 4--测试

## 5--打包和交付准备

