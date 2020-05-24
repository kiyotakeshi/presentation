# 業務経歴書

## 基本情報

|key|value|
|----|----|
|Twitter|[@ponkan1219](https://twitter.com/ponkan1219) |
|Qiita|[@ponkan1219](https://qiita.com/ponkan1219)|
|GitHub|[ponkan1219](https://github.com/kiyotakeshi)|
|Scrapbox|[非エンジニア領域のメモ置き場](https://scrapbox.io/ponkan1219/)|
|英語力|TOEIC720点|

## 概要

- NWエンジニアとして大規模オンプレの保守運用

- Ansibleを使用したdev,stg環境の構築、監視の整備

- マイクロサービスのアプリケーションの動作基盤を、Terraformで構築

- Spring MVCを使用した応募審査システムの機能追加

## 主な業務経歴

### 大規模オンプレ現場でハードウェアの運用保守、NW機器(FW,LB)の設定変更(1年)

- Jenkinsジョブにてファームウェアの適用(PowerCLIスクリプトを展開)

- 通信要件に応じたFWの穴あけ、LBのVIP設定

- yamlで記載されGit管理されたping監視の設定を変更

- Confluenceに通信要件の対応に関する社内ルールのドキュメントを整備

### Ansibleを使用したdev,stg環境の構築(半年)

- Itamaeで管理されているdev環境をAnsibleに置換

- Stg環境のサーバ構築(Prometheus,Grafanaによる新規監視)

- Redisの負荷試験、性能調査を実施

### マイクロサービスのアプリケーションの動作基盤を、Terraformで構築

- EKS on Fargate でマイクロサービスのPodを動作する環境をTerraformにて新規構築
    - ALB Ingress Controllerと必要なPodにIRSA(IAM Role for Service Account)を設定
    - aws-auth(ConfigMap)を編集し、クラスタの操作権限を調整

- 社内でのマイクロサービス、Kubernetesの解説、ドキュメントの整備

### Spring MVCを使用した応募審査システムの機能追加

- エンドポイントの追加開発

## 触れたことのある技術

### OS

CentOS6/7 | VMware ESXi 5/6 | Ubuntu18/19

### ネットワーク

Packet Tracer | Juniper(SRX) | PaloAlto(PA)

### 言語

Java(業務でメインに使用している言語) | Golang | Python | Shell script(bash) | Power Shell

### フレームワーク等

Spring Boot

### RDB/NoSQL

MySQL | Redis | Memcached

### クラウド

#### AWS

VPC | S3 | ELB | EC2 | ECS | Route53 | IAM | RDS(MySQL,Postgres) | DynamoDB | Cloud Watch | EKS | ECR | ACM | SES

#### GCP

VPC | GCS | Cloud Functions | Cloud Pub/Sub

### SaaS/PaaS

GitHub | BitBucket | DataDog

### その他

Terraform | Docker | Vagrant | Jenkins | PlantUML | Ansible | nginx | Apache | Tomcat | Prometheus | Grafana | BIND | Postfix | Slack | Jira | Confluence | Bamboo | Backlog | Kibera | 自作PC(Ryzen5 2400G) | Raspberry pi 4 model B

## 普段の開発環境

- Kinessiss Freestyle か HHKB(Professional BT)

- Visual Studio Code か IntelliJ
    - コードを書くときは、vimのkeybind

- コマンドラインは、zsh + peco
