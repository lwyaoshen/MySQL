# MySQL 元数据
你可能想知道MySQL以下三种信息：
- 查询结果信息： SELECT, UPDATE 或 DELETE语句影响的记录数。
- 数据库和数据表的信息： 包含了数据库及数据表的结构信息。
- MySQL服务器信息： 包含了数据库服务器的当前状态，版本号等。
在MySQL的命令提示符中，我们可以很容易的获取以上服务器信息。

命令 | 描述
---|---
SELECT VERSION( ) | 服务器版本信息
SELECT DATABASE( ) | 当前数据库名 (或者返回空)
SELECT USER( ) | 	当前用户名
SHOW STATUS | 服务器状态
SHOW VARIABLES | 	服务器配置变量

