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

