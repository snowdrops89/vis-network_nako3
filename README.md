# vis-network_nako3
[vis-network](https://visjs.org/index.html#modules)を使って、なでしこ３でネットワーク図を書くNAKO3プラグイン。

## 使い方
　[なでしこ３貯蔵庫にライブラリとして公開しています。](https://n3s.nadesi.com/show/vis_network)

　プログラム冒頭で取り込みます。

```
！『https://n3s.nadesi.com/plain/vis_network.nako3』を取り込む。
```

　[なでしこ貯蔵庫](https://n3s.nadesi.com/index.php?page=all&action=list)で使う前提で作成したので、最初にvis-networkのCDN取り込み用のスクリプトタグをhtmlのヘッダに埋め込んで取り込み完了待ちしていますが、自前のhtmlで使う場合には当然html側にスクリプトタグを書いた方が早いです。

　`id`に`vis-network`を付けることで、スキップするようにしています。

```
<script id="vis-network" type="text/javascript" src="https://unpkg.com/vis-network/standalone/umd/vis-network.min.js"></script>
```

## テスト

- [一番簡単なテスト](https://snowdrops89.github.io/vis-network_nako3/test/vis_test_0.html)

- [html側でCDN取り込み](https://snowdrops89.github.io/vis-network_nako3/test/vis_test_1.html)
