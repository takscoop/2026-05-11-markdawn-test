# 2026-05-11-markdawn-test
2026-05-11-markdawn-test

# AI Task Manager

AIがタスクの優先順位を自動で提案してくれる、次世代のタスク管理アプリケーションです。
日々の業務の「何から手をつければいいか分からない」を解決します。

## デモ



> [!NOTE]
> 現在は開発中のため、デモ環境はローカルでのみ動作します。

## 技術スタック

| カテゴリ | 技術 | バージョン |
| :--- | :--- | ---: |
| フロントエンド | React | 18.2 |
| フレームワーク | Next.js | 14.0 |
| スタイリング | Tailwind CSS | 3.3 |
| AI連携 | OpenAI API | - |

## 前提条件

- Node.js v18以上
- npm v9以上

## セットアップ

以下の手順でローカル環境を構築できます。

```bash
# リポジトリをクローン
git clone https://github.com/your-username/ai-task-manager.git

# ディレクトリに移動
cd ai-task-manager

# 依存パッケージをインストール
npm install

# 環境変数の設定ファイルをコピー
cp .env.example .env.local
```

> [!IMPORTANT]
> アプリを動かすには、`.env.local` にOpenAIのAPIキーを設定する必要があります。

### 環境変数一覧

| 変数名 | 説明 | 必須 |
| :--- | :--- | :---: |
| `OPENAI_API_KEY` | OpenAIのAPIキー | ✅ Yes |
| `NEXT_PUBLIC_API_URL` | バックエンドのURL | ❌ No |

## 使い方

以下のコマンドで開発サーバーを起動します。

```bash
npm run dev
```
ブラウザで `http://localhost:3000` を開いて確認してください。

