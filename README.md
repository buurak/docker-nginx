```
docker build -t buurak/nginx-server:v1 .
docker run -it --rm -d -p 80:80 --name nginx-server -v $(pwd):/usr/share/nginx/html buurak/nginx-server:v1    
```
