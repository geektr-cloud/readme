# GeekTR Private Cloud 相关项目

## Projects

- 开发基础服务 https://github.com/geektr-cloud/dev-base-services
  - Gitlab https://git.geektr.co
  - Verdaccio https://npm.geektr.co
  - Docker Registy https://registy.geektr.co

## Docker Images

|Name|Url|Desc|
|-|-|-|
|`geektrcloud/caddy`|[geektr-cloud/caddy](https://github.com/geektr-cloud/caddy)|caddy with tons of plugins (git,cors,realip,expires,cache,cloudflare,dyndns,cgi,filter,forwardproxy,geoip,grpc,ipfilter,jwt,login,s3browser)|
|`geektrcloud/verdaccio`|[geektr-cloud/verdaccio](https://github.com/geektr-cloud/verdaccio)|verdaccio with verdaccio-gitlab|
|`gcbuilder/node` ...|[geektr-cloud/gitlab-ci-builder](https://github.com/geektr-cloud/gitlab-ci-builder)|Gitlab CI 构建环境镜像|


## Archived Projects

|Name|Url|Desc|
|-|-|-|
|部署器|[geektr-cloud/deployer](https://github.com/geektr-cloud/deployer)|旧 docker compose 服务部署器|
|服务模板|[geektr-cloud/service-template](https://github.com/geektr-cloud/service-template)|旧 docker-compose 服务部署模板|
|Jumpserver|[geektr-cloud/jumpserver](https://github.com/geektr-cloud/jumpserver)|内网跳板机|
|Frp 服务器|[geektr-cloud/simple-frp-server](https://github.com/geektr-cloud/simple-frp-server)|Frp 服务器|
|绕墙 Frp 服务器|[geektr-cloud/dev-server-transfer-station](https://github.com/geektr-cloud/dev-server-transfer-station)|日本节点转发 -> Frp 服务器 -> 内网，用于无备案 http/https|
|绕墙 Api 网关|[geektr-cloud/archived-web-gateway](https://github.com/geektr-cloud/archived-web-gateway)|日本节点转发 -> Kong 网关 -> Frp 服务器 -> 内网，用于无备案 http/https|
|绕墙 Web 网关|[geektr-cloud/hub](https://github.com/geektr-cloud/hub)|Caddy -> Frp 服务器 -> 内网，用于无备案 http/https|
|Caddy Web 服务器|[geektr-cloud/web-server](https://github.com/geektr-cloud/web-server)||
|Frp 服务器|[geektr-cloud/frp-server](https://github.com/geektr-cloud/frp-server)||
|Frp 客户端|[geektr-cloud/frp-client](https://github.com/geektr-cloud/frp-client)||
