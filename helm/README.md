## Présentation de *Helm*

**Arborescence initiale**

```
.
├── hello
│   ├── charts
│   ├── Chart.yaml
│   └── templates
│       ├── hello-deploy.yml
│       └── hello-svc.yml
└── README.md
```

**Vérification**

```
helm template hello
```

**Récupération des valeurs par défaut**

```
helm show values hello/ > test-values.yml
```

**Déploiement initial d'une Chart**

```
helm install hello-dev hello/ -f test-values.yml --namespace dev-helm --create-namespace
```

**Liste des charts installées**

```
helm list -A
```

**Mise à jour d'une Chart**

```
helm upgrade hello-dev hello/ -f test-values.yml --namespace dev-helm --create-namespace
```

**Suppression d'une chart**

```
helm uninstall hello-dev -n dev-helm
```
