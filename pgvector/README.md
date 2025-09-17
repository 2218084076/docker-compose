# pgvector 服务

本目录用于通过 Docker Compose 部署带有 pgvector 扩展的 PostgreSQL。

## 启动方法

```bash
docker-compose up -d
```

## 默认端口

- 5432: PostgreSQL 服务端口

## 相关文件

- docker-compose.yml：服务编排配置
- data/init.sql：初始化 SQL 脚本

# Elasticsearch 服务

本目录用于通过 Docker Compose 部署 Elasticsearch。

## 启动方法

```bash
docker-compose up -d
```

## 默认端口

- 9200: HTTP API
- 9300: 集群通信

## 相关文件

- [docker-compose](docker-compose.yml)：服务编排配置

