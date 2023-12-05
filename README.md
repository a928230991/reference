Website: https://a928230991.github.io/reference
## Docker

[![Buy me a coffee](https://img.shields.io/badge/Buy%20me%20a%20coffee-048754?logo=buymeacoffee)](https://a928230991.github.io/#/sponsor) [![Docker Image Version (latest by date)](https://img.shields.io/docker/v/a928230991/reference)](https://hub.docker.com/r/a928230991/reference) [![Docker Image Size (latest by date)](https://img.shields.io/docker/image-size/a928230991/reference)](https://hub.docker.com/r/a928230991/reference) [![Docker Pulls](https://img.shields.io/docker/pulls/a928230991/reference)](https://hub.docker.com/r/a928230991/reference)

轻松通过 `docker` 部署 `Quick Reference` 网站。

```bash
docker pull a928230991/reference
```

```bash
docker run --name reference --rm -d -p 9667:3000 a928230991/reference:latest
# Or
docker run --name reference -itd -p 9667:3000 a928230991/reference:latest
```

在浏览器中访问以下 URL

```bash
http://localhost:9667/
```
