# globals.d.ts

我々は、[projects](./)を見ていく中で、ファイルベースのモジュールを使い、グローバル名前空間の汚染を避けることを推奨しました。そのときに、グローバルモジュールとファイルモジュールについて取り上げました。

しかしながら、もし初心者のTypeScriptの開発者がいる場合は、彼らにglobals.d.tsファイルを渡し、グローバルな名前空間にインターフェース/型を宣言することにより、あなたのすべてのTypeScriptコードにおいて、それらの型を魔法のように簡単に利用可能にすることができます。

> JavaScriptを生成するコードについてはすべて、ファイルモジュールを使うことを強くお勧めします

* `globals.d.ts`は、必要に応じて`lib.d.ts`を拡張するのに最適です
* JSからTSに移行している時に、簡単に`declare module "定義ファイルが存在しなくても構わない何かのライブラリ";`とするのは便利な手段です

