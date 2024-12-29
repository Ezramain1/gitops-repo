ArgoCD configuration and environment-specific values
- **Structure**:  ```
  gitops-repo/
  ├── environments/
  │   ├── dev/
  │   │   └── values.yaml
  │   ├── staging/
  │   │   └── values.yaml
  │   └── production/
  │       └── values.yaml
  └── base/
      └── application.yaml
