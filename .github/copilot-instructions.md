# GitHub Copilot Instructions - tomacheese Organization

## 言語設定 (Language Settings)

- **会話言語**: すべての会話（PR本文、レビューへの対応、コメントなど）は日本語で行うこと
- **PRタイトル**: 英語で記載すること
- **コミットメッセージ**: 英語で記載すること

## コミット規約 (Commit Conventions)

PRタイトルとコミットメッセージは [Conventional Commits](https://www.conventionalcommits.org/) の仕様に従うこと。

### フォーマット例
- `feat: add new feature`
- `fix: resolve authentication issue`
- `docs: update README`
- `style: fix eslint issues`
- `refactor: improve code structure`
- `test: add unit tests`
- `chore: update dependencies`

## 共通コーディング規約 (Common Coding Standards)

### プロジェクト構成
- **ライセンス**: MIT License を使用
- **パッケージマネージャー**: pnpm を優先使用
- **主要言語**: TypeScript を推奨

### コード品質
- **Linter**: ESLint を使用（`@book000/eslint-config` を推奨）
- **フォーマッタ**: Prettier を使用
- **型チェック**: TypeScript の厳密な型チェックを有効化

### 開発ワークフロー
- **CI/CD**: GitHub Actions を使用
- **プルリクエスト**: レビューを必須とし、コードの品質を維持
- **自動化**: 可能な限りスクリプトやワークフローで自動化

## 注意事項 (Notes)

この指示書は tomacheese オーガニゼーション全体に適用されるため、各プロジェクトの特性に関わらず共通で適用できる最小限のルールのみを記載しています。プロジェクト固有の詳細な規約については、各リポジトリの README やドキュメントを参照してください。