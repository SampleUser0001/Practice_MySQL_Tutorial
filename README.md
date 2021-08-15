# Practice_MySQL_Tutorial

MySQLのお勉強をする。  
~~[https://dev.mysql.com/doc/refman/8.0/ja/tutorial.html](https://dev.mysql.com/doc/refman/8.0/ja/tutorial.html)を試す。~~  
phpMyAdminがあるので接続自体はできるが、シェルのほうが都合がいいのでそちらからどうにかしたい。

## 準備

- .mylogin.cnfファイルを作成する。
    - [ここ](https://sampleuser0001.github.io/cloud9_note/DB/MySQL.html#%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E4%BD%9C%E6%88%90)を参考に作成する
    - 事前にコンテナを起動して、practice_mysql_tutorial_db_1コンテナ内で実行する。

## 実行

```sh
docker-compose up -d
docker exec -it practice_mysql_tutorial_db_1 /bin/bash
```

``` sh
cd /tmp/sql
sh sample.sh
```

## 参考

- [第3章 チュートリアル:MySQL 8.0 リファレンスマニュアル](https://dev.mysql.com/doc/refman/8.0/ja/tutorial.html)