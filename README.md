## mysql-backup

- 借助 mysqldump 进行 mysql 压缩备份
- 系统需要有 mysqldump zip 支持
- 删除过期备份文件，保留指定数量的备份文件
- 可通过邮箱发送压缩好的备份文件

## 使用

- 直接在项目中使用: [main.go](example/main.go)
- 使用docker: [docker-compose.yml](docker/docker-compose.yml)