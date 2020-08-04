## foodsテーブル

|Column|Type|Options|
|------|----|-------|
|name|text|null: false|
|preserve_id|integer|null: false, foreign_key: true|
|limit_year|integer|null: false|
|limit_month|integer|null: false|
|limit_day|integer|null: false|

### Association
- belongs_to :preserve_method

## foodsテーブル

|Column|Type|Options|
|------|----|-------|
|name|text|null: false|
|method|text|null: false|
|foods_id|integer|null: false, foreign_key: true|

### Association
- belongs_to :foods