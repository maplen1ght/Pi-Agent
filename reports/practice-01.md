# 实践课 1：Pi Agent 安装与使用

## 一、任务完成情况

| 序号 | 任务 | 完成情况 | 截图 | 对应任务书验收项 |
|---|---|---|---|---|
| 1 | 本地安装并启动 Pi | 完成 | S1 | S1 |
| 2 | 配置模型并完成一次会话 | 完成 | S2 | S2 |
| 3 | 切换模型与模型思考级别 | 完成 | S3.1–S3.4 | S3 |
| 4A | 使用 @ 引用代码文件 | 完成 | S4.1-A、S4.2-A | S4 |
| 4B | 粘贴小图片并测试 | 完成（图片以文件路径传入，PIL 辅助识别） | S4.3-B–S4.5-B | S5 |
| 5 | 安装并试用 Pi 插件 | 完成（pi-web-access） | S5.1、S5.2 | S6 |
| 6 | 让 AI 安装 PPT Skill（选做） | 完成安装、发现与调用 | S6.1–S6.4 | S7、S8 |

### 任务一 本地安装并启动

- 安装方式：官方 `install.ps1` 自托管安装
- 安装位置：`C:\Users\10742\.pi\agent\`
- 版本：1.5.2，底部状态栏显示工作目录 `D:\pi-test`

<img width="1730" height="923" alt="S1" src="https://github.com/user-attachments/assets/f6b0f415-6c75-48d8-bdde-7161eb59e0f2" />

### 任务二 配置模型并完成一次会话

使用 DeepSeek API Key 方式登录。

<img width="1730" height="923" alt="S2" src="https://github.com/user-attachments/assets/6b5bcdfd-1749-4120-8420-2ef228840016" />

### 任务三 切换模型与思考级别

<img width="1728" height="924" alt="S3-1" src="https://github.com/user-attachments/assets/c9bfc397-bd1b-4a14-bfa6-12a064574721" />

<img width="1728" height="924" alt="S3-2" src="https://github.com/user-attachments/assets/75e904e7-93b2-4041-ae00-be5bc4818787" />

### 任务四 引用代码并粘贴小图片

**A 使用 @ 引用代码文件**

<img width="2559" height="1527" alt="S4" src="https://github.com/user-attachments/assets/61d201e1-3842-4623-b74b-7a6dd542568d" />


**B 粘贴小图片并测试**

<img width="1629" height="840" alt="S5" src="https://github.com/user-attachments/assets/b98cbb7b-5be7-4322-a7d3-4fdb66be27e9" />


原始测试图片：

<img width="200" height="200" alt="blue-square-7" src="https://github.com/user-attachments/assets/ea141c6e-684d-4f44-b54c-bf2eb9e933b8" />


### 任务五 安装并使用一个插件

| 项目 | 内容 |
|---|---|
| 名称 | pi-web-access |
| 来源 | npm `pi-web-access`，https://github.com/nicobailon/pi-web-access |
| 安装命令 | `pi install npm:pi-web-access -l` |
| 作用 | 网页搜索、URL 抓取、GitHub 仓库克隆、PDF 提取、视频理解 |
| 所需配置 | 零配置可用（默认 Exa MCP），可选配置各家搜索 API key |

<img width="1730" height="923" alt="S6" src="https://github.com/user-attachments/assets/ea09f10b-a9d5-4cea-b64e-ff0a3c4e98ed" />

### 任务六 安装 PPT Skill（选做）

| 项目 | 内容 |
|---|---|
| 安装位置 | `D:\pi-test\.pi\skills\pptx` |
| 文件数 | 59 个 |
| 源 commit | e4bb5d960d87126ff3b3a8af1a104b7db67560ba |

<img width="1440" height="968" alt="S7" src="https://github.com/user-attachments/assets/385c710c-623b-4aac-8662-9c51f6523b41" />

<img width="2559" height="1527" alt="S8" src="https://github.com/user-attachments/assets/933ce567-7f29-4f5f-bdce-aa091bbabf88" />
