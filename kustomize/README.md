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

## Mise en place de l'environnement Dev

**Vérification par**
```
kubectl kustomize base
```

**Différenciation des ressources:**

* Préfixe/Suffixe de leur nom
* Isolation dans un namespace
