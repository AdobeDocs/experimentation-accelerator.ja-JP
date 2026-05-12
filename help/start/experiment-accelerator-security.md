---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer 実験アクセラレーター
description: Journey Optimizer 実験アクセラレーターを使用した AI でのデータ使用
topic: Content Management
role: User
level: Beginner
keywords: コンテンツ, 実験, 複数, オーディエンス, 処理
TQID: https://experienceleague.adobe.com/FaQ5-cPzhnIplEoL1HwVh390jot-EA8G5u6JP8CVneI
product_v2:
  - id: cb954087-f4fc-4456-afb9-e939cabcdc79
feature_v2:
  - id: b3538224-471e-4c63-a444-9b19d89ae29c
  - id: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04
  - id: dc22c819-3f29-4e91-8b7d-5c6719831141
subfeature_v2:
  - id: fb9a80eb-bebc-492f-a0e9-584595621ebb
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2:
  - id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
  - id: bcc5edb5-84c3-4940-9f84-ed88b6c16274
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
  - id: eb30f47f-d87a-400f-8f78-63ce7979ff56
source-git-commit: 659a4723ac8b7cbaf3ea06c34107bf876612ccb4
workflow-type: tm+mt
source-wordcount: 441
ht-degree: 100%

---

# Journey Optimizer 実験アクセラレーターを使用した AI でのデータ使用{#experiment-accelerator-security}

**Adobe Journey Optimizer 実験アクセラレーター**&#x200B;を使用すると、自動的にインサイトを検出し、実験や実験プログラムを改善する機会を推奨できます。 ソリューションでは、AI と機械学習を活用して、これらのレコメンデーションを提供します。 このステートメントでは、**Journey Optimizer 実験アクセラレーター**&#x200B;での顧客データの使用方法を明確にします。

## Journey Optimizer 実験アクセラレーターが使用するデータは何ですか？

現在、**Journey Optimizer 実験アクセラレーター**&#x200B;で使用されるデータには、次の 3 つのタイプがあります。

* **実験メタデータ**：実験名、実験に使用されるオーディエンスの定義、実験の処理（例：名前、分割率、実験の提供先の場所やサーフェス）。

* **処理のパフォーマンス**：各処理の人数、成功指標の平均、標準偏差。

* **処理の内容**：Web サイト上でユーザーに表示される、処理のレンダリングされた HTML とスクリーンショット。

## Journey Optimizer 実験アクセラレーターは、このデータをどのように活用しますか？

**Journey Optimizer 実験アクセラレーター**&#x200B;は、各処理のコンテンツを取得し、埋め込み（例：コンテンツの数学的表現）を作成して、これらの埋め込みを処理のパフォーマンスと相関させます。 このプロセスにより、今後の使用に最適なコンテンツ属性を抽出できます。 これらの属性は、アドビがホストする大規模言語モデルに送られ、人間が読み取れる形式のステートメントに変換されて、インサイトを生成し、機会を提案するのに使用されます。

## Journey Optimizer 実験アクセラレーターでは、使用されるデータに対してどのような制限がありますか？

各顧客は、特定の組織とサンドボックスに割り当てられています。 サンドボックスごとに専用モデルのトレーニングが実施されます。 サンドボックスを削除すると、関連するすべてのデータ、シグナルおよびモデルが完全に削除されます。

* お客様データは、その顧客からのモデルのトレーニングや微調整にのみ使用します。

* モデルのトレーニングや微調整を行う際に、複数の顧客を混在させることはありません。

## アドビのモデルや AI はブランドのユーザーエクスペリエンスを自動的に変更しますか？

いいえ。 **Journey Optimizer 実験アクセラレーター**&#x200B;は、変更対象とその変更方法に関してのみレコメンデーションを行います。 Journey Optimizer や Target を使用してエクスペリエンスを変更する権限を持つユーザーのみが、これらのレコメンデーションに基づいてアクションを実行できます。 すべてのレコメンデーションは、プッシュする前に確認および編集できます。

## データやシステムの安定性にリスクはありますか？

**Journey Optimizer 実験アクセラレーター**&#x200B;は、データを取り込んで分析し、今後のテストに関するインサイトとレコメンデーションを生成するだけです。 テスト設定を変更するアクセス権はありません。 ツール内で生成されたすべての提案は、実装に Target と Journey Optimizer に送信され、顧客の現在のアクティビティに影響を与えないことが確保されます。
