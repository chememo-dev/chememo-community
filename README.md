# Chememo Community

化学を学ぶすべての人のための、知識共有コミュニティです。

実験で困ったこと、調べてわかったこと、論文を読んで理解したことなど、化学に関する知見を記事にして共有する場所です。

## このリポジトリについて

ここは [Chememo](https://chememo.pages.dev) に掲載される記事やコミュニティ運営の場です。

- **記事**: `[著者ID]/記事名.md` に Markdown 形式で記事を保管しています
- **コメント**: 各記事へのコメントは [Discussions](https://github.com/chememo-dev/chememo-community/discussions) で管理しています
- **要望・課題**: サイトやコミュニティへの要望は [Issues](https://github.com/chememo-dev/chememo-community/issues) で受け付けています

## 要望や課題の出し方

サイトの改善要望、記事の内容に関する指摘、新しい機能の提案などは [Issues](https://github.com/chememo-dev/chememo-community/issues) に投稿してください。

- できるだけ具体的に書いていただけると対応しやすいです

## 記事を書くには

Chememo では誰でも記事を投稿できます。プログラミングの知識は不要で、すべてブラウザ上で完結します。

### 大まかな流れ

1. GitHub アカウントを作成する（初回のみ）
2. このリポジトリをフォークする（初回のみ）
3. `あなたのGitHubユーザー名/記事名.md` というファイルを作成して記事を書く
4. Pull Request を送る
5. レビュー後に公開

### 詳しい手順

記事の書き方（フロントマターの設定、Markdown 記法、化学式の書き方など）は、以下のガイドで詳しく説明しています。

- [記事を書く](https://chememo.pages.dev/guide/writing) — 投稿手順・Markdown 記法
- [コンテンツガイドライン](https://chememo.pages.dev/guide/content) — 記事の品質基準・文体ルール
- [コミュニティガイドライン](https://chememo.pages.dev/guide/community) — コミュニティのルール

### 記事テンプレート

```markdown
---
title: "記事のタイトル"
description: "記事の概要（1〜2文）"
pubDate: 2026-01-15
tags: ["有機化学", "実験技術"]
---

ここから本文を書きます。
```

## ディレクトリ構成

```
chememo-community/
├── clameyes/             # 著者: clameyes
│   ├── profile.md        # 著者プロフィール
│   ├── recrystallization.md
│   └── ...
├── your-username/        # 著者: あなた
│   ├── profile.md
│   └── your-article.md
└── README.md
```

## ライセンス

投稿された記事の著作権は各著者に帰属します。
