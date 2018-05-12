lasta-gradle-settings
========================
[LastaFlute](http://dbflute.seasar.org/ja/lastaflute/ "LastaFlute") プロジェクトを gradle プロジェクトに変換するための gradle ファイルを提供します。      
(マルチプロジェクトの hangar を変換する設定を公開しています。その他はよしなに微調整を)


追加要素
------------------------
以下のライブラリを使えるよう追記しています。
+ AssertJ
+ EclipseCollections
+ Laspock


手順
-----------------------------
0. [LastaFlute(hangar)](https://github.com/lastaflute/lastaflute-example-maihama "hangar") から LastaFlute [公式の手順](http://dbflute.seasar.org/ja/lastaflute/howto/startup/multi.html#howto "手順")で目的のプロジェクトを作成。（この時点では maven プロジェクト）
1. 全ての pom.xml を削除する。
2. このプロジェクトのファイルを #change_it_first で検索して、0で生成したプロジェクト用に書き換える。
3. プロジェクトルートに settings.gradle, base に gradle.properties, build.gradle を配置
