# hatenablog-contents

## Overview
**はてなブログ**に投稿する記事（`.md`）や設定ファイル（`.css`, `.html`）を管理する個人用リポジトリ

## Requirement
- **OS**: Windows 11  
- **Editor**: Visual Studio Code  

## Usage
1. **Visual Studio Code**でリポジトリを開く  
2. 記事（`.md`）、デザイン（`.css`）、ヘッダーやフッター（`.html`）を編集  
3. **はてなブログ**にアクセスし、編集内容をコピペして反映


## Features
### ディレクトリ構成

```plaintext
.vscode/
├── markdown-style.css
└── settings.json
```

| ファイル名             | 詳細                                   |
|------------------------|----------------------------------------|
| `markdown-style.css`   | VS Code用Markdownプレビューのスタイル設定 |
| `settings.json`        | VS Codeのプロジェクト固有の設定       |


```plaintext
assets/
├── css/
│   ├── hatena-design.css
├── html/
│   ├── hatena-about_blog-description.md
│   ├── hatena-footer.html
│   ├── hatena-header.html
│   ├── hatena-sidebar_toc.html
└── images/
```

| ファイル名             | 詳細                                   |
|------------------------|----------------------------------------|
| `hatena-design.css`    | はてなブログのデザインCSSファイル     |
| `hatena-about_blog-description.md` | ブログ説明用のMarkdownファイル         |
| `hatena-footer.html`             | はてなブログのフッターHTML             |
| `hatena-header.html`             | はてなブログのヘッダーHTML             |
| `hatena-sidebar_toc.html`        | サイドバー目次用HTML                  |
| *各種画像*    | アニメ感想記事用の画像フォルダ |

```plaintext
posts/
├── about/
│   └── about.md
└── anime-reviews/
　   └── anime-reviews_2024_summer.md
```

```plaintext
templates/
├── parts.md
└── template.md
```

```plaintext
drafts.md
.gitattributes
.htmlhintrc
```

## Reference
これからメモる

## Author

[はてなブログ - Lua_Archives](https://luarce.hatenablog.com/archive)

[Twitter (@luarce77)](https://twitter.com/luarce77)

## Licence
This repository is licensed under the MIT License.

