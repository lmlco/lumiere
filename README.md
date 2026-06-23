# LUMIÈRE — AI Fashion Digital Magazine

AIでモデル・服・アクセサリーを見せる、女性向けの閲覧型デジタルファッション雑誌のプロトタイプ。
2026年7月号「Summer Glow」/ 専属AIモデル「Aoi」。

外部依存ゼロの単一HTML（CSS/JSインライン）。画像は「AI生成写真風」のプレースホルダーで、各ビジュアルに `data-ai-prompt` を持たせ、後で本物のAI生成画像へ差し替え可能。

## 公開ページ（女性版 LUMIÈRE）

- **縦スクロール版**: https://lmlco.github.io/lumiere/women/ — エディトリアルフィード / 専属AIモデル / Shoppableタグ
- **スライド版**: https://lmlco.github.io/lumiere/women/flip.html — パワポ風スライドデッキ（クリック / 矢印 / スワイプ）

ルート（ https://lmlco.github.io/lumiere/ ）は `women/` へリダイレクトします。ヘッダーから2つのモードを相互に行き来できます。

> 男性版（MERIDIAN）は別途 `mens/` に追加予定。

## 特徴

- Quiet Luxury Editorial のアートディレクション、ライト/ダークモード対応
- レスポンシブ（PC / モバイル）、文字はスライド寸法に比例＋自動フィット
- 外部画像・外部フォント・外部CDN不使用（完全自己完結）
