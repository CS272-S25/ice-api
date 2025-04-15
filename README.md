build
```bash
docker build . -t ctnelson1997/cs272-s25-ice-api
docker push ctnelson1997/cs272-s25-ice-api
```

run
```bash
docker pull ctnelson1997/cs272-s25-ice-api
docker run --name=cs272_s25_ice_api -d --restart=always -p 43706:43706 -e CS272_CODES=AAAA... ctnelson1997/cs272-s25-ice-api
```