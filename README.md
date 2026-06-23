# LUMIÈRE — AI Fashion Digital Magazine

AIでモデル・服・アクセサリーを見せる、女性向けの閲覧型デジタルファッション雑誌のプロトタイプ。
2026年7月号「Summer Glow」/ 専属AIモデル「Aoi」。

外部依存ゼロの単一HTML（CSS/JSインライン）。画像は「AI生成写真風」のプレースホルダーで、各ビジュアルに `data-ai-prompt` を持たせ、後で本物のAI生成画像へ差し替え可能。

## 公開ページ

- **縦スクロール版**: [index.html](https://lmlco.github.io/lumiere/) — エディトリアルフィード / 専属AIモデル / Shoppableタグ
- **スライド版**: [flip.html](https://lmlco.github.io/lumiere/flip.html) — パワポ風スライドデッキ（クリック / 矢印 / スワイプ）

ヘッダーから2つのモードを相互に行き来できます。

## 特徴

- Quiet Luxury Editorial のアートディレクション、ライト/ダークモード対応
- レスポンシブ（PC / モバイル）、文字はスライド寸法に比例＋自動フィット
- 外部画像・外部フォント・外部CDN不使用（完全自己完結）
