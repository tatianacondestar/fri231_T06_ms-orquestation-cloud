# Kubernetes Cloud + Seguridad Profesional

## Arquitectura
Cluster Kubernetes en AWS EC2 usando Minikube.

## Componentes
- RBAC
- Network Policies
- Backup YAML
- Escaneo de imágenes con Trivy

## Archivos
- rbac.yaml
- networkpolicy.yaml
- backup-cluster.yaml

## Seguridad aplicada
- Restricción de acceso mediante RBAC
- Bloqueo de tráfico entre pods
- Escaneo de vulnerabilidades

## Problemas encontrados
### Problema 1
Permisos IAM insuficientes para EKS.

### Solución
Se implementó Minikube en EC2.

### Problema 2
NetworkPolicy no funcionaba.

### Solución
Se instaló Calico CNI.

## Resultado
Cluster funcional con políticas de seguridad aplicadas.
