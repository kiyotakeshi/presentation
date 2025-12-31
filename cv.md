# 経歴書

## 基本情報

- [GitHub](https://github.com/kiyotakeshi)
- [Zenn](https://zenn.dev/kiyotatakeshi)
- [Speaker Deck](https://speakerdeck.com/kiyotakeshi69/)

- [前職の GitHub(更新していない)](https://github.com/kiyotake-tagbangers)
- [現職の GitHub(更新していない)](https://github.com/KiyotaTakeshi)
- [はてなブログ(更新していない)](https://ponkan1219.hateblo.jp/)
- [Qiita(更新していない)](https://qiita.com/ponkan1219)
- [前職でのテックブログ](https://blog.tagbangers.co.jp/ja/author/kiyotake.html)
- [前職でのテックブログ](https://www.gxp-group.co.jp/gplus/?p=5334)

## 主な業務経歴

現職での業務経歴

### WIP

- hoge

## 前職での業務経歴 (新しいものから順に記載)

<details>
<summary>前職での業務経歴</summary>

### WordPress で管理していたサイトを CloudFront * S3 による静的配信に移管

- terraform で構築
- ドメイン(レジストラ)の移管、Name server の変更

### 書類管理システムの機能追加

- Spring Boot(2系)のアプリケーション

- 電子帳簿保存法の改正に伴い、書類の履歴やファイル名を検索できるように

### 既存システムの決済サービスのリプレイスに関する開発

- Spring Boot(2系)のアプリケーションで使用している決済代行会社のサービス終了に伴うリプレイス

- FTP サーバーを使用したバッチ処理のテストコードを記載([mina-sshd](https://github.com/apache/mina-sshd)を使用)

### Ruby(3.1系),Rails(7系) を使用した json を返す API サーバの新規開発

- Web API のエンドポイントの設計、OpenAPI を使用したエンドポイントの記載

- app.diagrams.net(旧 draw.io)を使用した、データベースの設計、ER図の作成

### Spring Boot で開発された Batch アプリの機能追加

### GCP の Cloud Run の検証

- [Spring Boot でサンプルアプリケーション](https://github.com/KiyotaTakeshi/gcp-backend-sample) を作成し、コミットすると Cloud Native Buildpacks で Docker イメージをビルドしデプロイ

- Cloud Run  から Cloud SQL に疎通するための Serverless VPC Connector などは [terraform で構築](https://github.com/KiyotaTakeshi/gcp-terraform)

### 社内での勉強会で [roadmap.sh](https://roadmap.sh/) の [Backend Developer](https://roadmap.sh/backend) を基にサンプルコードを用意してハンズオンを実施

- [MongoDB のハンズオン, MongoDB * Spring のサンプル](https://github.com/kiyotakeshi/spring-mongo)

- [jwt を使用した認証、認可のサンプル](https://github.com/KiyotaTakeshi/spring-security-postgres)

- [Java17 * Basic認証のサンプル](https://github.com/KiyotaTakeshi/basic-authentication-java17)

- [Bcypt Encoder のハンズオン](https://github.com/kiyotakeshi/spring-security-encoder-playground)

- [Spring * Kafka によるイベント駆動型アーキテクチャのサンプル](https://github.com/kiyotakeshi/kafka-spring-sample)

- [Elasticsearch のハンズオン](https://github.com/KiyotaTakeshi/es-sample)

### .NET Core(3.1系) を使用した BFF(json を返す API サーバ)の新規開発

- Web API のエンドポイントの設計、OpenAPI を使用したエンドポイントの記載

- CQRS, Mediator pattern を使用

- .NET Core を使用した実装

### .NET Core(3.1系) を使用した BFF の Azure へのデプロイ

- マルチステージビルドを使用したアプリケーションのコンテナ化

- 他サービスとの疎通のための設定の調整

### 複数コンテナの動作基盤(ECS)を構築

- Terraform を使用

- CodeBuild を使用した CI/CD 環境も構築

### Side-car pattern の検証と既存アプリのコンテナ化

- Twelve Factor App にのっとったアプリケーションの修正
  - 成果物を一つにし、設定を外部注入できるようにする
  - ログを標準出力に出す

- ECS on Fargate(Task, Service)の構築

- GitHub Actions を使用した CI/CD の構築

### Amazon Linux2 への移行作業

- 既存サーバーの調査と移行後の動作の確認

### サーバーレスアプリケーションの動作基盤(Lambda,API Gateway)の構築

- Terraform, Bref, Serverless Framework を使用

- チーム内で Terraform の知見を共有し、単一障害点になることを回避

### 複数コンテナの動作基盤(Elastic Beanstalk)を構築

- Terraform を使用

- Amazon Linux2 Docker platform(旧 Multicontainer Docker platform) を構築

### Spring MVC を使用した応募審査システムの機能追加

- エンドポイントの追加開発

### Ansibleを使用した Dev,Stg 環境の構築(半年)

- Itamae で管理されているdev環境を Ansible に置換

- Stg環境のサーバ構築(Prometheus,Grafanaによる新規監視)

- Redis の負荷試験、性能調査を実施

### 大規模オンプレ現場でハードウェアの運用保守、NW機器(FW,LB)の設定変更(1年)

- Jenkinsジョブにてファームウェアの適用(PowerCLIスクリプトを展開)

- 通信要件に応じたFWの穴あけ、LBのVIP設定

- yamlで記載されGit管理されたping監視の設定を変更

- Confluenceに通信要件の対応に関する社内ルールのドキュメントを整備

</details>

## 保有資格

- AWS Certified Solutions Architect - Professional

- AWS Certified Solutions Architect - Associate

- CCNA Routing and Switching

- LinaC level 1

- TOEIC 720点
