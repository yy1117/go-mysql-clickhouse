# go-mysql-clickhouse

通过改写MySQL的binlog的SQL类型来规避数据合并的性能

INSERT => INSERT

UPDATE => INSERT

DELETE => INSERT

获取最新数据的SQL详见configure.sql中的SQL2

QQ群：192815465
