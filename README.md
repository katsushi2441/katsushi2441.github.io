# katsushi2441.github.io

GitHub Pages のユーザーサイト（ドメイン直下）。

プロジェクトページ（`/vwork/` など）からは配置できない **ドメインルート専用ファイル** を配信するためのリポジトリです。

| パス | 役割 |
|---|---|
| `robots.txt` | AI検索クローラー（GPTBot / ClaudeBot / PerplexityBot ほか）の明示許可とsitemap宣言 |
| `llms.txt` | サイトの要点と主要ページ（llms.txt仕様） |
| `.well-known/ai.txt` | 学習・検索インデックス・引用の利用方針 |
| `ai/summary.json` | AIエージェント向けのサイト概要 |
| `ai/faq.json` | よくある質問（用語定義・免責） |
| `ai/service.json` | 提供プロダクトと料金の一覧 |
| `sitemap.xml` | ルートと主要ページ |
| `index.html` | ドメイン直下のトップページ |

`.nojekyll` を置いて Jekyll のビルドを無効化しています（`.well-known/` のような
ドット始まりディレクトリが除外されるのを防ぐため）。

運営: 株式会社エクスブリッジ (EXBRIDGE, Inc.) https://exbridge.jp/
