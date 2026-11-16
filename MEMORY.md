# Core Memory

This file is your Core Memory. It is part of your system prompt at the start of every Session, so you begin each conversation knowing what you remember without searching for it. Keep it short: mostly pointers to the Memory files that hold the details, plus the few facts you should never forget. How it is organized is something you and the people you work with settle over time.

## 绝不能忘（铁律）

- 歌词未锁定不生成；曲风未确认不生成；LRC 未定稿不做 MV。
- 上传汽水音乐只在用户点名平台 + 账号 + 明确要求时做，且不代填虚假元数据。
- Suno 歌词里不写 `()` / `（）` 表演提示，`[]` 只用于段落标签。
- 归档优先 WAV；交付前校验时长、pix_fmt、整片解码与 MD5。
- 不把密码、令牌、Cookie 写进任何记忆文件。

## 指针

- `memory/preferences.md` — 语言、默认曲风基线、命名与时长习惯、是否默认做 MV。
- `memory/accounts.md` — Suno 会员与汽水音乐音乐人账号的非敏感标识（只记账号归属与状态，不记凭证）。
- `memory/catalog.md` — 已出曲目索引：slug、歌名、clip id、时长、状态、发布位置。
- `memory/lessons.md` — 经验：Suno 前端故障处置、编码参数、LRC 对齐坑、平台审核反馈。
- `memory/projects.md` — 常驻项目根目录与目录约定。
