# DevOps Stack (GitLab + Jenkins + SonarQube + NGINX)

Descripción
Entorno DevOps local usando Docker Compose con:
- GitLab
- Jenkins
- SonarQube
- Reverse Proxy con NGINX

Arquitectura
- NGINX → reverse proxy
- Jenkins → CI/CD
- GitLab → repositorios
- SonarQube → calidad de código


```bash
docker compose up -d
