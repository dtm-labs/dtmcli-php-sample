# dtmcli-php-sample
dtmcli的php使用示例
## 快速开始
### 部署启动dtm
需要docker版本20.04以上
```
git clone https://github.com/dtm-labs/dtm
cd dtm && git checkout v1.7.5
docker-compose up
```
### 启动示例
```
composer install
php demo.php start
```
### 输出

可以从dtmcli-php-sample的日志里看到执行的顺序如下：

- TransOutTry
- TransInTry
- TransInConfirm
- TransOutConfirm

整个tcc事务执行成功

### 特别说明
该示例使用了workerman扩展,不同系统环境依赖请查看官方文档：http://doc.workerman.net/install/requirement.html
