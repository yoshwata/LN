# LN

## Codex skills (project-local)

このリポジトリでは `ln-brainstormer` を「このプロジェクトだけ」で使えるように、`CODEX_HOME` をリポジトリ内の `.codex/` に向けて起動します。

- 起動: `./codex.sh`
- 直接起動する場合: `CODEX_HOME="$PWD/.codex" codex`

※ もし `~/.codex/skills/ln-brainstormer` にも入っている場合、他プロジェクトでも見えてしまうので「本当にこのプロジェクトだけ」にしたいならそちらは削除してください。
