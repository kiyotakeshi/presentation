# 経歴書

## 基本情報

- [GitHub](https://github.com/kiyotakeshi)
- [はてなブログ](https://ponkan1219.hateblo.jp/)
- [Speaker Deck](https://speakerdeck.com/kiyotakeshi69/)
- [技術ブログ](https://speakerdeck.com/kiyotakeshi69/)
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

- EKS on Fargate でマイクロサービスで作られたアプリケーションを動作させる環境を Terraform にて新規構築
    - 必要なAWSコンポーネントを作成
    - ALB Ingress Controller と必要な Pod に IRSA(IAM Role for Service Account) を設定
    - aws-auth(ConfigMap)を編集し、クラスタの操作権限を調整

- 社内でのマイクロサービス、Kubernetesの解説、ドキュメントの整備

### Spring MVCを使用した応募審査システムの機能追加

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

## 保有資格

- AWS Certified Solutions Architect - Professional

- AWS Certified Solutions Architect - Associate

- CCNA Routing and Switching

- LinaC level 1

- TOEIC 720点

## ポートフォリオ

### [Todo アプリケーション](https://www.bullstechnology.com/)

- [リポジトリ](https://github.com/kiyotakeshi/todo)
- テストコードを元に、 [API仕様書](https://www.bullstechnology.com/api) を自動生成する仕組みである、 RESTDocs を使用したバックエンド実装

- ES6 の表現で記述した JS により fetch することでバックエンドのAPIをコールする仕組みを実装

- これらをコンテナ化に対応した状態でローカル開発

- git の tag の push に反応して GitHub Actions による自動ビルドと jar の生成を実行

- フロントの実装を React にし、
バックエンドに認証を導入することを検討し開発中

### [Todo アプリケーションの AWS デプロイ](https://github.com/kiyotakeshi/todo-aws)

- Terraform により、Todo アプリをデプロイするAWS の環境を定義

### [Todo アプリケーションの Vultr デプロイ](https://github.com/kiyotakeshi/todo-vultr)

- Terraform により、Todo アプリをデプロイする Vultr の環境を定義
    - AWSだと個人利用としてはコストが割高なため
    - Vultr は海外VPS でありながら東京リージョンがある

## 触れたことのある技術

- [StackShare](https://stackshare.io/kiyotakeshi/following)を参照

### OS

CentOS6/7/8 | VMware ESXi 5/6 | Ubuntu18/19

### ネットワーク

Packet Tracer | Juniper(SRX) | PaloAlto(PA)

### 言語

Java(業務でメインに使用している言語) | Kotlin | JavaScript(TypeScript) | Golang | Python | Shell script(bash) | Power Shell

### フレームワーク等

Spring Boot

### RDB/NoSQL

MySQL | Postgres | Redis | Memcached | Elasticsearch | MongoDB

### クラウド

#### AWS

VPC | S3 | ELB | EC2 | ECS(on EC2,Fargate) | Route53 | IAM | RDS(MySQL,Postgres) | DynamoDB | CloudWatch

EKS(on Fargate) | ECR | ACM | SES | RDS Proxy | Lambda | SSM | Elastic Beanstalk | Elasticsearch Service | ElastiCache | SecretManager

#### GCP

VPC | GCS | Cloud Functions | Cloud Pub/Sub

### SaaS/PaaS

GitHub | BitBucket | DataDog

### その他

Terraform | Docker | Kubernetes | Helm | Vagrant | Jenkins | Postman | PlantUML | Ansible | nginx | Apache | Tomcat | Prometheus | Grafana | BIND | Postfix | Slack | Jira | Confluence | Bamboo | Backlog | Kibera | 自作PC(Ryzen5 2400G) | Raspberry pi 4 model B | Vultr

## 普段の開発環境

- Kinessiss Freestyle か REALFORCE TKL for Mac(R2TL-USVM-WH)

- Visual Studio Code か IntelliJ
    - コードを書くときは、vimのkeybind

- コマンドラインは、zsh + peco
