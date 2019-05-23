## バージョンの確認
### コマンド  
psql --version
### SQL  
SELECT version();

## ユーザー（ロール）管理
### 作成
CREATE ROLE *user_name* **OPTION**;  
CREATE USER *user_name* **OPTION**;  

- 基本的にどちらも同じだが、CREATE USER だとデフォルトで「LOGIN」ロールが付与される。

OPTION  
- SUPERUSER | NOSUPERUSER
- CREATEDB | NOCREATEDB
- CREATEROLE | NOCREATEROLE
- CREATEUSER | NOCREATEUSER
- INHERIT | NOINHERIT
- LOGIN | NOLOGIN
- REPLICATION | NOREPLICATION
- CONNECTION LIMIT connlimit
- [ ENCRYPTED | UNENCRYPTED ] PASSWORD 'password'
- VALID UNTIL 'timestamp'
- IN ROLE role_name [, ...]
- IN GROUP role_name [, ...]
- ROLE role_name [, ...]
- ADMIN role_name [, ...]
- USER role_name [, ...]
- SYSID uid

### 削除
DROP ROLE *user_name*;
DROP USER *user_name*;

### 変更
ALTER ROLE *user_name* **OPTION**;

