# dtmcli-php-sample
dtmcli的php使用示例
## 快速开始
### 安装运行dtm
参考[dtm安装运行](https://dtm.pub/guide/install.html)

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
