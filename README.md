## users

| Column             | Type       | Options          |
| ------------------ | ---------- | ---------------- |
| nickname           | string     | null: false      |
| encrypted_password | string     | null: false      |

### Association
has_many :caluculations


## caluculations

| Column             | Type       | Options           |
| ------------------ | ---------- | ----------------- |
| junction_id        | integer    | null: false       |
| price              | integer    | null: false       |
| terminal_id        | integer    | null: false       |

### Association
belongs_to :user
