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
├── markdown-style.css //
└── settings.json
```

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

