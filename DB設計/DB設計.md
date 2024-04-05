**収入画面**  
【incomes】
| Column       | Type       | Null | Key   | Default | 
| :-----       | :---       | :--- | :---- | :-----  |
| id           | long       | NO   | PRI   |         |
| setting_id  | int        | NO   |       |         |
| amount       | int        | NO   |       |         |
| created_date | timestamp  | NO   |       |         |
| updated_date | timestamp  | YES  |       |         | 

**支出画面**  
【expences】
| Column       | Type       | Null | Key   | Default | 
| :-----       | :---       | :--- | :---- | :-----  |
| id           | long       | NO   | PRI   |         |
| setting_id   | int        | NO   |       |         |
| amount       | int        | NO   |       |         |
| created_date | timestamp  | NO   |       |         |
| updated_date | timestamp  | YES  |       |         | 

**残高表示**  
・現在の残高  
-> incomeとexpenceテーブルを使って計算する  

・残高の変動履歴  
-> 存在するレコード単位でincomeとexpenceテーブルを使って計算する  

**設定**  
・収入のカテゴリ編集と追加  
【setting_income】
| Column             | Type       | Null | Key   | Default | 
| :-----             | :---       | :--- | :---- | :-----  |
| setting_id                 | long       | NO   | PRI   |         |
| category_name      | string     | NO   |       |         |
| created_date       | timestamp  | NO   |       |         |
| updated_date       | timestamp  | YES  |       |         | 

・支出のカテゴリ編集と追加  
【setting_expence】
| Column             | Type       | Null | Key   | Default | 
| :-----             | :---       | :--- | :---- | :-----  |
| setting_id                 | long       | NO   | PRI   |         |
| category_name      | string     | NO   |       |         |
| created_date       | timestamp  | NO   |       |         |
| updated_date       | timestamp  | YES  |       |         | 
