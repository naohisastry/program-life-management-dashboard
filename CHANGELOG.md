# Changelog (更新履歴)

本プロジェクトのダッシュボードおよびデータモデルの変更履歴です。

---

## [v1.19] - 2026-10-02
### Added
- **Unified Header / Footer 共通ナレッジスタイル**:
  - `crypto-utility-trajectory` および `broadcaster-audience-shift-dashboard` と整合した半透明グラスモーフィズム・ヘッダー（`gradient-title`, `version-tag`, `header-desc`）を導入。
  - 共通フッター（`app-footer`, `footer-container`, `footer-title`, `footer-sub`, 動的更新日スクリプト）を標準化。
- **OGP / メタデータ完全準拠**:
  - `og:site_name`, `og:title`, `og:description`, `og:image`, `twitter:card` を正式実装。
  - サムネイル画像 `social-preview.png`（1200×630）を配備。
- **リード文の経営指標体感型改定**:
  - 仮想データベース構築および「Program Life Management」という経営指標導入の重要性を体感できるツールとしての説明へ刷新。
- **GitHub Pages 公開用リポジトリ構築**:
  - `program-life-management-dashboard` としてスタンドアロン公開環境および標準ドキュメント一式を整備。

---

## [v0.19] - 2026-07-30
- 経営俯瞰・番組カルテ・予実健全性の3タブUIの統合。
- 多年度切替（FY2025/多年度拡張）の土台実装。
- 散布図フィット機能（全域／選択にフィット）の追加。

## [v0.18] - 2026-07-28
- P5整合性チェック結果の表示連動。
- 慣行取引独立テーブルの可視化。

## [v0.14] - 2026-07-22
- 初期ダッシュボード試作版。87番組CFグラフのプロトタイプ実装。
