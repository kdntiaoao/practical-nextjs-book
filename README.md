# 書籍「実践Next.js」の学習用リポジトリ

- 書籍ページ
  - https://gihyo.jp/book/2024/978-4-297-14061-8
- サンプルコード
  - https://github.com/practical-nextjs-book/training
  - https://github.com/practical-nextjs-book/applications

## ディレクトリ構成

```
.
├── practices        個人的な検証
└── samples          公式のサンプル
    ├──  training    第 1 章〜第 4 章：練習用プロジェクトを用いた Next.js の基礎的な解説
    └── applications 第 5 章〜第 10 章：SNS アプリを用いた Next.js の実践的な解説
```

## サンプルコードの起動

```bash
# ルートでパッケージをインストールする
npm ci

# 任意のディレクトリに移動
cd samples/training

# 任意のワークスペースのローカルサーバー起動
npm run dev -w packages/training-web-1
```
