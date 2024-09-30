---
title: Components Privileges
---

### karmada-operator
```yaml
  - apiGroups:
      - "autoscaling.karmada.io"
    resources:
      - cronfederatedhpas
      - cronfederatedhpas/status
      - federatedhpas
      - federatedhpas/status
    verbs:
      - get
      - list
      - watch
  - apiGroups:
      - "cluster.karmada.io"
    resources:
      - clusters
      - clusters/status
    verbs:
      - get
      - list
      - watch
  - apiGroups:
      - "certificates.k8s.io"
    resources:
      - certificatesigningrequests
      - certificatesigningrequests/status
    verbs:
      - get
      - list
      - watch
  - apiGroups:
      - "multicluster.x-k8s.io"
    resources:
      - serviceexports
      - serviceexports/status
      - serviceimports
      - serviceimports/status
    verbs:
      - get
      - list
      - watch
  - apiGroups:
      - "networking.karmada.io"
    resources:
      - multiclusteringresses
      - multiclusteringresses/status
      - multiclusterservices
      - multiclusterservices/status
    verbs:
      - get
      - list
      - watch
  - apiGroups:
      - "policy.karmada.io"
    resources:
      - overridepolicies
      - clusteroverridepolicies
      - propagationpolicies
    verbs:
      - get
      - list
      - watch
  - apiGroups:
      - "work.karmada.io"
    resources:
      - resourcebindings
      - resourcebindings/status
      - clusterresourcebindings
      - clusterresourcebindings/status
      - works
      - works/status
    verbs:
      - get
      - list
      - watch
```
