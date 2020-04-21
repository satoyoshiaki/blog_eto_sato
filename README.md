# テーブルとカラム、データ型構想

## taskテーブル

### カラム:データ型
#### name:string
#### description:text
#### priority:string
#### status:string
#### end_date:date
#### user_id:references

## userテーブル

### カラム:データ型
#### name:string
#### email:string
#### password_digest:string


## lavelテーブル

### カラム:データ型
#### name:string


## lavellingテーブル

### カラム:データ型
#### task_id:references
#### lavel_id:references
