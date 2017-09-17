# MySQL 创建数据库
## 使用 mysqladmin 创建数据库
使用普通用户，你可能需要特定的权限来创建或者删除 MySQL 数据库。
所以我们这边使用root用户登录，root用户拥有最高权限，可以使用 mysql mysqladmin 命令来创建数据库。
实例
以下命令简单的演示了创建数据库的过程，数据名为 RUNOOB:
```
[root@host]# mysqladmin -u root -p create RUNOOB
Enter password:******
```
以上命令执行成功后会创建 MySQL 数据库 RUNOOB。

# MySQL 删除数据库

## 使用 mysqladmin 删除数据库
使用普通用户登陆mysql服务器，你可能需要特定的权限来创建或者删除 MySQL 数据库。
所以我们这边使用root用户登录，root用户拥有最高权限，可以使用 mysql mysqladmin 命令来创建数据库。
在删除数据库过程中，务必要十分谨慎，因为在执行删除命令后，所有数据将会消失。
以下示例删除数据库RUNOOB：
```
[root@host]# mysqladmin -u root -p drop RUNOOB
Enter password:******
```

执行以上删除数据库命令后，会出现一个提示框，来确认是否真的删除数据库：
```
Dropping the database is potentially a very bad thing to do.
Any data stored in the database will be destroyed.

Do you really want to drop the 'RUNOOB' database [y/N] y
Database "RUNOOB" dropped
```