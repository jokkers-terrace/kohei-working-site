# AI向けの作業ルール

このリポジトリを編集するAI（ChatGPT / Codex / Cortex / Claude Code など）は、
作業前に必ず [README.md](README.md) を読むこと。ルールはREADMEの1本にまとめています。

要点だけ：

1. 作業前に `git pull`、作業後に `git push`（`main` に push すると公開されます）。
2. サイト本体は `index.html` の1枚。CSSもJSもこの中。
3. 画像は `assets/` に置いてコミットする。
4. 画像に文字（帯・透かし・署名）を焼き込まない。文字はHTML側で載せる。
