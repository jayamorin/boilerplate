# directory
Directory structure template
.
├── base
│   ├── deployment.yaml
│   ├── ingress.yaml
│   ├── kustomization.yaml
│   └── service.yaml
├── .github
│   └── workflows
│       ├── service-a-build.yaml
│       ├── service-b-build.yaml
│       └── service-c-build.yaml
├── .gitignore
├── overlays
│   ├── dev
│   │   ├── kustomization.yaml
│   │   └── patch.yaml
│   └── prod
│       ├── kustomization.yaml
│       └── patch.yaml
├── project-build.yaml
├── project-deploy.yaml
├── README.md
└── services
    ├── service-a
    │   ├── Dockerfile
    │   ├── .dockerignore
    │   ├── info.yaml
    │   ├── README.md
    │   ├── src/**
    │   └── TODO.md
    ├── service-b
    │   ├── Dockerfile
    │   ├── .dockerignore
    │   ├── info.yaml
    │   ├── README.md
    │   ├── src/**
    │   └── TODO.md
    └── service-c
        ├── Dockerfile
        ├── .dockerignore
        ├── info.yaml
        ├── README.md
        ├── src/**
        └── TODO.md
