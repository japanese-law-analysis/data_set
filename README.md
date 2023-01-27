これは法律・判例などのデータセットです。

フォルダ・ファイルとその中身は以下のようになっています。

# law

法令関係が入っています

## law/list.json

[e-gov法令検索](https://elaws.e-gov.go.jp/)からダウンロードできる法令データの一覧です。

[listup_law](https://github.com/japanese-law-analysis/listup_law)を使用して生成しています。

## law/repeal_list.json

[e-gov法令検索/廃止法令一覧](https://elaws.e-gov.go.jp/repeal/)からダウンロードできる廃止された法令データの一覧です。

[listup_law](https://github.com/japanese-law-analysis/listup_law)を使用して生成しています。

## law/ryakusyou.json

「～（以下「～」という。）」や「～（～をいう。）」のような略称・定義規定を解析し、略称部分と正式名称部分を抜き出したリストです。

[analysis_ryakusyou](https://github.com/japanese-law-analysis/analysis_ryakusyou)を使用して解析・生成しています。

# precedent

判例関係が入っています。

## precedent/list.json

判例集の情報が書かれています。

[listup_precedent](https://github.com/japanese-law-analysis/listup_precedent)を使用して生成しています。

## precedent/listup_info.json

`precedent/list.json`ファイルの生成範囲などが書かれています。


## precedent/text_files/*.txt

`precedent/list.json`に書かれている全ての判例のテキストファイルが置かれています。

[pdf2txt_precedent](https://github.com/japanese-law-analysis/pdf2txt_precedent)を使用して生成しています。

# ライセンス

著作権法第十三条の規定により、法令・判決は著作権が発生しません。よって、これをもとに生成した本データセットも著作権が発生しません。

よって、CC0ライセンスのもと公開します。
