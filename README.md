## Docker-Desktop: heading...

#### Visit: https://hub.docker.com/repositories/omarmdwasimuddin --->Click: Create repository --->Repository Name: my-node --->click: Create ---> repo name copy koro.
![](https://imgur.com/g4bsr6V.png)
#### vs Terminal e command daw [repo build koro]
```bash
docker buildx build --platform linux/amd64 -t omarmdwasimuddin/my-node .
```
#### check docker images
```bash
docker images
```
---

#### repo push koro
```bash
docker push omarmdwasimuddin/my-node
```
---
