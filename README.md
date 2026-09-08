# CUMCM Codex Skill

本仓库用于队内共享完整的 `cumcm-step-review` Skill，包含建模流程、历年优秀论文摘要与分析、算法资料、论文检索工具、绘图工具、LaTeX/PDF/DOCX 支持文件和模板。

## 在 Codex 中安装

最方便的方法是在 Codex 中发送：

> 请使用 skill-installer 从 GitHub 仓库 Math3666/cumcm 的 `skills/cumcm-step-review` 路径安装这个 Skill。


安装完成后，新开一个 Codex 任务或在下一轮调用：

> 使用 cumcm-step-review 完成这道国赛题。

## 手动安装

将 `skills/cumcm-step-review` 整个目录复制到：

```text
%CODEX_HOME%\skills\cumcm-step-review
```

如果没有设置 `CODEX_HOME`，Windows 默认位置通常为：

```text
%USERPROFILE%\.codex\skills\cumcm-step-review
```

必须复制整个目录，不能只复制 `SKILL.md`，否则优秀论文资料、算法资料和配套工具不会随 Skill 一起安装。

## 仓库结构

```text
skills/cumcm-step-review/
├── SKILL.md
├── references/
├── assets/
├── scripts/
├── tools/
└── agents/
```

题目数据、队伍论文和运行结果不属于本仓库，应放在各自比赛项目目录中。
