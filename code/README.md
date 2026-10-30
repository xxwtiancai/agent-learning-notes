# 代码阅读

[返回首页](../README.md) · [代码阅读模板](../templates/code-note.md)

起始队列覆盖 Harness、RSI、Memory 和 Sandbox。下面的 commit 是 2026-10-30 核对的阅读快照，预建笔记仍为 `queued`，不代表已经完成代码分析或运行。

| ID | 仓库 | 主题 | 阅读快照 | 状态 | 笔记 |
| --- | --- | --- | --- | --- | --- |
| C001 | [Harness²](https://github.com/google-research/harness2) | Harness / RSI | [1cfe254](https://github.com/google-research/harness2/tree/1cfe254e8d25b15f37048c3730134686abe60335) | `queued` | [阅读起点](harness2.md) |
| C002 | [Strands Harness SDK](https://github.com/strands-agents/harness-sdk) | Harness / Runtime | [0f8bf1a](https://github.com/strands-agents/harness-sdk/tree/0f8bf1a850851afb5c1b1142496b0e5a7356fc86) | `queued` | [阅读起点](strands-harness-sdk.md) |
| C003 | [OpenHands Software Agent SDK](https://github.com/OpenHands/software-agent-sdk) | Harness / Tools / Sandbox | [f0adfd0](https://github.com/OpenHands/software-agent-sdk/tree/f0adfd0aef206f73f755313b41043333f1de4c6f) | `queued` | [阅读起点](openhands-sdk.md) |
| C004 | [OpenSandbox](https://github.com/opensandbox-group/OpenSandbox) | Sandbox / Execution | [e731067](https://github.com/opensandbox-group/OpenSandbox/tree/e731067ad09f891f331dbbaa64fcdfb4ceb73031) | `queued` | [阅读起点](opensandbox.md) |
| C005 | [Letta Code](https://github.com/letta-ai/letta-code) | Memory / Harness | [1595958](https://github.com/letta-ai/letta-code/tree/15959581a2b2ed9535982d20916220e42043ff2e) | `queued` | [阅读起点](letta-code.md) |
| C006 | [Darwin Gödel Machine](https://github.com/jennyzzt/dgm) | RSI / Code evolution | [a565fd2](https://github.com/jennyzzt/dgm/tree/a565fd2d1dca504ef5104a7cc0f3bdc4ab9b4fd2) | `queued` | [阅读起点](dgm.md) |

## 新增或继续阅读

1. 新增条目时写下仓库、commit 和一个具体阅读问题，再复制模板。
2. 已有笔记从固定版本开始读。重要调用链使用 commit 链接，避免默认分支变化后失去上下文。
3. 更新到新版本时，在笔记中保留旧 commit，并记录本次阅读版本的变化。
4. 实际运行以后，再补充环境、命令与观察结果；仅静态阅读时如实标明。

MemGPT 论文与当前 Letta Code 是不同时间的材料，按历史版本和当前实现分别理解。
