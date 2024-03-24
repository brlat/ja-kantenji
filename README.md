# ja-kantenji
Japanese braille Kantenji tables for Liblouis

Githubの使い方も忘れてしまっているので、練習でまずここで編集してから、Liblouisのフォークを編集使用と思います。

## Liblouisにマージしてもらえるようにするために必要なこと

Liblouisのメーリングリストで以前質問した時にもらった条件です。

1. It must be clear which braille code is implemented. This is done by including the necessary comments with a description of the braille code and/or hyperlinks to web pages that describe it. If official specifications and braille authorities exist these should be referenced for sure. But manuals, introduction pages, Wikipedia pages etc. are also useful.
2. The second point is related to the first: there are a number of required metadata fields (special comments) a table must have. Just like the first point it must make it clear which braille code is implemented, but in machine readable form rather than plain language.
3. Tables must be backed by test data, which is used to validate the table after every change to the table itself or to the Liblouis source code. The test data is the contract that warrants a correct behavior of Liblouis. The table itself should be seen as the implementation of the contract. Ideally the tests are also constructed in such a way that it makes them suitable as documentation about the braille code. But a dictionary style is also permitted. You may choose how much effort you put in the test data. Obviously the better the tests are the more comfort you will have that Liblouis will always keep behaving correctly.

テーブルファイルを作ってからpull requestするまでの流れは下記のwikiに書かれています。

- [Liblouis - How to contribute](https://github.com/liblouis/liblouis/wiki/How-to-contribute)



