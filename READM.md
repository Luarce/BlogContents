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

#### .vscode/
| ファイル             | 詳細                                   |
|------------------------|----------------------------------------|
| `markdown-style.css`   | VS Code用Markdownプレビューのスタイル設定 |
| `settings.json`        | VS Codeのプロジェクト固有の設定       |

#### assets/
| ファイル             | 詳細                                   |
|------------------------|----------------------------------------|
| `hatena-design.css`    | はてなブログのデザインCSSファイル     |
| `hatena-about_blog-description.md` | ブログ説明用のMarkdownファイル         |
| `hatena-footer.html`             | はてなブログのフッターHTML             |
| `hatena-header.html`             | はてなブログのヘッダーHTML             |
| `hatena-sidebar_toc.html`        | サイドバー目次用HTML                  |
| `images/`    | 画像フォルダ |

#### posts/
| ファイル                     | 詳細                                    |
|--------------------------------|-----------------------------------------|
| `about/about.md`               | ブログの概要説明記事                   |
| `anime-reviews/anime-reviews_2024_summer.md` | 2024年夏アニメの感想記事           |

#### templates/
| ファイル         | 詳細                                  |
|--------------------|---------------------------------------|
| `parts.md`         | 記事で使用するパーツテンプレート      |
| `template.md`      | 記事全体のテンプレート               |

#### その他(root/)
| ファイル         | 詳細                                  |
|--------------------|---------------------------------------|
| `drafts.md`        | 執筆中または草稿のアイデア           |
| `.gitattributes`   | Gitの属性設定                        |
| `.htmlhintrc`      | HTMLコードスタイルチェック設定        |

## Reference
これからメモる

## Author

[はてなブログ - Lua_Archives](https://luarce.hatenablog.com/archive)

[Twitter (@luarce77)](https://twitter.com/luarce77)

## Licence
This repository is licensed under the MIT License.

