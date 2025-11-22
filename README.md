# Bun Project

## 開発環境

このプロジェクトは Dev Container を使用した開発環境を提供しています。

### 環境構成

- **ベース OS**: Ubuntu（最新版）
- **ランタイム**: Node.js 22
- **パッケージマネージャー**: Bun、npm
- **ツール**: Docker CLI、GitHub CLI

### プリインストール済み拡張機能

- **Biome** - コード格式化とリンティング
- **Prisma** - ORM サポート
- **Vitest Explorer** - ユニットテストの実行管理
- **Markdown Mermaid** - マークダウン図表作成
- **PostgreSQL** - データベース管理
- **GitLens** - Git 統合

### エディター設定

- **フォーマッター**: Biome（保存時に自動適用）
- **インデント**: 2 スペース
- **自動修正**: ESLint、インポート整理、Biome クイックフィックスが有効

### セットアップ

Dev Container 起動時に以下が自動実行されます：

- ユーザー権限の設定
- Bun のグローバルインストール

詳細は `.devcontainer/devcontainer.json` と `.devcontainer/post-create.sh` を参照してください。
