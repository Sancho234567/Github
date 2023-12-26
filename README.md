```mermaid
flowchart LR

A[Develop app] -->|Visual Studio| B(Round)
B --> C{App Repository}
B --> {GitHub Actions
C -->|One| D[Push to Registry] --> Azure Container Registry
C -->|Two| E[Deploy to Kubernetes] --> Azure Kubernetes Service
```
