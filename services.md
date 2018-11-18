# Services
|名前|説明|
|:---:|:---|
|ClusterIP|k8s Cluster内でのみ疎通可能な仮想IP|
|ExternalIP|特定のk8s NodeのIPアドレス|
|NodePort|全k8s Nodeの全IPアドレス|
|LoadBalancer|クラス違いで提供されているLoadBalancerの仮想IP|
|HeadLess(None)|PodのIPアドレスを用いたDNS Round Robin|
|ExternalName|CNAMEを用いた疎結合性の確保|
|None-Selector|自由に宛先メンバを設定可能な様々な種別のエンドポイント|
