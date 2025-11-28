## Mise en place du référentiel

```
.
├── base
│   ├── kustomization.yml
│   ├── nginx-cm.yml
│   ├── nginx-conf-cm.yml
│   ├── nginx-deploy.yml
│   ├── nginx-hpa.yml
│   └── nginx-svc.yml
├── dev
├── preprod
└── prod
```

**Vérification par**
```
kubectl kustomize base
```
