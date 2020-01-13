# Introduction

## example
exampleより以下の項目を削除し、Introductionに適切な内容を記載して利用してください。

## 本書に関して
本書は要件定義を**『可能な限り』**体系的に行うためのものになります。  
ただ、要件定義自体が定まったフォーマットがないため、これまで@aaaiiuieが業務を行なってきた中でポイントとなる項目をメインに記載いたします。

## 前提
### | マークダウンについて
本書を作成するために使用したツールは**Gitbook**になります。  
そのため、**マークダウンで記述**が前提になります。

### | 本書で扱うテーマ
今回本書の題材として**『システムのリプレース』**をテーマに記載いたします。

本書は企画書ではありません。  
本書では**『システムのリプレースを行う必要がある』**という顧客の要望に対して記載いたします。

既にプロジェクトを実施するという前提のもと、要件定義を実施していることを前提に記載いたします。

### | gitでのバージョン管理
本書はバージョン管理を目的としているため、gitを利用しています。  

## ドキュメントの構成
以下の構成でドキュメントを作成しております。

```
document-example/
├── 0_Introduction // 本書の説明
│   └── image // 本項で使用しするファイル設置場所
├── 1_ProjectCharter // 各項目のフォルダ
│   ├── 1-1_ProjectBackGround.md // プロジェクトの背景
│   ├── 1-2_ProjectTarget.md // プロジェクトの目的
│   ├── 1-3_ProjectScope.md // プロジェクトのスコープ
│   ├── 1-4_ProjectCost.md // プロジェクトの費用
│   ├── 1-5_ProjectSchedule.md // プロジェクトのスケジュール
│   ├── 1-6_ProjectMember.md // プロジェクトのメンバー
│   ├── 1-7_ProjectMeeting.md // プロジェクトの会議体
│   ├── 1-8_ProjectRiskManagement.md // プロジェクトのリスクマネジメント
│   ├── 1-9_ProjectCostManagement.md // プロジェクトのコストマネジメント
│   └── image // 本項で使用しするファイル設置場所
├── 1_ProjectCharter_README.md // プロジェクト憲章の目次 
├── 2_TechnologyRequirement // 各項目のフォルダ
│   ├── 2-1_Requirements.md // 推奨閲覧環境
│   ├── 2-2_LanguageAndMiddleware.md // 言語・ミドルウェア 
│   ├── 2-3_Cooperation.md // 外部システムとの連携
│   └── image // 本項で使用しするファイル設置場所
├── 2_TechnologyRequirement_README.md // 技術要件の目次
├── 3_SystemDesign // 各項目のフォルダ
│   ├── 3-1_SystemConstitution.md // システム構成
│   ├── 3-2_DatabaseDocument.md // データベース定義書
│   ├── 3-3_DirectoryMap.md // ディレクトリマップ
│   ├── 3-4_SiteMap.md // サイトマップ
│   └── image // 本項で使用しするファイル設置場所
├── 3_SystemDesign_README.md // システム設計の目次
├── 4_OperationFlow // 各項目のフォルダ
│   ├── 4-1_Stakeholder.md // ステークホルダー
│   ├── 4-n_example-1.md // ●●業務と●●業務に関するワークフロー1（参考例）
│   ├── 4-n_example-2.md // ●●業務と●●業務に関するワークフロー2（参考例）
│   └── image // 本項で使用しするファイル設置場所
├── 4_OperationFlow_README.md // 業務フローの目次
├── 5_FunctionRequirement // 各項目のフォルダ
│   ├── 5-n_example-1.md // 5.n.example-1(参考例：ログイン)
│   └── image // 本項で使用しするファイル設置場所
├── 5_FunctionRequirement_README.md // 機能要件一覧の目次
├── 6_NonFunctionalRequirement // 各項目のフォルダ
│   ├── 6-1_UsabilityAccessibility.md // ユーザビリティ・アクセシビリティ
│   ├── 6-2_Scalability.md // 規模・機能性
│   ├── 6-3_Function.md // 性能
│   ├── 6-4_Reliablity.md // 信頼性
│   ├── 6-5_Compatibility.md // 上位互換性
│   ├── 6-6_Neutrality.md // システム中立性
│   ├── 6-7_Portability.md // 移行性
│   └── image // 本項で使用しするファイル設置場所
├── 6_NonFunctionalRequirement_README.md // 非機能要件一覧の目次
├── 7_OperationAndMaintenance // 各項目のフォルダ
│   ├── 7-1_Item.md // 運用保守の項目
│   └── 7-2_FunctionDevelopment.md // 追加開発の対応方針
├── 7_OperationAndMaintenance_README.md // 運用保守の目次
├── README.md // 
├── SUMMARY.md // 

```

## 環境
要件定義を行う上で利用しているマシンやツール類について記載いたします。

|no|項目|概要|
|:---:|:---|:---|
|1|マシン|MacBook Pro(macOS Catalina 10.15.2)|
|2|エディタ|Atom（マークダウンをプレビューできればなんでも良い）|
|3|Gitbook|mdファイルをHTMLファイルやPDFに出力するためのツールとして利用するため|
|4|Googleスプレッドシート|マトリックス表の作成のため|
|5|AdobeXD|画面デザインを行うためのソフトとして利用するため|
|6|Zeplin|細かい余白やCSSの出力等に利用するため|
|7|skitch|出力した画像の上に注釈を加えるために利用するため|
|8|keynote|簡易的なグラフを作るため|

## その他
普段本書のバージョン管理は **「プロジェクト管理サービス backlog」** が提供しているリポジトリを利用しています。  
リポジトリ名も課題名とブランチ名が紐づいた形、かつ課題自体がWBSに関係している内容になります。
そのため、githubでの運用に即していない箇所もあるかと思いますが、予めご了承ください。












