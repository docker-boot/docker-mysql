# MySQL

### 端口
```
3306
```

### 账号
```
数据库名：test

用户名：test

test密码：123456

root密码：123456
```

### 进容器
```
docker-compose exec mysql bash
```

### 进MySQL
```
mysql -u root -p
```

### 授权远程
```
GRANT ALL PRIVILEGES ON *.* TO 'test'@'%' IDENTIFIED BY '123456' WITH GRANT OPTION;

FLUSH PRIVILEGES;
```

### phpMyAdmin
```
http://localhost:10011/index.php

服务器：外网ip（注：127.0.0.1 和 localhost -- mysqli::real_connect(): (HY000/2002): Connection refused） 
```
