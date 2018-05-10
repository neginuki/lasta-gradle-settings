lata-gradle-settings
========================

LastaFlute で生成したプロジェクトを gradle プロジェクトに変換する。

目的
---------------

LastaFlute で作成した、プロジェクトを gradle プロジェクトに変換する。  
ここでは、マルチプロジェクトの hangar を変換する設定を公開しています。   
https://github.com/lastaflute/lastaflute-example-maihama


追加要素
------------------------
以下のライブラリを使えるよう追記してます。
+ AssertJ
+ EclipseCollections
+ Laspock


手順
-----------------------------
1. pom.xml を削除する。
2. このプロジェクトのファイルを #change_it_first で検索して、対象プロジェクト用に書き換える。
3. プロジェクトルートに settings.gradle, base に gradle.properties, build.gradle を配置
