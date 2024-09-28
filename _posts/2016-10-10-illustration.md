---
layout: post
title: "illustration"
author: ""
categories: illustration
tags: [documentation,sample]
---
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ブログリンク集</title>
    <style>
         .link-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .link-item {
            width: calc(33.33% - 30px); /* 余白を差し引いて計算 */
            margin: 2px;
            text-align: center;
        }
        .post-date {
            display: none;
        }
        .link-item img {
            width: 100%;
            height: 200px; /* 高さを固定 */
            object-fit: cover; /* アスペクト比を維持しつつ、画像の中央を表示 */
            border-radius: 10px;
            transition: transform 0.3s ease; /* ズームのトランジションを設定 */
        }
        .link-item img:hover {
            transform: scale(1.1); /* カーソルを合わせたときに1.1倍にズーム */
        }
        .link-item a {
            text-decoration: none;
            color: #0099e6;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <h1>関連記事</h1>
    <div class="link-container">
        <div class="link-item">
            <a href="{{ site.baseurl }}/illust1">
                <img src="{{ site.github.url }}/assets/img/sannbika_2-1.jpg" alt="讃美歌">
                <p>讃美歌</p>
            </a>
        </div>
        <div class="link-item">
            <a href="{{ site.baseurl }}/illust1">
                <img src="{{ site.github.url }}/assets/img/pri_1.jpg" alt="ファンアート">
                <p>異邦</p>
            </a>
        </div>
        <div class="link-item">
            <a href="{{ site.baseurl }}/illust2">
                <img src="{{ site.github.url }}/assets/img/cuba-1.jpg" alt="リンク3の画像">
                <p>TBD</p>
            </a>
        </div>
        <div class="link-item">
            <a href="{{ site.baseurl }}/illust2">
                <img src="{{ site.github.url }}/assets/img/cuba-1.jpg" alt="リンク3の画像">
                <p>TBD</p>
            </a>
        </div>
    </div>

</body>
</html>


