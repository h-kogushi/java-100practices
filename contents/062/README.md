[目次](../toc.md)
[前の問題](../061/README.md)　[次の問題](../063/README.md)


***
## 062：複合(2)
* 以下の要件を満たすプログラムを実装せよ。
    * 任意のデータを格納することができるクラス。
    * データは、キーバリュー形式で管理し、最大100個格納できる（＝登録できるキーの数が最大100個）。
    * また、すでに挿入されているものと同じキーでデータを挿入した場合は、既存のデータを上書きする。
    * 任意のタイミングでデータの挿入・取得ができる。
    * 101個目に相当するデータを挿入した場合は、"最も長く利用されていないもの"を削除した上で挿入する。
    * 一度格納したデータは、上記の個数の上限に達したことによる削除、または同じキーでデータを上書きしない限り、常に残り続ける。
    * 単純な挿入・取得処理では、入れたデータは消えない。また、同じデータを２回以上取り出すこともできる。

