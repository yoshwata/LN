---
name: ln-brainstormer
description: ライトノベルのアイデア（コンセプト、キャラ、世界観、プロット等）をブレインストーミングし、テンプレートに従って1アイデア1ファイルで書き出します。
---

# ln-brainstormer

このスキルは、ライトノベルの創作活動をサポートし、アイデアを構造化して保存するためのガイドを提供します。

## ワークフロー

### 1. アイデアの着想・深掘り
ユーザーとの対話を通じて、物語の核となる「面白さ」を引き出します。以下の視点を提供してください。
- **「もし〜だったら？」(What If)**: 斬新な設定の提案。
- **カタルシスの設計**: 読者がどこでスッキリするか、何に感動するか。
- **キャラクターのギャップ**: 意外な一面や弱点による人間味の付与。

### 2. テンプレートの適用
アイデアが具体化したら、プロジェクトのフォルダ構成に合わせたテンプレートを選択します。
- `00_concept/`: [concept.md](references/concept.md)
- `01_worldbuilding/`: [worldbuilding.md](references/worldbuilding.md)
- `02_characters/`: [character.md](references/character.md)
- `03_plot/`: [plot.md](references/plot.md)
- `04_scenes/`: [scene.md](references/scene.md)
- `05_lore/`: [lore.md](references/lore.md)
- `06_theme/`: [theme.md](references/theme.md)
- `07_notes/`: [note.md](references/note.md)

### 3. ファイルの保存
- **1アイデア1ファイル**: アイデアごとに新しいマークダウンファイルを作成します。
- **命名規則**: ファイル名は `snake_case` または `kebab-case` で、内容がひと目でわかるものにしてください（例: `02_characters/main_heroine_aria.md`）。
- **既存設定との整合性**: 新しいアイデアを追加する際は、既存のファイルを `grep_search` 等で確認し、矛盾がないかチェックしてください。

## 執筆のアドバイス
- **読者の期待**: そのジャンルの読者が何を求めているか（例：追放系なら「見返し」、ラブコメなら「ニヤニヤ」）を常に意識してください。
- **引きの強さ**: 各章や各シーンの終わりに、次のページをめくりたくなる「引き」を作ってください。
