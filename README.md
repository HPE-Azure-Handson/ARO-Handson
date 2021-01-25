# Azure Red Hat OpenShift （ARO）の概要　～ハンズオン～
このハンズオンでは、1日間でAzure Red Hat OpenShift（以下、ARO）の基礎知識を学びます。

## Day1
|  No  |  項目  |　内容 |時間|
| ---- | ---- | ---- |---- |
| 1 |  AROのセットアップ  | - 環境の概要説明<br>- 環境準備（VNET作成等）<br>- ARO作成コマンド実行<br>- 初期環境設定（認証など）  | 1時間 |
| 2 |  <講義>  | AROの概要<br> - AROテクニカル・リファレンス、AROのメリット、AKSとの違い、機能、課金体系など<br> - (option) OpenShiftの概要  | 1時間 |
| 3 |  <講義>  | ハンズオンの説明と環境<br> - 環境構成の説明<br> - リソース、コンポ―ネントの説明<br> -  実施項目概要とゴールの説明 | 30分 |
| ～ | 【休憩】|～|～|
| 4 |  ARO環境へのログイン  | - ARO環境へのログイン（CLI, GUI）<br> - 環境構成の確認<br> -  リソース利用状況の確認（CLI, GUI） | 30分 |
| 5 |  イメージデプロイとアクセス  |  - コンテナイメージデプロイ<br> - ソースからのビルド機能<br> -  Podへのアクセス方法 | 30分 |
| 6 | Azure環境の確認 | Azure環境の確認（Azure PortalとOpenShift GUIの関連など） | 30分 |
| ～ | Q&A|まとめとＱ＆Ａ|30分|

※Day1で終了する場合は最後に「99.環境の削除」を行ってARO環境を削除してください。

## Day2
|  No  |  項目  |　内容 |時間|
| ---- | ---- | ---- |---- |
| 7 | Operatorの概要 | - サンプルOperatorのデプロイ |30分 |
| 8 | 運用管理機能の概要 | - Cluster Monitoring<BR> - Cluster Logging |30分 |
| ～ | 【休憩】|～|～|
| 9 | CI/CDパイプラインの実践 | - TechReference#6をベースにサマリコンテンツを体験 |30分 |
| 10 | (option)AzureAD連携による認証 | TBD |30分 |
| 11 | (option)Azure関連PaaSとの連携 | TBD |30分 |
| 12 | (option)スケールアウト | ①-1.Podのスケールアウト/手動<br>①-2.Podのスケールアウト/自動<br>②-1.ノードのスケールアウト/手動<br>②-2.ノードのスケールアウト/自動 |90分 |
| 13 | (option)ストレージの作成 | Azureディスクをマウント |30分 |
| 99 | 環境の削除 | AROの削除 |30分 |
| ～ | Q&A|まとめとＱ＆Ａ|30分|


## 事前準備、前提
- 事前に、ご自身でAzure Subscriptionを準備していただく必要があります。
- 前提
  - k8s概要知識、OpenShift概要知識、Azure概要知識を持っている
  - Linux OS/bashの基礎知識を持っている（簡単な操作は可能）

## 実施側事前準備・実施前提
- ハンズオンコンテンツの準備、（必要に応じてカスタマイズ）
- リモート実施の場合、リモート会議のセットアップ、事前確認
- 可能であれば実施日前に環境へのアクセス確認
- ハンズオンでは短期間で概要を理解する目的をふまえPrivate構成では行わない

