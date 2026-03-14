---
name: ln-brainstormer
description: ライトノベルのアイデア（コンセプト、キャラ、世界観、プロット等）をブレインストーミングし、テンプレートに従って1アイデア1ファイルで書き出します。
---

# ln-brainstormer

このスキルは、ライトノベルの創作活動をサポートし、アイデアを構造化して保存するためのガイドを提供します。

## ワークフロー

### 0. 作業ディレクトリ（配置先）の決定
このスキルは **いま作業しているディレクトリ** を尊重して、アイデアの出力先（ベース）を決めます。

- ルートで作業している場合: リポジトリ直下の `00_concept/` などに配置します
- `ideas/<concept>/` 配下で作業している場合: そのディレクトリ配下の `00_concept/` などに配置します

実務上は「`00_concept/`（〜`07_notes/`）が存在する一番近い親ディレクトリ」をベースにしてください。

### 1. アイデアの着想・深掘り
ユーザーとの対話を通じて、物語の核となる「面白さ」を引き出します。以下の視点を提供してください。
- **「もし〜だったら？」(What If)**: 斬新な設定の提案。
- **カタルシスの設計**: 読者がどこでスッキリするか、何に感動するか。
- **キャラクターのギャップ**: 意外な一面や弱点による人間味の付与。

### 2. テンプレートの適用
アイデアが具体化したら、上で決めた「ベースディレクトリ」配下の要素フォルダにテンプレートを適用します。

- `<base>/00_concept/`: [concept.md](references/concept.md)
- `<base>/01_worldbuilding/`: [worldbuilding.md](references/worldbuilding.md)
- `<base>/02_characters/`: [character.md](references/character.md)
- `<base>/03_plot/`: [plot.md](references/plot.md)
- `<base>/04_scenes/`: [scene.md](references/scene.md)
- `<base>/05_lore/`: [lore.md](references/lore.md)
- `<base>/06_theme/`: [theme.md](references/theme.md)
- `<base>/07_notes/`: [note.md](references/note.md)

### 3. ファイルの保存
- **1アイデア1ファイル**: アイデアごとに新しいマークダウンファイルを作成します。
- **命名規則**: ファイル名は `snake_case` または `kebab-case` で、内容がひと目でわかるものにしてください。
  - ルート運用の例: `02_characters/ai_middle_manager_vr_main_heroine.md`
  - `ideas/<concept>/` 運用の例: `ideas/001_some_concept/02_characters/main_heroine_aria.md`
- **既存設定との整合性**: 新しいアイデアを追加する際は、既存のファイルを `grep_search` 等で確認し、矛盾がないかチェックしてください。

## 執筆のアドバイス
- **読者の期待**: そのジャンルの読者が何を求めているか（例：追放系なら「見返し」、ラブコメなら「ニヤニヤ」）を常に意識してください。
- **引きの強さ**: 各章や各シーンの終わりに、次のページをめくりたくなる「引き」を作ってください。
