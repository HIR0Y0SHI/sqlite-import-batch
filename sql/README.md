# SAUNA DB

## 環境

SQLite(sqlite3)

## DB作成

```bash
sqlite3 sauna.splite3

# 確認
sqlite> .database
```

## SQL実行

**初回実行の場合**、以下コマンドでDDL/DMLの実行。

```bash
sqlite> .read sql/01_add_sauna_master.sql
sqlite> .read sql/02_add_evaluation_table.sql
sqlite> .read sql/03_add_facility_type_master.sql
sqlite> .read sql/04_add_target_master.sql

```
