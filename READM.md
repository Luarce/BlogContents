# hatenablog-contents

## Overview
はてなブログに投稿する記事（.md）や設定内容（.css,.html）を管理するリポジトリ

## Requirement
- Windows 11
- Visual Studio Code

## Usage
.vscode/  
├── markdown-style.css  # VS Code用Markdownプレビューのスタイル設定  
└── settings.json   # VS Codeの設定ファイル  

assets/  
├── css/  
│   ├── hatena-design.css       # はてなブログで使用するデザインCSS
│   └── in-progress_design.css  # 開発中のCSS
├── html/
│   ├── hatena-about_blog-description.md # ブログ説明用のMarkdown
│   ├── hatena-footer.html               # はてなブログのフッター
│   ├── hatena-header.html               # はてなブログのヘッダー
│   ├── hatena-sidebar_toc.html          # サイドバーの目次用HTML
│   └── in-progress_footer.html          # 開発中のフッターHTML
└── images/
    └── anime-reviews/
        ├── makeine_title.png      # アニメ感想記事用の画像
        ├── nigoriri_title.png     # 同上
        ├── roshidere_title.png    # 同上
        └── shikanoko_title.png    # 同上

posts/
├── about/
│   └── about.md                # 「ブログについて」の記事
└── anime-reviews/
    └── anime-reviews_2024_summer.md # 2024年夏アニメ感想

templates/
├── parts.md                   # 記事で利用するパーツテンプレート
└── template.md                # 記事全体のテンプレート

.gitattributes              # Gitの属性設定
.htmlhintrc                 # HTMLのコードスタイルチェック設定
drafts.md                   # 執筆中または草稿のアイデア

## Features

## Reference

## Author

[はてなブログ - Lua_Archives](https://luarce.hatenablog.com/archive)

[Twitter (@luarce77)](https://twitter.com/luarce77)

## Licence

