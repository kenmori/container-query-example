# container-query-example

[Edit in StackBlitz next generation editor ⚡️](https://stackblitz.com/~/github.com/kenmori/container-query-example)


## container queryを書けるようにする

WIP


- inline-size。コンテナの幅に対してスタイルを適用することを意味する
- 高さに基づきたい場合は size
- container自身にpaddingを持たせない
- 空白をつける
- conainer指定したらその中のものは子孫要素を定義する。ないものを定義しても適用されない

相対的な値設定
2.57cqi・・・コンテナのインラインサイズの2.57パーセント 
cqb・・・コンテナのブロックサイズ
cqw・・・コンテナのwidth
cqh・・・コンテナのhight

- container: my-container / inline-size;

参照
- https://developer.mozilla.org/ja/docs/Web/CSS/CSS_containment/Container_queries
- https://blog.logrocket.com/css-container-queries-guide/
- https://blog.logrocket.com/new-css-style-queries/#issues-style-queries
- https://www.youtube.com/watch?v=CHKUFsnABw4
- https://web.dev/articles/new-responsive?hl=ja
- https://codepen.io/kenjimorita/pen/KKYBwOq