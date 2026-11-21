<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/header-morning-mist-dark.png" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/header-morning-mist.png" />
    <img src="./assets/header-morning-mist.png" alt="浅蓝晨雾星轨顶部装饰" width="100%" />
  </picture>
</p>

# 你好，这里是热情。

<img align="right" width="180" src="./assets/avatar.png" alt="热情的蓝色 Q 版头像" />

电气科班出身，平时主要和低压嵌入式硬件打交道——画原理图和 PCB、啃芯片手册、查供电与静态测试点是本行。<br />
顺着好奇心往外摸，又慢慢把嵌入式固件、Python 自动化流水线、计算机视觉小实验、Linux 双栈运维与 Cloudflare 边缘工具一块补了起来。

现实让人安静了些，但没磨掉好奇。比起追着热点跑，更喜欢把零散的硬件笔记、排故经验和顺手写出的小工具，打磨成能长期跑得稳、留得住的东西。平时也爱读点历史、经济和心理学杂书；Rust 和更底层的系统工程还在愿望清单里慢慢推进。

欢迎四处看看，也欢迎来聊。

<br clear="right" />

<table>
  <tr>
    <td align="center" width="33%">
      <strong>硬件与嵌入式</strong><br />
      <sub>STM32 · ESP32-S3 · FreeRTOS</sub><br />
      <sub>低压电路 · 仿真调试 · 嘉立创 EDA Pro</sub>
    </td>
    <td align="center" width="33%">
      <strong>自动化与小实验</strong><br />
      <sub>Python · C/C++ · TypeScript</sub><br />
      <sub>AI 流水线 · 视觉识别 · 桌面小工具</sub>
    </td>
    <td align="center" width="33%">
      <strong>运维与长期归档</strong><br />
      <sub>Linux 双栈安全 · Cloudflare · R2 灾备</sub><br />
      <sub>脱敏知识库 · 博客树洞 · 实测验收</sub>
    </td>
  </tr>
</table>

## 「常去的地方」

| 站点 | 定位与内容 |
| :--- | :--- |
| [**Reqing · 小热**](https://reqing.online) | 独立个人主页与社交入口——零追踪脚本、无数据库、原图保真、支持明暗与降噪动效的极简名片页 |
| [**热情的树洞**](https://blog.reqing.online) | 长期写作与知识沉淀——收录嵌入式与硬件学习文档、Linux 运维笔记、信息安全实践、读书随笔与生活记录，配全栈安全加固与 Cloudflare R2 加密异地灾备 |

## 「正在维护与折腾过的事」

- [**`daily-brief-agent`**](https://github.com/reqingonline/daily-brief-agent) · `Python` · 长期运行<br />
  每天早晚定时执行的中文全球大事与市场简报流水线：覆盖多赛道信源采集、`72 h / 7 d` 跨期去重、来源多样性与结构硬校验（不达标自动重写），搭配精确订阅指令与 SMTP 逐一投递。
- **工程与运维脱敏知识库** · `Markdown / Python CI` · 持续沉淀<br />
  把跨阶段的硬件排故卡、Linux 最小权限加固、站点架构与 AI 工作流设计整理成结构化长期文档；显式区分现役基线与历史演进，并内置自动化防泄漏安检脚本与 GitHub Actions 门禁。
- **跨界小实验与顺手工具** · `CV / 仿真 / 桌面端`<br />
  喜欢围绕真实场景顺手造轮子——做过基于 `OpenCV / YOLO / PyQt5` 的无人机目标追踪 GUI、`Proteus` 电路仿真、牌面视觉识别与标注评测、实时语音场景的自动播控小工具，也写过本地离线桌面信息整理工具的完整架构规格。

## 「一点工程洁癖」

- **先查底层，再看上层**：调硬件先量供电与静态点，排网络先测真实协议握手，不把“服务显示绿灯”当验收结论。
- **默认可回滚、零误删**：动关键配置、防火墙或归档目录前先留快照与退路，待清理文件统一进隔离区人工复核，不随手 `rm`。
- **最小权限与防泄漏边界**：公网服务降权运行，笔记、仓库与自动化脚本严禁硬编码凭据，公开交付前默认走一遍静态安检。
- **实用之外也讲点审美**：明暗双主题不留白边、排版克制无冗余，能自己打磨干净的绝不靠臃肿插件硬凑。

## 「手边的工具箱」

- **硬件与仿真**：`STM32` · `ESP32-S3` · `FreeRTOS` · `嘉立创 EDA Pro` · `Proteus` · `PlatformIO` · 示波器与 Python 波形分析
- **开发与数据**：`C / C++` · `Python`（`NumPy / SciPy / OpenCV`）· `TypeScript` · `SQLite` · `Git`
- **系统与边缘云**：`Linux (Ubuntu / Debian)` · `iptables` · `Nginx` · `Docker` · `systemd` · `Cloudflare Workers / Pages / R2`
- **阅读与愿望清单**：`Rust`（学习队列）· 底层网络协议 · 历史 / 经济 / 心理学随读

## 「最近留下的脚印」

<p align="center">
  <a href="https://github.com/reqingonline">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=reqingonline&amp;theme=github-compact&amp;hide_border=true&amp;area=true&amp;bg_color=0d1117&amp;color=58a6ff&amp;line=58a6ff&amp;point=c9d1d9" />
      <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=reqingonline&amp;theme=github-light&amp;hide_border=true&amp;area=true" />
      <img src="https://github-readme-activity-graph.vercel.app/graph?username=reqingonline&amp;theme=github-light&amp;hide_border=true&amp;area=true" alt="热情最近的 GitHub 活动图" width="100%" />
    </picture>
  </a>
</p>

## 「找到我」

- **Email**：[davidhengshaw@gmail.com](mailto:davidhengshaw@gmail.com)
- **Telegram**：[@Xiaore923](https://telegram.me/Xiaore923)
- **OpenPGP**：[`7ABE 0801 596D 6C33`](./pgp-key.asc)（[keys.openpgp.org](https://keys.openpgp.org/vks/v1/by-fingerprint/7D11B30D7B3F03CA1AD62C407ABE0801596D6C33)）

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=reqingonline&amp;label=Profile%20views&amp;color=0e75b6&amp;style=flat" alt="主页访问次数" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/footer-morning-pulse-dark.png" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/footer-morning-pulse.png" />
    <img src="./assets/footer-morning-pulse.png" alt="浅蓝晨雾脉冲底部装饰" width="100%" />
  </picture>
</p>
