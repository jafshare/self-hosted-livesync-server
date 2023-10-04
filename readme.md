## What is this

- CouchDB Server which configured about CORS for Obsidian and Self-hosted LiveSync.

## How to Use

1. 克隆仓库
2. 设置环境变量`COUCHDB_USER`和`COUCHDB_PW`用于生成对应的账号密码
3. 运行`docker-compose up -d`
4. 访问`http://you-ip/_utils`即可设置`couchdb`的后台，创建`db`
5. 在`obsidian`插件中填写配置即可

| name           | value                               | example        |
| -------------- | ----------------------------------- | -------------- |
| COUCHDB_USER   | The account name you want to access | testuser       |
| COUCHDB_PW     | The password                        | testpassword   |

## License 
MIT
