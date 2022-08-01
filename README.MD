```powershell
podman machine start

podman build -t demo-fastapi .

podman run -p 8080:8080 demo-fastapi

podman machine stop
```