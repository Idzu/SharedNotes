Установка
```
docker run -d --rm -p 8080:8080 \ -v $(pwd)/charts:/charts \ -e DEBUG=true \ chartmuseum/chartmuseum \ --storage="local" \ --storage-local-rootdir="/charts"
```

Создать chart
```
helm create postgres 
helm create pgadmin
```