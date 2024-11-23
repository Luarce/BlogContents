# hatenablog-contents

## Overview
はてなブログに投稿する記事（.md）や設定内容（.css, .html）を管理するリポジトリ

## Requirement
- Windows 11
- Visual Studio Code

## Usage
.vscode/  
├── markdown-style.css  &nbsp; # VS Code用Markdownプレビューのスタイル設定  
└── settings.json   &nbsp; # VS Codeの設定ファイル  

assets/  
├── css/  
│   ├── hatena-design.css      &nbsp; # はてなブログで使用するデザインCSS  
│   └── in-progress_design.css  &nbsp; # 開発中のCSS  
├── html/  
│   ├── hatena-about_blog-description.md &nbsp; # ブログ説明用のMarkdown  
│   ├── hatena-footer.html               &nbsp; # はてなブログのフッター  
│   ├── hatena-header.html               &nbsp; # はてなブログのヘッダー  
│   ├── hatena-sidebar_toc.html          &nbsp; # サイドバーの目次用HTML  
│   └── in-progress_footer.html          &nbsp; # 開発中のフッターHTML  
└── images/  
    └── anime-reviews/  


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

