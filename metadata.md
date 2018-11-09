# metadata
## Annotation
`metadata.annotaions`に設定することができる。  
アノテーションはリソースに対するメモ書きのようなもの。
```yaml
apiVersion: v1
kind: Pod
metadata:
  name: sapmle-annotations
  annotations:
    annotation1: val1
    annotatoin2: val2
spec:
  containers:
    - name: nginx-containter
      image: nginx:1.12
```
* システムコンポーネントのためにデータを保存
* 全ての環境では利用できない設定
* 正式に組み込まれる前の機能の設定

## Label
`metadata.labels`に設定することができる。  
ラベルはリソースを分割するための情報
```yaml
apiVersion: v1
kind: Pod
metadata:
  name: sample-label
  labels:
    label1: val1
    label2: val2
spec:
  containers:
    - name: nginx-container
      image: nginx:1.12
```
* 開発者が利用するラベル
* システムが利用するラベル
