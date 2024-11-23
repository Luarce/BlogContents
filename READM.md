# hatenablog-contents

## Overview
**はてなブログ**の記事管理やカスタマイズを効率化するためのリポジトリ  

## Requirement
- **OS**： Windows 11
- **Editor**： Visual Studio Code
  - **推奨プラグイン**：
    - Markdown All in One
    - markdownlint

## Usage
1. **Visual Studio Code**でリポジトリを開く
2. 記事（`.md`）、デザイン（`.css`）、ヘッダーやフッター（`.html`）を編集
3. **はてなブログ**にアクセスし、編集内容をコピペして反映

## Features
### ディレクトリ構成
#### .vscode/
| ファイル | 詳細 |
|--------|-----|
| `markdown-style.css` | VS Code用Markdownプレビューのスタイル設定 |
| `settings.json` | VS Codeのプロジェクト固有の設定 |

#### assets/
| ファイル | 詳細 |
|--------|-----|
| `css/hatena-design.css` | `デザイン -> カスタマイズ -> デザインCSS` |
| `html/hatena-about_blog-description.md` | `設定 -> aboutページ編集 -> 表示設定 -> ブログの説明(モード：Markdown)` |
| `html/hatena-footer.html` | `デザイン -> カスタマイズ -> フッタ` |
| `html/hatena-header.html` | `デザイン -> カスタマイズ -> ヘッダ` |
| `html/hatena-sidebar_toc.html` | `デザイン -> カスタマイズ -> サイドバー -> 追加モジュール` |
| `images/` | アニメ感想用画像ディレクトリ |

#### posts/
| ファイル | 詳細 |
|--------|-----|
| `about/about.md` | ブログの概要説明記事 |
| `anime-reviews/anime-reviews_2024_summer.md` | 2024年夏アニメの感想記事 |

#### templates/
| ファイル | 詳細 |
|--------|-----|
| `parts.md` | 記事で使用するパーツテンプレート |
| `template.md` | 記事全体のテンプレート |

#### その他 (root/)
| ファイル | 詳細 |
|--------|-----|
| `drafts.md` | 執筆中または草稿のアイデア |
| `.gitattributes` | Gitの属性設定 |
| `.htmlhintrc` | HTMLコードスタイルチェック設定 |

## Reference
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [はてなブログ公式ヘルプ](https://help.hatenablog.com/)

## Author

[はてなブログ - Lua_Archives](https://luarce.hatenablog.com/archive)  
[Twitter (@luarce77)](https://twitter.com/luarce77)

## Licence
This repository is licensed under the MIT License.
