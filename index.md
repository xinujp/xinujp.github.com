---
layout: page
title: xinu.jp
tagline: some trivial matters
---
{% include JB/setup %}

### こんなテーマで
#### インターネットやソフト開発など  
仕事がら、この辺のチップスが多くなりそうです。  
ちなみに Unix 大好きです。Windows 大嫌いです。
#### 地味に難しいブルースハープ  
ブルースハープ(10holes)って、かなり難しいです。  
それも、ピアノやバイオリンのように見るからに難しいのではなく、カンタンそうに見えて難しい。  
地味に難しいブルースハープに、はまってます。
#### その他もろもろ  
blog 的な使い方が主なので、なんでもありです。

### それほど役に立たないメモサイト
いろいろと情報を集めて、備忘録的に書き込んでゆこうと思います。  
あくまで自分用の情報なので、他の人にはあまり役に立たないかも。

### ついでに markdown + Jekyll-Bootstrap のテスト
このサイトは Jekyll-Bootstrap で作成しています。  
Jekyll-Bootstrap は初めて使うので、当面、そのテストも行います。  
また、更についでに、github にも載せようかと。

### 最近の投稿

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
