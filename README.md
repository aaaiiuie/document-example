# Introduction

## example
exampleより以下の項目を削除し、Introductionに適切な内容を記載して利用してください。

## 本書に関して
本書は要件定義を**『可能な限り』**体系的に行うためのものになります。  
ただ、要件定義自体が定まったフォーマットがないため、これまで@arakaki.mitsuhideが業務を行なってきた中でポイントとなる項目をメインに記載いたします。

## 前提
### | マークダウンについて
本書を作成するために使用したツールは**Gitbook**になります。  
そのため、**マークダウンで記述**が前提になります。

### | 本書で扱うテーマ
今回本書の題材として**『システムのリプレース』**をテーマに記載いたします。

本書は企画書ではありません。  
本書では**『システムのリプレースを行う必要がある』**という顧客の要望に対して記載いたします。

既にプロジェクトを実施するという前提のもと、要件定義を実施していることを前提に記載いたします。

## 応用
本書は**バージョン管理をすること**に重きを置いています。  
そのため、**gitを用いたバージョン管理**を想定して記載しております。

## ドキュメントの構成
以下の構成でドキュメントを作成しております。

```
document-example/
├── 0_Introduction
│   └── image
│       ├── fontawesome-download.png
│       ├── fontawesome.png
│       └── gitbook.png
├── 1_ProjectCharter
│   ├── 1-1_ProjectBackGround.md
│   ├── 1-2_ProjectTarget.md
│   ├── 1-3_ProjectScope.md
│   ├── 1-4_ProjectCost.md
│   ├── 1-5_ProjectSchedule.md
│   ├── 1-6_ProjectMember.md
│   ├── 1-7_ProjectMeeting.md
│   ├── 1-8_ProjectRiskManagement.md
│   ├── 1-9_ProjectCostManagement.md
│   └── image
│       ├── 1.jpg
│       ├── member.key
│       ├── member.png
│       ├── square1.svg
│       └── square2.svg
├── 1_ProjectCharter_README.md
├── 2_TechnologyRequirement
│   ├── 2-1_Requirements.md
│   ├── 2-2_LanguageAndMiddleware.md
│   ├── 2-3_Cooperation.md
│   └── image
│       ├── 3721_640_auto.png
│       ├── flow-2.png
│       └── flow.png
├── 2_TechnologyRequirement_README.md
├── 3_SystemDesign
│   ├── 3-1_SystemConstitution.md
│   ├── 3-2_DatabaseDocument.md
│   ├── 3-3_DirectoryMap.md
│   ├── 3-4_SiteMap.md
│   └── image
│       ├── element.png
│       ├── schema.png
│       ├── sitemap.png
│       └── structureimage.png
├── 3_SystemDesign_README.md
├── 4_OperationFlow
│   ├── 4-1_Stakeholder.md
│   ├── 4-n_example-1.md
│   ├── 4-n_example-n.md
│   └── image
│       ├── workflow.png
│       ├── workflow2.png
│       ├── workflow3.png
│       └── workflow4.png
├── 4_OperationFlow_README.md
├── 5_FunctionRequirement
│   ├── 5-n_example-1.md
│   ├── 5-n_example-1cp.md
│   └── image
│       ├── ds-rc-000-0001-2.png
│       ├── ds-rc-000-0001.png
│       ├── rc-000-0001-2.png
│       ├── rc-000-0001.png
│       ├── rc-000-0002.png
│       ├── rc-000-0003.png
│       ├── rc-000-0004-2.png
│       ├── rc-000-0004-3.png
│       ├── rc-000-0004.png
│       ├── rc-000-0005.png
│       ├── rc-000-007-validation.png
│       ├── rc-000-007.png
│       ├── rc-000-008.png
│       └── rc-000-009.png
├── 5_FunctionRequirement_README.md
├── 6_NonFunctionalRequirement
│   ├── 6-1_UsabilityAccessibility.md
│   ├── 6-2_Scalability.md
│   ├── 6-3_Function.md
│   ├── 6-4_Reliablity.md
│   ├── 6-5_Compatibility.md
│   ├── 6-6_Neutrality.md
│   ├── 6-7_Portability.md
│   ├── 6-n_example-n.md
│   └── image
│       └── portability.png
├── 6_NonFunctionalRequirement_README.md
├── 7_Designguideline
│   ├── 7-1_MaterialComponent.md
│   ├── 7-n_example-1.md
│   └── 7-n_example-n.md
├── 7_Designguideline_README.md
├── 8_OperationAndMaintenance
│   ├── 8-1_Incident.md
│   └── 8-2_FunctionDevelopment.md
├── 8_OperationAndMaintenance_README.md
├── 9_Glossary
│   └── 9-1_Glossary.md
├── 9_Glossary_README.md

```

## 環境
要件定義を行う上で利用しているマシンやツール類について記載いたします。

|no|項目|概要|
|:---:|:---|:---|
|1|マシン|MacBook Pro(macOS Catalina 10.15.2)|
|2|エディタ|Atom（マークダウンをプレビューできればなんでも良い）|
|3|Gitbook|mdファイルをHTMLファイルやPDFに出力するためのツールとして利用|
|4|Googleスプレッドシート|マトリックス表の作成|
|5|AdobeXD|画面デザインを行うためのソフトとして利用|
|6|Zeplin|細かい余白やCSSの出力等に利用|
|7|skitch|出力した画像の上に注釈を加えるために利用|













