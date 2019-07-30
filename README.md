## Rewrite

```bash
dotnet publish src/MyWeb --output .publish --runtime linux-x64
docker-compose build
docker-compose up
```

- http://localhost:8080/api/values
- http://localhost:8080/i/values