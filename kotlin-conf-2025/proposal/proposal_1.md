
タイトル： 大規模レガシーに挑む「-1→1」のKotlinマイクロサービス開発

概要：
サービスのスケールに伴い負債を抱えた大規模なレガシーシステムでは、マイクロサービスの新規開発は0→1ではなく、負債を精算しつつ進める-1→1の開発です。
本セッションでは、共有DB、分解ではなく分散してしまったマイクロサービス群によって複雑化した環境での新規マイクロサービスの立ち上げにKotlinを採用し、
・data/value classを用いた効率的なドメインモデリングでのDDD
・copy()のvisibilityなどKotlinが持つ課題、また成長方向を見据えてのイミュータブルを軸にしたプログラミング
・Gradle Kotlin DSLによるマルチプロジェクトなクリーンアーキテクチャ
・マイクロサービス間の結合度合いを意識した段階的データ洗浄フローのアプリケーション実装
を通じて、Kotlinをなぜ選定したかどう活用したか、そして負債を解消する具体手法と知見を共有します。