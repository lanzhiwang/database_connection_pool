# 在PHP中使用pdo驱动和gearman实现的数据库连接池

[连接池实现参考](https://gonzalo123.com/2010/11/01/database-connection-pooling-with-php-and-gearman/)

[gearman参考](https://blog.csdn.net/qq43599939/article/details/54177438)

有待改进的点：
1. 预先加载的连接数量要可配置
2. 当实际的PDO连接数不够时刻自动增加
3. 异常处理
4. PDO方法支持
5. 命名空间估计也不对
6. ...



