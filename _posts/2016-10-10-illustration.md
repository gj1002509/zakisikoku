---
layout: post
title: "illustration"
author: ""
categories: illustration
tags: [documentation,sample]
---

<!DOCTYPE html>
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
            margin: 15px;
            text-align: center;
        }
        .link-item img {
            width: 100%;
            height: 200px; /* 高さを固定 */
            object-fit: cover; /* アスペクト比を維持しつつ、画像の中央を表示 */
            border-radius: 10px;
        }
        .link-item a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <h1>関連記事</h1>
    <div class="link-container">
        <div class="link-item">
            <a href="{{ site.baseurl }}/sono1">
                <img src="{{ site.github.url }}/assets/img/yuri1.png" alt="リンク1の画像">
                <p>リンクの説明1</p>
            </a>
        </div>
        <div class="link-item">
            <a href="{{ site.baseurl }}/illust1">
                <img src="{{ site.github.url }}/assets/img/city-1.jpg" alt="リンク2の画像">
                <p>リンクの説明2</p>
            </a>
        </div>
        <div class="link-item">
            <a href="{{ site.baseurl }}/illust1">
                <img src="{{ site.github.url }}/assets/img/cuba-1.jpg" alt="リンク3の画像">
                <p>リンクの説明3</p>
            </a>
        </div>
    </div>

</body>
</html>


