---
marp: true
theme: default
header: "とにかく楽をしたい"
footer: "©︎ 4418"

size: 16:9
paginate: true

style: |
    section.title {
        --title-height: 120px;
        --subtitle-height: 64px;

        overflow: visible;
        display: grid;
        grid-template-columns: 1fr;
        grid-template-rows: 1fr var(--title-height) var(--subtitle-height) 1fr;
        grid-template-areas: "." "title" "subtitle" ".";
    }

    section.title h1,
    section.title h2 {
        margin: 0;
        padding: 0;
        text-align: center;
        height: var(--area-height);
        line-height: var(--area-height);
        font-size: calc(var(--area-height) * 0.7);

        
    }

    section.title h1 {
        grid-area: title;
        --area-height: var(--title-height);
    }

    section.title h2 {
        grid-area: subtitle;
        --area-height: var(--subtitle-height);
    }

    section {
        justify-content: start;
    }
---

<!-- _class: title -->

# とにかく楽をしたい！

## 生活を向上させるツールの紹介

<!--
_color: white
_footer: 'Photo by Earl Lasala on Unsplash'
-->

![bg brightness:0.4](https://unsplash.com/photos/xFjti9rYILo/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8MXx8bWFjaGluZXx8MHx8fHwxNjM4MzI1NTA1&force=true)

---

## 楽をしたい

-   何かやりたいけど何ができるのかわからない

-   どうやればいいのかわからない

![bg left:45%](https://unsplash.com/photos/1SAnrIxw5OY/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8NHx8c2ltcGxlJTIwd29ya3x8MHx8fHwxNjM4MzQ2OTQy&force=true)

---

## とにかく楽して終わらせるために

必要なポイント

-   何がどう言うふうに作れるか知る
-   便利なツールを知る
-   省ける作業は省く
-   苦しいことは避ける

![bg left:40%](https://unsplash.com/photos/w6ftFbPCs9I/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8MXx8c291cHx8MHx8fHwxNjM4MzIxMjY1&force=true)

---

## 作るものの例(情報系で)

-   イラストやデザイン制作
-   画像編集
-   動画編集(ちょっとめんどい)
-   Web 制作(ちょっとめんどい)
-   音楽制作(ちょっとめんどい)
-   プログラミング(めんどい)
-   3D CG 制作(難しい)

![bg left:40%](https://unsplash.com/photos/jsgJtBOR6jY/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8MXx8Y3JlcGV8fDB8fHx8MTYzODM0MTY4OQ&force=true)

---

## イラストやデザインに便利なツール

**Figma**
Adobe 系と異なり、**無料**で使える。
Web 上で使えるので、制限 Mac でも Windows でも使える。

![bg left:40%](./images/figma.png)

---

## スライドを楽に作りたい

-   **PowerPoint**は重い

**Marp**という VSCode のプラグインを使うことで、VScode 上で軽量にスライドを作ることができる。**無料**
このスライドも Marp で作成されている。

-   Markdown というマークアップ言語を使う必要がある

![bg left:40%](./images/marp.png)

---

## 文章を書きたくない

**AI のべりすと**を使うと、文章の冒頭部分を与えるだけで、続きを AI に作ってもえる。**無料**

![bg left:40%](./images/novelist.png)

---

## イラストを楽して作りたい

**Photoshop**にはさすが Adobe といえるような高度な機能が付いている。
(制限 Mac でやるのはスペック的におすすめしないけど。)

<br>
Adobe Photoshop 2022の新機能を使って芸術作品を生成する。

![bg left:40%](./images/photoshop.png)

---

## 音楽を作りたい

何を参考にすればわからないという時

**SoundQuest**と言うサイトが便利。**無料**

## おすすめのソフト

Mac や iOS デバイスで使える、**GarageBand**がおすすめ。**無料**

<!-- ここ -->
<!-- https://soundquest.jp/about/ -->

![bg vertical left:40%](./images/soundquest.png)
![bg](./images/garageband.png)

---

## プログラミングがしたかったら

制限 Mac でそこまで準備せずに使うことができる言語は

-   Python
-   Ruby(おすすめしない)

Python でやるおすすめのもの

-   **LINE の BOT**
-   スクレイピング
    サイトから画像などのデータを自動でダウンロードするやつ

![bg left:40%](https://unsplash.com/photos/vpOeXr5wmR4/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8MXx8cHJvZ3JhbW1pbmd8fDB8fHx8MTYzODMzOTE3Mg&force=true)

---

## 実は LINE の BOT は簡単に作れる

LINE には「公式アカウント」と呼ばれるアカウントがあるが、自動で返信してくるやつを BOT という。

左の BOT は Node.js で作られているが、Python でも同じことができる)

<br>

送られたメッセージに対して返答するという基本的な機能に加えて、ボタンや画像を送信することもできる。

![bg left:25%](./images/line.png)

---

## コードが書くのが面倒...

**Copilot**という VSCode の拡張機能を使えば、AI がコードを書くことを手伝ってくれる。

どういうことをしたいのかをコメントに書くことで、AI がコードを補完してくれる。

※Copilot の利用には登録申請が必要

![bg left:40%](./images/copilot.png)

---

## CSS 書きたくない

**Bootstrap**というものを使うことで、CSS をあまり書かずに Web サイトの見た目をよくすることができる。

ググると情報がいっぱい出てくる。

![bg left:40%](./images/bootstrap.png)

---

## 3D モデル作りたいけど...

**Blender**というソフトを使うのが一番手軽だが、制限 Mac に入れるのは少々面倒。
(ICT に行けば多分入れてくれる。)

Blender の使い方は YouTube で調べれば大量に出てくるのでそれを見ればどうにかなる。

![bg left:40%](./images/blender.png)

---

## 3D スキャンソフトを使って楽をしたい

iOS デバイス用のスキャンソフトがたくさんある。
**LiDAR** 搭載デバイスがあると**Scaniverse**というアプリが使える

-   iPhone 12 Pro, Pro Max
-   13 Pro, Pro Max

LiDAR が搭載されていない iOS デバイスでは少し厳しい。
(Android の人は**Matterport**というアプリもあるが、iOS に比べると数が少ない)

![bg left:40%](./images/scaniverse.png)

---

## 3D スキャンした様子

-   細かいところは荒いが、大まかな形は取得できる
-   このモデルを Blender に転送して、いろいろと調整することもできる

![bg left:25%](./images/nishiwaseda2.png)
![bg left:50%](./images/nishiwaseda3.png)

---

### Blender に転送した様子

![vertical margin-bottom:0](./images/nishiwaseda-blender.png)

---

# 終わり

こういう感じの様々な便利ツールを活用すると色々と楽になるので、どんどん活用して生活を向上させよう！
