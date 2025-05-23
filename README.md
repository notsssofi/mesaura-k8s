# Farmacia Mesaura - Proyecto Final

Este proyecto representa la infraestructura de Farmacia Mesaura desplegada en Kubernetes.

## Estructura

- `frontend/`: Portal B2C
- `backend/`: API principal
- `dashboard/`: Gestión interna
- `worker/`: Sincronización de stock
- `manifests/`: YAMLs de Kubernetes
- `docs/`: Diagramas y documentación
- `.github/workflows/`: CI/CD automático

## Namespaces

- `frontend`
- `backend`
- `dashboard`
- `dev`

## CI/CD

- Push en rama `dev` → deploy a namespace `dev`
- Push en rama `main` → deploy a `prod` (futuro)

## Requisitos

- Kubernetes (Minikube o K3s)
- kubectl
- GitHub Actions habilitado
