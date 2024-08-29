# OpenData Bridge - オープンデータの加工と共有をシンプルに

# 作品概要
**OpenData Bridge**は、オープンデータの生成、加工、そして共有をサポートするツール群を提供します。  
私達は前回の都知事杯Open Data Hackathon2023で提案した、オープンデータの整形を行うツール群、OpenData Bridgeを複数のプロジェクトに実戦投入してきました。
今回の都知事杯では、その中で見えてきた課題を解消し、自治体によるオープンデータ生成の促進と、目的に応じたデータ加工がもっと簡単に行える環境を整えて行きます。


# 作品のロードマップ
![ロードマップ](odb_roadmap.jpg)

# 作品構成要素
| 構成要素       | 概要                                                                 | 現在の開発状況 | GitHub Repository                              | 実績                              | デモ動画                     |
|----------------|----------------------------------------------------------------------|----------------|-----------------------------------------------|-----------------------------------|------------------------------|
| **ODB-Lab**    | 生成AIのサポートと自治体標準オープンデータセットへの変換に特化したデータ補完機能・テンプレートでデータ整形を実現。 | Web版開発完了,アプリ版企画中         | [CMS](https://github.com/dx-junkyard/opendata-bridge-cms)<br> [frontend](https://github.com/dx-junkyard/opendata-bridge-frontend) <br> [LLM component](https://github.com/dx-junkyard/fast-api-with-open-interpreter) <br> [ODBridge-proxy-api](https://github.com/dx-junkyard/OpenData-Bridge-proxy-api)  | [地方公共団体のオープンデータ取組支援ツールの実現可能性調査](https://www.digital.go.jp/budget/entrustment_deliverables)     | [都知事杯ODH2023DemoDay](https://www.youtube.com/watch?v=GrIohSqZYEY&t=5827s) |
| **ODB-Library**| データ変換のパーツやpipeline定義の登録・共有                               | 自治体ごとの最適化＆事例追加中         | [リンク](https://github.com/example/odb-lib)   | 行政サービスカタログ化PJ（２件）  | [デモ](https://github.com/dx-junkyard/OpenData-Library) |
| **ODB-Pipeline**| データの加工フローを自動化                                          | LLMの組込み試行中    | [ODB-pipeline](https://github.com/dx-junkyard/OpenData-Bridge-pipeline)  | 行政サービスカタログ化PJ（２件）  | [デモ](https://github.com/dx-junkyard/OpenData-Library) |
| **ODB-Archive** | データの加工結果を補完、共有                        | （著作権の問題について検討中）  | [リンク](https://github.com/example/odb-arch)  | （なし）                      | [射水市の人口データ加工結果](https://github.com/dx-junkyard/OpenData-Archive/tree/main/LocalGovData/162116_city_imizu/PopulationData) |


## （前回）都知事杯オープンデータ・ハッカソン2023DemoDay発表資料
- [2024/03/16 動画](https://www.youtube.com/watch?v=GrIohSqZYEY&t=5723s)
- [2024/03/16 資料](20240316.pdf)

## コミュニティ参加のお誘い
dx-junkyardでは、技術共有やコラボレーションを通じて、互いに学び、支援し合うメンバーを募集しています。一緒に創造性と革新性に満ちた社会の実現に貢献しましょう。
[コミュニティ参加はこちらのフォームから](https://forms.gle/PVW4kYYh53SzbfdbA)


## 連絡先
OpenData Bridgeやデモ動画に関するご質問、その他のお問い合わせはこちらからお願いいたします。
[https://www.dx-junkyard.com/](https://www.dx-junkyard.com/)

![メール](em_add.png)


