# 7大特典サイト 作業メモ

最終更新: 2026-06-08（完成版）

## 公開URL
- ホーム: https://barbiechan7.github.io/7tokuten/
- 第1章: https://barbiechan7.github.io/7tokuten/chapter1.html
- 第2章: https://barbiechan7.github.io/7tokuten/chapter2.html
- 第3章: https://barbiechan7.github.io/7tokuten/chapter3.html（コンビニの食事選び）
- 第4章: https://barbiechan7.github.io/7tokuten/chapter4.html（ダイエットへの想い・note・相談会案内）

## ローカルフォルダ
```
/Users/yukin/Sites/7tokuten
```

Cursor で編集するときは、このフォルダを開いてから依頼する。

## GitHub
- リポジトリ: https://github.com/barbiechan7/7tokuten
- ブランチ: main
- Pages: main / ルート(/)

## ファイル構成
| ファイル | 内容 |
|---|---|
| `index.html` | ホーム（ヒーロー＋写真＋目次） |
| `chapter1.html` | 第1章：一生ダイエッター思考診断 |
| `chapter2.html` | 第2章：ダイエット自己分析シート（CodePenリンク） |
| `chapter3.html` | 第3章：コンビニの食事選び |
| `chapter4.html` | 第4章：ダイエットへの想い（note＋相談会案内） |
| `style.css` | 共通スタイル |
| `images/` | バナー・装飾・hero-photo.png・tokuten-menu.png |

## デザイン
- メインカラー: `#fd90b6`
- 章ボタン: ピンクのグラデーション4色（style.css の `--gradient-ch1`〜`ch4`）
- ヒーロー: 案A（左テキスト＋2×2ボタン、右角丸写真）
- スマホ: 768px以下で縦並び

## 外部リンク
- 第2章 CodePen: https://codepen.io/barbiechan/full/PwbyOMp
- 第4章 note: https://note.com/yuki7451/n/n577fef452724

## 変更を公開する手順
```bash
cd /Users/yukin/Sites/7tokuten
# 編集後…
git add .
git commit -m "変更内容のメモ"
git push origin main
```
※ push 後、反映まで数分。キャッシュが残る場合は ⌘+Shift+R（PC）または再読み込み（スマホ）。

## Cursor で再編集するとき
「7tokuten のサイトを修正したい」と `/Users/yukin/Sites/7tokuten` を開いた状態で依頼すればOK。
変更後は「push」と言えば GitHub Pages に反映できる。
