# ~~10 億ドルの損失を出すコードを書いていませんか？~~

# 「10 億ドルの損失」招く Kotlin Null Safety の落とし穴

Kotlin は「The Billion-Dollar Mistake」とも呼ばれる Null 参照問題を防ぐために、Null Safety をサポートしています。しかし、完全に安心するにはまだ早いかもしれません。Kotlin でのソフトウェア開発では、未だ Kotlin のみのエコシステムで完結することは難しく、Java（JVM）の資産を活用する場面が多くあり、Java との連携の境界線上には意外な落とし穴があります。本セッションでは、実際のプロジェクトで遭遇した Kotlin の型システムを突破してきた null の問題を共有しつつ、Kotlin と Java の相互運用における Platform Type、Generics、Type Erasure、Deserialization、Reflection などの内容を踏まえ、Kotlin の Null Safety ついて話します!!
