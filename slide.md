---
marp: true
theme: default
header: "とにかく楽したい"
footer: "by 4418"

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

        border: 1px dashed gray; /* debug */
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

# とにかく楽して自主制作

## 何も考えたくない

<!--
_color: white
_footer: 'Photo by Earl Lasala on Unsplash'
-->

![bg brightness:0.4](https://unsplash.com/photos/xFjti9rYILo/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8MXx8bWFjaGluZXx8MHx8fHwxNjM4MzI1NTA1&force=true)

---

## 何か作れと言われても

-   何を作ればいいかわからん
-   どうやって作ればいいのかわからん
-   調べ方わからん

-   **めんどい**

<!--
_footer: '©︎ 4418'
-->

![bg left:45%](https://unsplash.com/photos/1SAnrIxw5OY/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8NHx8c2ltcGxlJTIwd29ya3x8MHx8fHwxNjM4MzQ2OTQy&force=true)

---

## とにかく楽して終わらせるために

必要なポイント

-   何がどう言うふうに作れるか知る
-   便利なツールを知る
-   省ける作業は省く
-   苦しいことは避ける

<!--
_footer: '©︎ 4418'
-->

![bg left:40%](https://unsplash.com/photos/w6ftFbPCs9I/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8MXx8c291cHx8MHx8fHwxNjM4MzIxMjY1&force=true)

---

## 自主制作の例

**制限 Mac でできる、現実的なもの**

-   イラストやデザイン制作
-   画像編集
-   動画編集(ちょっとめんどい)
-   Web 制作(ちょっとめんどい)
-   音楽制作(ちょっとめんどい)

**やろうと思えばできるけど非現実的なやつ**

-   プログラミング
-   3D CG 制作

<!--
_footer: '©︎ 4418'
-->

![bg left:40%](https://unsplash.com/photos/jsgJtBOR6jY/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8MXx8Y3JlcGV8fDB8fHx8MTYzODM0MTY4OQ&force=true)

---

## イラストやデザインに便利なツール

**Figma**
Adobe 系と異なり、**無料**で使える。
Web 上で使えるので、制限 Mac でも Windows でも使える。

<!--
_footer: '©︎ 4418'
-->

![bg left:40%](./figma.png)

---

## イラストを楽して作りたい

**Photoshop**
さすが Adobe といえるような高度な機能が付いている。
(制限 Mac でやるのはスペック的におすすめしないが。)

<br>
Adobe Photoshop 2022の新機能を使って芸術作品を生成する。

<!--
_footer: '©︎ 4418'
-->

![bg left:40%](./photoshop.png)

---

## 音楽を作りたいけど

何を参考にすればわからないという時

**SoundQuest**と言うサイトが便利。**無料**

<!-- ここ -->
<!-- https://soundquest.jp/about/ -->

<!--
_footer: '©︎ 4418'
-->

![bg left:40%](./soundquest.png)

---

## もしプログラミングがしたければ

制限 Mac ですぐに使うことができる言語は

-   Python
-   Ruby

のみで、他の言語を使いたいというときはかなり面倒になる。

Python でやるおすすめのやつ

-   **LINE の BOT**

![bg left:40%](https://unsplash.com/photos/vpOeXr5wmR4/download?ixid=MnwxMjA3fDB8MXxzZWFyY2h8MXx8cHJvZ3JhbW1pbmd8fDB8fHx8MTYzODMzOTE3Mg&force=true)

---

## 3D モデル作りたいけど...

**Blender**というソフトを使うのが一番手軽だが、制限 Mac に入れるのは少々面倒。
(ICT に行けば多分入れてくれる。)

Blender の使い方は YouTube で調べれば大量に出てくるのでそれを見ればどうにかなる。

![bg left:40%](./blender.png)

---

## 3D モデルを
