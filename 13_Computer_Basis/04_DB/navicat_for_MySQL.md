MySQL数据库客户端图形界面管理工具。

如果是DBA，建议直接用mysql命令行客户端，这对熟悉mysql各个命令帮助要大很多，除非是写一些存储过程之类的，或许gui工具有所帮助（组织代码）。

# 命令

- 返回数据库中所有表

```bash
select table_name from information_schema.tables where table_schema='lsb-test'
```

- 在某个表中查询字段

```bash
SELECT * FROM `user` WHERE phone='18565681300'
```

- 还可以插入，删除，但并没有很智能