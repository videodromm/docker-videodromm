# docker-videodromm

netdromm project:

``` sh
cd path_to_netdromm
docker build -t netdromm .
docker run -it --rm -p 8088:8088 --name netdromm netdromm
```