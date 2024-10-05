# Pysio's Home
![Vue-blog](https://socialify.git.ci/pysio2007/Vue-blog/image?description=1&descriptionEditable=Pysio%27s%20Home%20%E4%B8%80%E4%B8%AA%E6%B8%A9%E6%9A%96%E7%9A%84%E5%AE%B6&forks=1&language=1&name=1&owner=1&pattern=Circuit%20Board&pulls=1&stargazers=1&theme=Auto)
[![Netlify Status](https://api.netlify.com/api/v1/badges/29c374b3-c599-45be-9a6f-c177201960b3/deploy-status)](https://app.netlify.com/sites/pysioblog/deploys)
[![Build Docker Image](https://github.com/pysio2007/Vue-blog/actions/workflows/bulid-docker.yml/badge.svg)](https://github.com/pysio2007/Vue-blog/actions/workflows/bulid-docker.yml)   
## 关于本仓库
本仓库是Pysio的个人博客 同时欢迎PR扩充文件 文章会显示GIT提交者  
交换友链请开Issues :P
### Docker 部署说明
拉取Docker镜像
```bash
docker pull pysio/pysioblog
```
运行Docker镜像
```bash
docker run --name PysioHome -p 8080:80 -d pysioblog
```