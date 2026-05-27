---
solution: Journey Optimizer
product: journey optimizer
title: Journey Optimizer 実験アクセラレーター
description: 効果的に実験を行い、インサイトを生成する処理能力を向上させます
topic: Content Management
role: User
level: Beginner
keywords: コンテンツ, 実験, 複数, オーディエンス, 処理
TQID: https://experienceleague.adobe.com/nCmogRT9JCTYK7VjfO-MNjz8lnDkRsaeCiZL4bIy0RQ
product_v2: id: cb954087-f4fc-4456-afb9-e939cabcdc79
feature_v2: id: b3538224-471e-4c63-a444-9b19d89ae29cid: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04id: d998adac-2f81-400b-a669-d07bb196e4ebid: dc22c819-3f29-4e91-8b7d-5c6719831141id: fe338112-e2ce-4876-8989-fc4d497613f1
subfeature_v2: id: fb9a80eb-bebc-492f-a0e9-584595621ebb
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2: id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2: id: bcc5edb5-84c3-4940-9f84-ed88b6c16274id: d095671a-1355-40aa-8b5f-06c33c68080bid: e1e0219c-f879-479f-8427-888ed2a6e9c2
source-git-commit: 659a4723ac8b7cbaf3ea06c34107bf876612ccb4
workflow-type: tm+mt
source-wordcount: 507
ht-degree: 100%

---

# Journey Optimizer 実験アクセラレーターへのアクセス

[実験を作成および設定](https://experienceleague.adobe.com/ja/docs/journey-optimizer/using/content-management/content-experiment/content-experiment)し、キャンペーンまたはジャーニーをプロファイルに送信した後、**[!UICONTROL Journey Optimizer 実験アクセラレーター]**&#x200B;にアクセスして、実験のパフォーマンスをより深く掘り下げることができます。

**[!UICONTROL Journey Optimizer 実験アクセラレーター]**&#x200B;には、[!UICONTROL 実験]ドロップダウンの左側のメニューから、またはアプリスイッチャーからアクセスできます。 Target ライセンスのみを持つユーザーは、アプリスイッチャーを通じてのみアクセスできます。

![](assets/access.png)

使用可能な実験は、設定によって異なります。

* **Adobe Journey Optimizer ユーザーの場合**：有効にした組織のサンドボックスで設定した実験は自動的に含まれます。

* **Journey Optimizer を使用している Adobe Target ユーザーの場合**：Target の任意の A/B アクティビティは、Journey Optimizer の本番稼働用サンドボックス内の **[!UICONTROL Journey Optimizer 実験アクセラレーター]**&#x200B;に表示されます。

* **Adobe Target のみのユーザーの場合**：Target 組織内のすべての A/B アクティビティは、Journey Optimizer の本番稼働用サンドボックスに含まれます。

**[!UICONTROL Journey Optimizer 実験アクセラレーター]**&#x200B;を使用するには、サンドボックスにアクセスし、関連する権限に従う必要があります。

* **[!UICONTROL 実験を表示]**
* **[!UICONTROL 実験メタデータを管理]**

+++ Adobe Experience Platform または Adobe Journey Optimizer ライセンスを使用して、実験関連の権限を割り当てる方法について説明します

1. **[!DNL Permissions]** 製品で、「**[!UICONTROL 役割]**」タブに移動し、目的の「**[!UICONTROL 役割]**」を選択します。

1. 「**[!UICONTROL 編集]**」をクリックして、権限を変更します。

1. **[!UICONTROL 実験アクセラレーター]**&#x200B;のリソースを追加し、ドロップダウンメニューから「**[!UICONTROL 実験を表示]**」または「**[!UICONTROL 実験メタデータを管理]**」を選択します。

   ![](assets/permissions-experiment.png)

1. 「**[!UICONTROL 保存]**」をクリックして、変更を適用します。

この役割に既に割り当てられているユーザーの権限は、自動的に更新されます。

この役割を新しいユーザーに割り当てるには：

1. 役割ダッシュボード内の「**[!UICONTROL ユーザー]**」タブに移動し、「**[!UICONTROL ユーザーを追加]**」をクリックします。

1. ユーザーの名前、メールアドレスを入力するか、リストから選択して、「**[!UICONTROL 保存]**」をクリックします。

   まだユーザーを作成していない場合は、[このドキュメント](https://experienceleague.adobe.com/ja/docs/experience-platform/access-control/abac/permissions-ui/users)を参照してください。

ユーザーは、インスタンスにアクセスする手順が記載されたメールを受信します。

+++

</br>

+++ Adobe Target ライセンスを使用して、実験関連の権限を割り当てる方法について説明します

1. **[Admin Console](http://adminconsole.adobe.com/)** を開きます。

1. **[!UICONTROL 製品]**&#x200B;で、「**[!UICONTROL Adobe Experience Platform]**」を選択します。

1. 「**[!UICONTROL 新規プロファイル]**」をクリックします。

   ![](assets/permission-target.png)

1. プロファイルの&#x200B;**[!UICONTROL 名前]**&#x200B;と&#x200B;**[!UICONTROL 説明]**&#x200B;を入力し、「**[!UICONTROL 保存]**」をクリックします。

1. 新しく作成した&#x200B;**[!UICONTROL プロファイル]**&#x200B;を開き、「**[!UICONTROL 権限]**」タブに移動します。

1. **[!UICONTROL experimentation-accelerator]** 権限の横にある ![](assets/do-not-localize/Smock_Edit_18_N.svg) をクリックします。

   ![](assets/permission-target-1.png)

1. **[!UICONTROL 実験を表示]**&#x200B;や&#x200B;**[!UICONTROL 実験メタデータを管理]**&#x200B;など、このプロファイルに必要な権限を追加し、「**[!UICONTROL 保存]**」をクリックします。

   >[!TIP]
   >
   > ユーザーが異なるアクセスレベルを必要とする場合は、個別のプロファイルを作成します。 例えば、**[!UICONTROL 実験を表示]**&#x200B;のみを使用する **[!UICONTROL Experimentation Accelerator ビューア]**&#x200B;プロファイルと、**[!UICONTROL 実験を表示]**&#x200B;および&#x200B;**[!UICONTROL 実験メタデータを管理]**&#x200B;の両方を使用する **[!UICONTROL Experimentation Accelerator エディター]**&#x200B;プロファイルを作成します。

   ![](assets/permission-target-2.png)

1. 「**[!UICONTROL 権限]**」タブから、「**[!UICONTROL サンドボックス]**」を選択します。

1. ユーザーが Journey Optimizer Experimentation Accelerator を使用できるサンドボックスを追加し、「**[!UICONTROL 保存]**」をクリックします。

1. 「**[!UICONTROL ユーザー]**」タブを開き、「**[!UICONTROL ユーザーを追加]**」をクリックします。

   ![](assets/permission-target-3.png)

1. このアクセス権を受け取るユーザーを追加し、「**[!UICONTROL 保存]**」をクリックします。

このプロファイルに追加されたユーザーは、アプリスイッチャーから Journey Optimizer Experimentation Accelerator にアクセスできるようになりました。

+++


<!--
table style="table-layout:fixed"><tr style="border: 0;">
<td><img alt="Overview" href="experiment-accelerator-overview.md" src="assets/do-not-localize/experiments-2.jpeg">
<div align="center"><p><strong><a href="experiment-accelerator-overview.md">Overview</a></strong></p></div></td>
<td><img alt="Experiments" href="experiment-accelerator-monitor.md" src="assets/do-not-localize/experiment-overview.jpeg">
<div align="center"><p><strong><a href="experiment-accelerator-monitor.md">Experiments</a></strong></p></div></td>
<td><img alt="Metrics" href="experiment-accelerator-metrics.md" src="assets/do-not-localize/experiment-metrics.png">
<div align="center"><p><strong><a href="experiment-accelerator-metrics.md">Metrics</a></strong></p></div></td>
</tr></table
-->
