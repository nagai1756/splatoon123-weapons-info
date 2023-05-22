# spl123-weapons-json
* 誰でもご自由にお使いください。
* 間違いなどありましたら是非お伝えください。
* 当方githubについてかなり初心者ですので、あらかじめご容赦ください。
## 目次
* [ブキの分類について](#types)
* [ブキ毎のパラメータについて](#para)
* [fアイル構造について](#struct)
<div id="types">

## ブキの分類について
* spl1(7種)
    * 'シューター'
    * 'リールガン'
    * 'ローラー'
    * 'フデ'
    * 'チャージャー'
    * 'スロッシャー'
    * 'スピナー'
* spl2(11種)
    * 'シューター'
    * 'ブラスター'
    * 'リールガン'
    * 'ボトルガイザー'
    * 'ローラー'
    * 'フデ'
    * 'チャージャー'
    * 'スロッシャー'
    * 'スピナー'
    * 'マニューバー'
    * 'シェルター'
* spl3(11種)
    * 'シューター'
    * 'ローラー'
    * 'チャージャー'
    * 'ブラスター'
    * 'スロッシャー'
    * 'スピナー'
    * 'フデ'
    * 'マニューバー'
    * 'シェルター'
    * 'ストリンガー'
    * 'ワイパー'
<div id="para">

## ブキの詳細情報について
* spl1
    * 名前
    * 種類
    * サブ
    * スペシャル
    * デス時のスペシャルゲージ減少量(%)

* spl2,3
    * 名前
    * 種類
    * サブ
    * スペシャル
    * スペシャル必要ポイント
<div id="struct">

## ファイルの構造について
```json
[
    [
        {
            "name": "**",
            "type": "**",
            "subName": "**",
            "specialName": "**",
            "specialDown": "**"
        },
        ...
        {
            "name": "**",
            "type": "**",
            "subName": "**",
            "specialName": "**",
            "specialDown": "**"
        }
    ],
    [
        ...
    ],
    ...
    [
        ...
        {
            "name": "**",
            "type": "**",
            "subName": "**",
            "specialName": "**",
            "specialDown": "**"
        }
    ]
]
```
