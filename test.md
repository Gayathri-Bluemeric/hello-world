
**Resource Specification**
```yaml
apiVersion: rbac.authorization.k8s.io/v1
kind: ClusterRole
metadata:
  annotations:
    rbac.authorization.kubernetes.io/autoupdate: 'true'
  creationTimestamp: '[REDACTED_TIMESTAMP_ISO8601]'
  labels:
    kubernetes.io/bootstrapping: rbac-defaults
  managedFields:
    - apiVersion: rbac.authorization.k8s.io/v1
      fieldsType: FieldsV1
      fieldsV1:
        f:metadata:
          f:annotations:
            .: {}
            f:rbac.authorization.kubernetes.io/autoupdate: {}
          f:labels:
            .: {}
            f:kubernetes.io/bootstrapping: {}
        f:rules: {}
      manager: kube-apiserver
      operation: Update
      time: '[REDACTED_TIMESTAMP_ISO8601]'
  name: cluster-admin
  resourceVersion: '73'
  uid: '[REDACTED_UUID]'
rules:
  - apiGroups:
      - '*'
    resources:
      - '*'
    verbs:
      - '*'
  - nonResourceURLs:
      - '*'
    verbs:
      - '*'
```
