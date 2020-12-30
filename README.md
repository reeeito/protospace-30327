# README

##users　テーブル

| Column     | Type    | Option     |
| ---------- | ------- | ---------- |
| email      | string  | null:false |
| password   | string  | null:false |
| name       | string  | null:false |
| profile    | text    | null:false |
| occupation | text    | null:false |
| position   | text    | null:false |

##comments　テーブル

| Column    | Type       | Option     |
| --------- | ---------- | ---------- |
| text      | text       | null:false |
| user      | references |            |
| prototype | references |            |


##prototypesテーブル
| Column      | Type          | Option     |
| ----------- | ------------- | ---------- |
| title       | string        | null:false |
| cattch_copy | text          | null:false |
| consept     | text          | null:false |
| user        | references    |            |