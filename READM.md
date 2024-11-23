# hatenablog-contents

## Overview
**はてなブログ**に投稿する記事（`.md`）や設定ファイル（`.css`, `.html`）を管理するリポジトリです。  
Markdownで記事を執筆し、デザインや構造をカスタマイズできます。

---

## Requirement
- **OS**: Windows 11  
- **Editor**: Visual Studio Code  

---

## Usage
1. **Visual Studio Code**でリポジトリをクローン・開く  
2. 記事（`.md`）、デザイン（`.css`）、ヘッダーやフッター（`.html`）を編集  
3. **はてなブログ**にアクセスし、編集内容をコピペして反映

---

## Features
### ディレクトリ構成

```plaintext
.vscode/
├── markdown-style.css
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
├── parts.md                  # 記事で利用するテンプレート部品
└── template.md               # 記事全体のテンプレート
```

```plaintext
drafts.md                     # 執筆中または草稿のアイデア
.gitattributes                # Gitの属性設定
.htmlhintrc                   # HTMLコードスタイルのチェック設定
```

## Reference

## Author

[はてなブログ - Lua_Archives](https://luarce.hatenablog.com/archive)

[Twitter (@luarce77)](https://twitter.com/luarce77)

## Licence

