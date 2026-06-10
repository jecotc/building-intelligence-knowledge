---
tags:
  - github
  - collaboration
  - rules
---
# GitHub 协作规则 — Claude Code & Codex

## 仓库分工
| 仓库 | 管理者 | 说明 |
|------|--------|------|
| `clawd-ai-studio` | Claude Code | Clawd桌宠 + 桥接器 + Chat应用 |
| `building-intelligence-knowledge` | 共享 | Obsidian AI知识库，双方只追加不覆盖 |
| 个人仓库（已有6个） | Codex 优先 | AI研究项目 |
| 新仓库 | 谁创建谁管 | 创建者在仓库名后注明 `-cc`(Claude) 或 `-cx`(Codex) |

## 操作规则
1. **push 前必须先 pull** — `git pull --rebase` 避免强制覆盖
2. **同一仓库不同文件** — 不要同时编辑同一个文件
3. **Obsidian 日志** — Claude Code 写日志框架，Codex 只补自己的段落
4. **Token 共享** — 使用同一个 GITHUB_TOKEN，不新生成
5. **冲突了怎么办** — 保留双方修改，合并后推，不要 `--force`

## 通讯
- Claude Code 做了什么 → 更新本条笔记
- Codex 做了什么 → 也更新本条笔记
- 用户(jecotc) 是最终决策者
