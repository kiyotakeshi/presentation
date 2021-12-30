# 経歴書

## 基本情報

- [GitHub](https://github.com/kiyotakeshi)
- [前職の GitHub](https://github.com/kiyotake-tagbangers)
- [現職の GitHub](https://github.com/KiyotaTakeshi)
- [はてなブログ](https://ponkan1219.hateblo.jp/)
- [Speaker Deck](https://speakerdeck.com/kiyotakeshi69/)
- [技術情報発信1](https://blog.tagbangers.co.jp/ja/author/kiyotake)
- [技術情報発信2](https://www.gxp-group.co.jp/gplus/?p=5334)
- [Qiita](https://qiita.com/ponkan1219)
- [Twitter](https://twitter.com/ponkan1219)

## 主な業務経歴

### 大規模オンプレ現場でハードウェアの運用保守、NW機器(FW,LB)の設定変更(1年)

- Jenkinsジョブにてファームウェアの適用(PowerCLIスクリプトを展開)

- 通信要件に応じたFWの穴あけ、LBのVIP設定

- yamlで記載されGit管理されたping監視の設定を変更

- Confluenceに通信要件の対応に関する社内ルールのドキュメントを整備

### Ansibleを使用した Dev,Stg 環境の構築(半年)

- Itamae で管理されているdev環境を Ansible に置換

- Stg環境のサーバ構築(Prometheus,Grafanaによる新規監視)

- Redis の負荷試験、性能調査を実施

### マイクロサービスのアプリケーションの動作基盤(EKS)を構築

- Terraform を使用

- Terraform を使用して、マイクロサービスで作られたアプリケーションを動作させる環境として EKS on Fargate を新規構築
    - 必要なAWSコンポーネントを作成
    - ALB Ingress Controller と必要な Pod に IRSA(IAM Role for Service Account) を設定
    - aws-auth(ConfigMap)を編集し、クラスタの操作権限を調整

- 社内でのマイクロサービス、Kubernetesの解説、ドキュメントの整備

### Spring MVC を使用した応募審査システムの機能追加

- エンドポイントの追加開発

### 複数コンテナの動作基盤(Elastic Beanstalk)を構築

- Terraform を使用

- Amazon Linux2 Docker platform(旧 Multicontainer Docker platform) を構築

### サーバーレスアプリケーションの動作基盤(Lambda,API Gateway)の構築

- Terraform, Bref, Serverless Framework を使用

- チーム内で Terraform の知見を共有し、単一障害点になることを回避

### 複数コンテナの動作基盤(ECS)を構築

- Terraform を使用

- CodeBuild を使用した CICD 環境も構築

### Amazon Linux2 への移行作業

- 既存サーバーの調査と移行後の動作の確認

### Side-car pattern の検証と既存アプリのコンテナ化

- Tweleve Factor App にのっとったアプリケーションの修正
    - 成果物を一つにし、設定を外部注入できるようにする
    - ログを標準出力に出す

- ECS on Fargate(Task, Service)の構築

- GitHub Actions を使用した CICD の構築

### .NET Core(3.1系) を使用した BFF(json を返す API サーバ)の新規開発

- Web API のエンドポイントの設計

- OpenAPI を使用したエンドポイントの記載

- CQRS, Mediator pattern を使用

- .NET Core を使用した実装

### .NET Core(3.1系) を使用した BFF の Azure へのデプロイ

- マルチステージビルドを使用したアプリケーションのコンテナ化

- 他サービスとの疎通のための設定の調整

### Spring Boot で開発された Batch アプリの機能追加

### GCP の Cloud Run の検証

- [Spring Boot でサンプルアプリケーション](https://github.com/KiyotaTakeshi/gcp-backend-sample) を作成し、コミットすると Cloud Native Buildpacks で Docker イメージをビルドしデプロイ

- Cloud Run から Cloud SQL に疎通するための Serverless VPC Connector などは [terraform で構築](https://github.com/KiyotaTakeshi/gcp-terraform)

### 社内での勉強会で [roadmap.sh](https://roadmap.sh/) の [Backend Developer](https://roadmap.sh/backend) を基にサンプルコードを用意してハンズオンを実施

- [MongoDB のハンズオン, MongoDB * Spring のサンプル](https://github.com/kiyotakeshi/spring-mongo)

- [jwt を使用した認証、認可のサンプル](https://github.com/kiyotakeshi/jwt-authentication)

- [jwt を使用した認証、認可のサンプル2](https://github.com/KiyotaTakeshi/spring-security-postgres)

- [Java17 * Basic認証のサンプル](https://github.com/KiyotaTakeshi/basic-authentication-java17)

- [Bcypt Encoder のハンズオン](https://github.com/kiyotakeshi/spring-security-encoder-playground)

- [Keycloak を使用した OIDC のサンプル](https://github.com/kiyotakeshi/keycloak-resource-server)

- [Spring * Redis](https://github.com/kiyotakeshi/spring-redis-playground)

- [Spring * Redis * RDB * Testcontainers](https://github.com/kiyotakeshi/spring-rdb-redis-testcontainers)

- [Spring * Kafka によるイベント駆動型アーキテクチャのサンプル](https://github.com/kiyotakeshi/kafka-spring-sample)

- [Elasticsearch のハンズオン](https://github.com/KiyotaTakeshi/es-sample)

## 保有資格

- AWS Certified Solutions Architect - Professional

- AWS Certified Solutions Architect - Associate

- CCNA Routing and Switching

- LinaC level 1

- TOEIC 720点

## ポートフォリオ

### [Todo アプリケーション](https://github.com/kiyotakeshi/todo-monolithic)

- テストコードを元に、 [停止中: API仕様書](https://www.bullstechnology.com/api) を自動生成する仕組みである、 RESTDocs を使用したバックエンド実装

- ES6 の表現で記述した JS により fetch することでバックエンドのAPIをコールする仕組みを実装

- これらをコンテナ化に対応した状態でローカル開発

- git の tag の push に反応して GitHub Actions による自動ビルドと jar の生成を実行

- フロントとバックエンドを分離したもの
    - [Front リポジトリ](https://github.com/kiyotakeshi/todo-ui)
    - [Backend リポジトリ](https://github.com/kiyotakeshi/todo-api)

- [terraform を使用した AWS デプロイ](https://github.com/kiyotakeshi/todo-aws)

- [terraform を使用した Vultr デプロイ](https://github.com/kiyotakeshi/todo-vultr)
    - AWSだと個人利用としてはコストが割高なため
    - Vultr は海外VPS でありながら東京リージョンがある

## 触れたことのある技術

- [StackShare](https://stackshare.io/kiyotakeshi/following) を参照
