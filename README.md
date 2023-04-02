# ポートフォリオ

## 自己紹介

インフラエンジニアを21年経験しております。

メインはサーバエンジニアですが、今後フルスタックエンジニアを目指し、
クラウド/バックエンド/フロント領域に関する個人開発/技術記事投稿を行っています。

## 経歴：

エンジニア歴21年

テストエンジニア　4年
* 携帯電話基地局のSWブラックボックステストメイン

社内SE　7年
* 社内サーバ運用/管理担当として、オンプレ/仮想化サーバ80台近くの管理を担当
* Access+SQLServerシステムから、PHP/jQuery+SQLServerへのリプレース実施

インフラ(サーバー)エンジニア　10年
* オンプレ(HP-UX/Solaris)3年
* 仮想化(VMware/Windows/Linux)5年
* クラウド(AWS)2年
* フェーズとしては設計/構築がメイン
  - 直近の案件にてオンプレからクラウドへのリプレース提案〜リリースも実施。

## スキルセット(業務経験)

* **バックエンド**: Ruby on Rails, PHP, Laravel
* **データベース**: MySQL, PostgreSQL, Oracle, SQLServer
* **デプロイメント**: AWS, Docker
* **バージョン管理**: Git, backlog
* **OS**: Linux(RHEL), Windows

## スキルセット(個人開発/技術記事作成)

[qiitaリンク](https://qiita.com/naritomo08/)
[GitHubリンク](https://github.com/naritomo08/)

* **フロントエンド**: React, Vue
* **バックエンド**: python, Elixir, Phoenix, Ruby on Rails, PHP, Laravel
* **データベース**: MySQL, PostgreSQL
* **デプロイメント**: AWS, Azure, GCP, Docker
* **バージョン管理**: Git, GitHub
* **その他ツール**: Lambda, APIGateway, Route53, ACM(SSH生成), ECS, ECR, ALB,
                  CI/CD(GitHubActioins), Terraform(Azure/AWS/GCP)

## 業務経験

### プロジェクト1: 社内システム管理
- 概要: 社内サーバ運用/管理担当として、オンプレ/仮想化サーバ80台近くの管理を担当
- 役割: サーバ運用チームリーダーを担当
- 使用技術: Windows/Linux/VMware/ZABBIX
- 成果: システムの運用に関わる立ち上げ〜リプレースまでのサイクルに関わる業務を実施。

### プロジェクト2: 社内システムリプレース(アプリ更改)
- 概要: Access+SQLServerで構成されたシステムのWeb化を実施
- 役割: 技術選定〜設計〜開発〜運用
- 使用技術: SQLServer/Access/PHP/jQuery/IIS/Windows
- 成果: アプリケーションリプレースに関わる顧客折衝/アプリリプレース技術の習得

### プロジェクト3: 社内システムリプレース(オンプレ→クラウド更改)
- 概要: オンプレ稼働サーバのクラウド(AWS)へのリプレース
- 役割: 技術選定〜提案〜設計〜構築〜運用
- 使用技術: AWS(EC2,DirectConnect,TransitGateway,VPC),Windows(AD)
- 成果: サーバリプレースに関わる顧客折衝/サーバーリプレース技術の習得

## 個人開発/技術記事作成

### 記事１: Dockerへの各種プログラム開発環境立ち上げ
* 概要: フロントエンド/バックエンドに関連する各種開発環境のDocker構築方法の提示
* 使用技術: Docker/Docker-compose/Laravel(PHP)/Rails(Ruby)/Phoenix(Elixir)
           React/Vue
* 成果: DockerによるOSを問わない開発環境構築方法の習得
* 技術記事: 
  - [Elixir/Phoenixをdocker環境で立ち上げてみる。](https://qiita.com/naritomo08/items/fecf4ace7b9ca9078102)
  - [ruby on railsをdocker環境で立ち上げてみる。](https://qiita.com/naritomo08/items/b39d4ee6987fb052ca79)
  - [php/laravelをdocker環境で立ち上げてみる。](https://qiita.com/naritomo08/items/a66f4647c13a6c4a920e)
  - [Vue/React開発環境をdocker環境で立ち上げてみる。](https://qiita.com/naritomo08/items/f57165958d258b6f5c17)

### 記事2: Terraformによる各種クラウドへのシステム立ち上げ
* 概要: Terraformを使用したコードからのインフラ構築方法の提示の提示
* 使用技術: Docker/Docker-compose/Terraform/AWS/Azure/GCP
* 成果: Terraformによるクラウド環境を問わない構築方法の習得
* 技術記事: 
  - [Terraformをdocker環境で立ち上げてみる。](https://qiita.com/naritomo08/items/7e5a9d1b7eaf18dc0060)
  - [Terraformエトセトラ](https://qiita.com/naritomo08/items/0765649b6e79ded5ef09)
* ソースリポジトリ
  - [Terraform稼働Docker](https://github.com/naritomo08/terraform_docker_public)
  - [Terraformソース](https://github.com/naritomo08/terraform_source_public)

### 記事3: CI/CD環境構築
* 概要: Terraform/Dockerを使用し、Laravelサイトのインフラ構築〜ECSへのデプロイ実施
* 使用技術: Docker/Docker-compose/Terraform/GitHubAction/AWS(ECS/ECR/ALB)
* 成果: ローカルLaravelサイトからAWS/ECSへのデプロイを通じたCI/CD環境の構築方法習得
* 技術記事: 
  - [Terraformを使用してECS環境構築し、Laravelサイトを立ち上げてみた。](https://qiita.com/naritomo08/items/6e38955145d80c1435bd)
* ソースリポジトリ
  - [インフラ構築Terraformソース](https://github.com/naritomo08/laravel-fargate-infra-public)
  - [デプロイ対象Laravelソース](https://github.com/naritomo08/laravel-fargate-app-public)

### 個人開発1: API開発
* 概要: API開発の実施(JSONパーサー)
* 使用技術: Docker/Docker-compose/Phoenix(Elixir)
* 成果: API開発を通じた開発方法の習得
* 技術記事: 
  - [Elixir/PhoenixでJSONパーサーAPIを作ってみる。](https://qiita.com/naritomo08/items/e45f5e97f44fcc6426a6)

## ソフトスキル

* コミュニケーション能力
  - 直近の案件にて、PLとしてプロジェクト提案からリリースまでの顧客折衝、チームマネージメントを実施しています。
* 問題解決能力
  - これまでの参画案件で技術的/コミュニケーション問題について自ら手を上げ対応してきました。
* 柔軟性
  - 今まで行ってきたサーバエンジニアにこもらず、別の領域へ個人開発/技術記事作成を介して自己研鑽しています。

## 資格
 
* [AWS Solution Architect Associate] - [令和5年1月]
* [LPICレベル1] - [平成26年1月]
* [マイクロソフト認定資格（MCSA）Windows Server 2008] - [平成24年4月]
