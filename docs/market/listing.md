# BcBlogEssayLiteraryTheme baserマーケット出品 入力値

フォームの欄の順に並べています。

## 基本情報

| 欄 | 入力値 |
|---|---|
| 公開ステータス | 非公開（承認後に公開） |
| テーマ・プラグイン名（商品名） | エッセイのブログテーマ（文芸）（BcBlogEssayLiteraryTheme） |
| 種類 | 無料テーマ ／ レスポンシブデザイン |
| 販売価格（税抜） | 0 |
| カテゴリ | シンプル、baserCMS5対応 |
| バージョン | 1.0.0 |
| ファイル名 | BcBlogEssayLiteraryTheme.zip |
| ファイルアップロード | `BcBlogEssayLiteraryTheme.zip`（GitHub Release の zip と同じもの） |
| 対応バージョン | 5系：5.4.2、5.4.1、5.4.0 |
| 対応バージョン 備考 | baserCMS5.4以上。ブログ（BcBlog）を使います。BurgerEditor（BcBurgerEditor）は任意です（通常のエディタで書いた記事にも対応）。 |
| ライセンス | URLで指定する ／ 名称：MIT License ／ URL：https://github.com/kaburk/BcBlogEssayLiteraryTheme/blob/main/LICENSE |
| 提供者 | 名称：kaburk ／ URL：https://blog.kaburk.com/ |
| Webサイト | 名称：（空欄） ／ URL：https://github.com/kaburk/BcBlogEssayLiteraryTheme |
| デモサイト | 空欄 |
| サポートページ | 公式サイト以外 ／ 名称：（空欄） ／ URL：https://github.com/kaburk/BcBlogEssayLiteraryTheme/issues |

## 説明概要（一覧画面・200文字以内：163文字）

```
baserCMS5.4以上向けの、エッセイ・コラム・日記のためのブログテーマです。生成りの地に明朝の見出しと本文を組んだ文庫本のような1カラムで、書き手のプロフィール・読了時間・ライト／ダークの切り替えを備えています。配色はテーマ設定の4色で変更でき、見本の記事・プロフィール・お問い合わせフォーム付きの初期データがあります。
```

メイン画像：`main.png`（500×500）

---

## 説明情報1

**説明見出し1**：このテーマについて

**説明詳細1**（エディタの「ソース」に貼る）

```html
<p>BcBlogEssayLiteraryTheme は、エッセイ・コラム・日記など、長い文章を落ち着いて読んでもらうための個人ブログのテーマです。生成り（紙の色）の地に、明朝の見出しと本文を組んだ、文庫本のような落ち着いた見た目です。段落の頭の1字下げ、傍点の強調、「＊　＊　＊」の場面の区切りで、長い文章を読ませます。</p>
<p>同じ仕組みで見た目だけが違う、2つのエッセイのブログテーマ（BcBlogEssayLiteraryTheme・BcBlogEssaySoftTheme）があります。</p>
<ul>
<li>サイドバーのない1カラム。本文の幅は1行 34〜38 文字程度で、文字と行間はゆったり</li>
<li>記事の詳細：読了時間の目安、投稿日・更新日、書き手のプロフィール（写真・名前・ひとこと・SNS）、本文の下のシェア、前後の記事、関連記事、コメント</li>
<li>一覧：1列で全件同じ形。アイキャッチがない記事は画像の場所を出さず、文字だけの形になります</li>
<li>本文：BurgerEditor のブロックでも、通常のエディタの HTML でも同じ見た目。引用、画像とキャプション、場面の区切り、表、補足の囲み</li>
<li>ライト／ダークの切り替え。配色モード（OS に合わせる／ライト／ダーク）と切り替えボタンの有無は、テーマ設定で選べます</li>
<li>テーマ設定の4色（メイン／サブ／リンク／ホバー）で配色を変更できます。どの色にしても文字が読みやすいよう、文字の濃さを自動で調整します。ロゴもテーマ設定で変更できます</li>
<li>お問い合わせフォーム（入力 → 確認 → 完了の3画面）、サイト内検索の結果画面、フッターの書き手のプロフィール</li>
<li>初期データ：見本のブログ一式（default）、ページ送りの確認用（test：記事40本）、最小構成（empty）</li>
<li>レスポンシブ（PC／スマホ）、印刷用の CSS、prefers-reduced-motion 対応</li>
</ul>
```

**説明画像1**：`pc-1-top.png`（PC：トップ）

---

## 説明情報2

**説明見出し2**：動作環境とインストール

**説明詳細2**

```html
<h4>動作環境</h4>
<ul>
<li>baserCMS5.4以上</li>
<li>ブログ（BcBlog）が有効であること。BurgerEditor（BcBurgerEditor）は任意です</li>
<li>最新の Chrome・Edge・Safari・Firefox（CSS のコンテナクエリ・:has()・color-mix() を使っています）</li>
</ul>
<h4>インストール</h4>
<ol>
<li>ダウンロードした zip を解凍し、フォルダ名が「BcBlogEssayLiteraryTheme」であることを確認して plugins フォルダに配置します（管理画面からのアップロードも可能です）</li>
<li>管理画面 &gt; テーマ管理 で BcBlogEssayLiteraryTheme を適用します</li>
<li>同じ画面で初期データ「default」（見本のブログ）・「test」（ページ送りの確認用）・「empty」（最小構成）のいずれかを読み込みます</li>
</ol>
<p><strong>初期データを読み込むと、ユーザー以外のデータ（固定ページ・ブログ・メールフォーム・ウィジェットなど）は初期化されます。運用中のサイトでは読み込まないでください。</strong></p>
```

**説明画像2**：`sp.png`（スマホ：トップ／記事の詳細／記事の詳細のダークモード）

---

## 説明情報3

**説明見出し3**：ソースコード・ライセンス

**説明詳細3**

```html
<p>ソースコードは GitHub で公開しています。不具合の報告・要望は Issues にお願いします。</p>
<p><a href="https://github.com/kaburk/BcBlogEssayLiteraryTheme" target="_blank">https://github.com/kaburk/BcBlogEssayLiteraryTheme</a></p>
<p>テーマ本体は MIT License です。同梱物・外部リソースのライセンスは次のとおりです。</p>
<ul>
<li>jQuery 3.7.1（同梱）：MIT License</li>
<li>Google Fonts（Shippori Mincho、CDN から読み込み）：SIL Open Font License 1.1</li>
<li>アイコン・見本画像：このテーマの一部（MIT License）</li>
</ul>
<p>ご利用は自己責任でお願いします。</p>
```

**説明画像3**：`pc-2-post.png`（PC：記事の詳細）

---

## 説明情報4

**説明見出し4**：（空欄）

**説明詳細4**：（空欄）

**説明画像4**：`pc-3-profile.png`（PC：プロフィールのページ）

---

## 説明情報5

**説明見出し5**：（空欄）

**説明詳細5**：（空欄）

**説明画像5**：`form.png`（PC：お問い合わせの入力画面）

予備：`pc-4-dark.png`（PC：記事の詳細のダークモード）。差し替えたいときに使う。

---

## リリース

| 欄 | 入力値 |
|---|---|
| リリース種別 | 新規公開申請 |
| リリースノート | 新規リリース |

---

## zip の確認結果

GitHub Release 1.0.0 の `BcBlogEssayLiteraryTheme.zip` を作ったあとに確認して書く。

- 最上位フォルダ名が `BcBlogEssayLiteraryTheme` か（解凍してそのまま plugins に置けるか）
- `config.php`・`VERSION.txt`（1.0.0）・`screenshot.png`・初期データ（default／test／empty）・`LICENSE`・`README.md` を含むか
- `.github`・`docs`・`.DS_Store`・作業用ファイルを含まないか
