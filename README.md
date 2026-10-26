# Expression Reference

中英文写作 Skill，当前版本 **1.2.0**。用于写初稿、润色和审稿，覆盖口播、邮件、产品文案、ToB 方案、教程、学术写作、评论、叙事及 UI 文案。

从读者、用途、核心意思、已有材料和说话人出发，按需选读写作参考。修改时保留事实、主张强度和作者自己的表达习惯。

## 安装

将仓库克隆到支持本地 Skills 的工具目录。以下命令用于首次安装，目录已存在时请先检查已有内容。

Codex：

```sh
git clone https://github.com/prest4u/expression-reference.git ~/.agents/skills/expression-reference
```

Claude Code：

```sh
git clone https://github.com/prest4u/expression-reference.git ~/.claude/skills/expression-reference
```

## 使用

新会话中调用 `expression-reference`，提供原稿或材料、读者和用途，例如：

```text
用 expression-reference 修改下面的工作邮件，让句子自然、直接，保留原有安排和承诺：
[粘贴原文]
```

[SKILL.md](SKILL.md) 是入口，按任务指向 `references/genres/`、`references/craft/` 和 `references/languages/` 等参考。公开版本保留[声音档案模板](references/voices/README.md)，个人档案由使用者在本地添加。

仓库保留旧版参考资料及其来源说明；当前选读路径以 SKILL.md 为准。

## 许可

本项目原创内容采用 [MIT License](LICENSE)。引用作品及外部内容的权利归其各自权利人所有，详见 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。
