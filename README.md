# zukan

ひろしま企業図鑑 ハイクラス転職LP の作業リポジトリ。

## 中身

| パス | 内容 | 公開URL |
|---|---|---|
| `index.html` | LP構成案（2026-07-28 方針変更版） | https://kenjinakamaru.github.io/zukan/ |
| `lp/` | LPビルド版（dist-portable） | https://kenjinakamaru.github.io/zukan/lp/ |
| `cta-demo/` | 図鑑内導線の下書き | `fuji.html` / `sidebar-banner.html` |

## 重要：このリポジトリの HTML は配布物ではありません

`lp/` 配下の HTML には、レビュー用に `<meta name="robots" content="noindex, nofollow">`
を**意図的に追加してあります**。

**先方に渡す配布物はこちら（noindex なし）:**

```
/Users/nakamaru/Desktop/zukan/0904_zukan_lp2.zip
```

このリポジトリのファイルをそのまま先方に渡したり本番へアップしたりすると、
noindex が付いたまま公開されてインデックスされません。必ず上記 zip を使うこと。

構成案（`index.html`）にも noindex を追加しています。担当者の実名と
内部指示（制作上の注意・残課題と分担・不採用コピー案）を含むため。

## クロール制御

ホスト直下の robots.txt でも `/zukan/` 配下をクロール対象外にしています。

- リポジトリ: https://github.com/kenjinakamaru/kenjinakamaru.github.io
- ファイル: `robots.txt`

なお robots.txt と noindex はいずれもアクセス制御ではありません。
URL を知っていれば誰でも閲覧できます。
