# hatenablog-contents

## Overview
はてなブログに投稿する記事（.md）や設定（.css, .html）を管理するリポジトリ

## Requirement
- Windows 11
- Visual Studio Code

## Usage
1. VSCodeからリポジトリにアクセス
2. VSCodeで記事（.md）や設定（.css, .html）を編集
3. はてなブログにコピペして反映

## Features
### ディレクトリ構成
.vscode/  
├── markdown-style.css  // VS Code用Markdownプレビューのスタイル設定  
└── settings.json   // VS Codeの設定ファイル  


assets/  
├── css/  
│   ├── hatena-design.css      // はてなブログで使用するデザインCSS  
├── html/  
│   ├── hatena-about_blog-description.md // ブログ説明用のMarkdown  
│   ├── hatena-footer.html               // はてなブログのフッター  
│   ├── hatena-header.html               // はてなブログのヘッダー  
│   ├── hatena-sidebar_toc.html          // サイドバーの目次用HTML  
└── images/  


posts/  
├── ジャンル1/  
│   └── 記事名.md  
└── ジャンル2/  
│   └── 記事名.md  

templates/  
├── parts.md    // 記事で利用するパーツテンプレート  
└── template.md // 記事全体のテンプレート  

drafts.md  // 執筆中または草稿のアイデア  

.gitattributes  // Gitの属性設定  
.htmlhintrc // HTMLのコードスタイルチェック設定  
## Reference

## Author

[はてなブログ - Lua_Archives](https://luarce.hatenablog.com/archive)

[Twitter (@luarce77)](https://twitter.com/luarce77)

## Licence

