<h1 align="center" style="border-bottom: none">
    <b>
        <a href="https://www.nocodb.com">NocoDB </a><br>
    </b>
    ✨ Airtable 的开源替代品 ✨ <br>

</h1>
<p align="center">
将 MySQL、PostgreSQL、SQL Server、SQLite 或 MariaDB 转换为智能电子表格。
</p>
<div align="center">

[![Build Status](https://travis-ci.org/dwyl/esta.svg?branch=master)](https://travis-ci.com/github/NocoDB/NocoDB)
[![Node version](https://badgen.net/npm/node/next)](http://nodejs.org/download/)
[![Twitter](https://img.shields.io/twitter/url/https/twitter.com/NocoDB.svg?style=social&label=Follow%20%40NocoDB)](https://twitter.com/NocoDB)

</div>

<p align="center">
    <a href="http://www.nocodb.com"><b>Website</b></a> •
    <a href="https://discord.gg/5RgZmkW"><b>Discord</b></a> •
    <a href="https://twitter.com/nocodb"><b>Twitter</b></a> •
    <a href="https://www.reddit.com/r/NocoDB/"><b>Reddit</b></a> •
    <a href="https://docs.nocodb.com/"><b>Documentation</b></a>
</p>  

![OpenSourceAirtableAlternative](https://user-images.githubusercontent.com/5435402/133762127-e94da292-a1c3-4458-b09a-02cd5b57be53.png)

<img src="https://static.scarf.sh/a.png?x-pxid=c12a77cc-855e-4602-8a0f-614b2d0da56a" />

<a href="https://www.producthunt.com/posts/nocodb?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-nocodb" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=297536&theme=dark" alt="NocoDB - The Open Source Airtable alternative | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>


# 快速尝试
### 一键式部署

#### Heroku
<a href="https://heroku.com/deploy?template=https://github.com/nocodb/nocodb-seed-heroku">
    <img 
    src="https://www.herokucdn.com/deploy/button.svg" 
    width="300px"
    alt="Deploy NocoDB to Heroku with 1-Click" 
    />
</a>
<br>

### 使用Docker
```bash
docker run -d --name nocodb -p 8080:8080 nocodb/nocodb:latest
```

> 要使用数据持久化，你可以挂载到 `/usr/app/data/`。

### 使用NPM
```
npx create-nocodb-app
```
### 使用git
```
git clone https://github.com/nocodb/nocodb-seed
cd nocodb-seed
npm install
npm start
```

### GUI

使用仪表板使用 : [http://localhost:8080/dashboard](http://localhost:8080/dashboard)


# 加入我们的社区
<a href="https://discord.gg/5RgZmkW">
<img src="https://discordapp.com/api/guilds/661905455894888490/widget.png?style=banner3" alt="">
</a>
<br>
<br>

# 截图

![1](https://user-images.githubusercontent.com/86527202/136066713-5408634f-5469-40eb-94c9-7eafae5e179c.png)
<br>

![2](https://user-images.githubusercontent.com/86527202/136066729-9b6a261a-231d-4d7f-9fc2-061c301d6192.png)
<br>

![5](https://user-images.githubusercontent.com/86527202/136066734-3f25aecc-bb7e-4db7-81c4-00b368d799d3.png)
<br>

![6](https://user-images.githubusercontent.com/86527202/136066735-2d4cb656-02dc-4233-ac4a-1ba9bd8acdf0.png)
<br>

![7](https://user-images.githubusercontent.com/86527202/136066737-eb6a56fb-5e2e-4423-912b-ced32e8b479c.png)
<br>

![8](https://user-images.githubusercontent.com/86527202/136066742-94c7eff7-d88e-4002-ad72-ffd23090847c.png)
<br>

![9](https://user-images.githubusercontent.com/86527202/136066743-1b4030c5-042f-4338-99b0-06237878ce53.png)
<br>

![9a](https://user-images.githubusercontent.com/86527202/136066745-9797775d-7db0-4681-ab10-d7ecbbd972ef.png)
<br>

![9b](https://user-images.githubusercontent.com/86527202/136066750-7b566ec3-0983-47ed-9a4e-f895239f1ea4.png)
<br>

![10](https://user-images.githubusercontent.com/86527202/136066753-6dcda2cf-e7a3-4024-a897-f2b7044a64f4.png)
<br>

![11](https://user-images.githubusercontent.com/86527202/136066756-fc203c2c-570e-4514-b9f4-2a41ac24e5dd.png)
<br>






# 特征
### 丰富的电子表格功能

- ⚡ 搜索，排序，过滤，隐藏列
- ⚡ 创建视图：网格，画廊，看板，甘特图，表单
- ⚡ 分享视图：公开 或 密码保护
- ⚡ 个人和锁定视图
- ⚡ 将图像上传到单元格（使用S3，Minio，GCP，Azure，DigitalOcean，Linode，OVH，Backblaze）
- ⚡ 角色：所有者，创建者，编辑器，查看器，评论者，自定义角色。
- ⚡ 访问控制：在 `数据库`、`表`、`列` 级别的访问控制。

### 工作流自动化应用商店：
- ⚡ 聊天：微软Teams，Slack，Discord，Mattermost
- ⚡ 电子邮件：SMTP，SES，MailChimp
- ⚡ 短信：Twilio
- ⚡ whatsapp
- ⚡ 任何第三方API

### Programmatic API访问通过：
- ⚡ REST API (Swagger)
- ⚡ GraphQL API
- ⚡ JWT身份验证和社交验证
- ⚡ 与Zapier，Integromat集成的API


# 生产安装
NoCodb 要求一个数据库用来存储电子表格视图和外部元数据。可以在`NC_DB`环境变量中指定此数据库的连接参数。

## Docker

#### MySQL 示例
```bash
docker run -d -p 8080:8080 \
    -e NC_DB="mysql2://host.docker.internal:3306?u=root&p=password&d=d1" \
    -e NC_AUTH_JWT_SECRET="569a1821-0a93-45e8-87ab-eb857f20a010" \
    nocodb/nocodb:latest
```

#### Postgres 示例
```bash
docker run -d -p 8080:8080 \
    -e NC_DB="pg://host:port?u=user&p=password&d=database" \
    -e NC_AUTH_JWT_SECRET="569a1821-0a93-45e8-87ab-eb857f20a010" \
    nocodb/nocodb:latest
```

#### SQL Server 示例
```bash
docker run -d -p 8080:8080 \
    -e NC_DB="mssql://host:port?u=user&p=password&d=database" \
    -e NC_AUTH_JWT_SECRET="569a1821-0a93-45e8-87ab-eb857f20a010" \
    nocodb/nocodb:latest
```

## Docker Compose
```bash
git clone https://github.com/nocodb/nocodb
cd docker-compose
cd mysql or pg or mssql
docker-compose up
```


## 环境变量
| 变量                | 强制 | 注释                                                                         | 缺省                                  |
|-------------------------|-----------|----------------------------------------------------------------------------------|--------------------------------------------|
| NC_DB                   | Yes       | 查看我们的数据库 URL                                                | 将在根文件夹中创建一个本地 SQLite 文件 |
| DATABASE_URL            | No        | JDBC URL 格式。 可以代替 NC_DB 使用。 用于一键式 Heroku 部署|   |
| DATABASE_URL_FILE       | No        | 包含 JDBC URL 格式的文件的路径。 可以代替 NC_DB 使用。 用于一键式 Heroku 部署|   |
| NC_PUBLIC_URL           | Yes       | 用于发送电子邮件邀请                        | 尽量从 http 请求参数推测一个        |
| NC_AUTH_JWT_SECRET      | Yes       | JWT secret 用于认证和存储其他加密项          | 将会产生一个随机的 secret          |
| NC_SENTRY_DSN           | No        | 用于 Sentry 监控                          |   |
| NC_CONNECT_TO_EXTERNAL_DB_DISABLED | No | 禁止使用外部数据库创建项目                              |   |
| NC_DISABLE_TELE | No | 禁用 telemetry                              |   |
| NC_BACKEND_URL | No | 自定义后端URL                              | 将使用`http://localhost:8080`  |

# 开发安装

```bash
git clone https://github.com/nocodb/nocodb
cd nocodb

# 运行后端
cd packages/nocodb
npm install
npm run watch:run

# 在浏览器打开 localhost:8080/dashboard

# 运行前端
cd packages/nc-gui
npm install
npm run dev

# 在浏览器打开 localhost:3000/dashboard
```

对代码做更改后会自动重新启动服务。

## 在本地运行 Cypress 测试

```bash
# 安装开发依赖(cypress)
npm install

# 使用 docker compose 使用所需的数据库运行 mysql 数据库
docker-compose -f ./scripts/docker-compose-cypress.yml up

# 使用以下命令运行后端 api
npm run start:api

# 使用以下命令运行前端 Web UI
npm run start:web

# 等到 3000 和 8080 端口都可用时，使用以下命令运行Cypress测试
npm run cypress:run

# or run following command to run it with GUI
npm run cypress:open

```

# 贡献

- 请看一下 ./scripts/contribute/HowToApplyLicense.md
- 忽略为 .json 或 .md 或 .yml 添加标头

# 🎯 为什么我们建立这个？

大多数互联网业务都配备了电子表格或数据库以解决其业务需求，每天有上亿人使用电子表格。我们基于数据库运行更强大的工具能更高效地完成工作。用SaaS产品解决此问题的尝试已经意味着可怕的访问控制，供应商锁定，数据锁定，突然的价格变化，甚至是将来可能会阻碍发展。

# ❤ 我们的任务 ：

我们的使命是为数据库提供最强大的无码界面，为世界上每一个互联网业务的开源使用。这不仅将民主化带给强大的计算工具，还将为数亿人增强他们的创造力。
