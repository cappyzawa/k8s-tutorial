# Resources
## Workloads
クラスタ上にコンテナを起動させるために利用するリソース。
* Pod
* ReplicationController
* ReplicaSet
* Deployment
* DaemonSet
* StatefulSet
* Job
* CronJob

## Discovery & LB
コンテナのサービスディスカバリや、クラスタの外部からもアクセス可能なエンドポイントなどを提供するリソース。
ServiceとIngressがある。
### Service
* ClusterIP
* ExternalIP
* NodePort
* LoadBalancer
* Headless
* EternalName
* None-Selector
### Ingress

## Config & Storage
設定や機密データをコンテナに埋め込んだり、永続ボリュームを提供するリソース。
* Secret
* ConfigMap
* PersistentVolumeClaim

## Cluster
クラスタ自体の振る舞いを定義するリソース。
セキュリティまわりの設定やポリシー、クラスタの管理性を高める機能のためのリソースがある
* Node
* Namespace
* PersistentVolume
* ResourceQuota
* ServiceAccount
* Role
* ClusterRole
* RoleBinding
* ClusterRoleBinding
* NetworkPolicy

## Metadata
クラスタ内の他のリソースの動作を制御するためのリソース。
* LimitRange
* HorizontalPodAutoscaler
* PodDisruptionBudget
* CustomResourceDefinition
