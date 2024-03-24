【参考資料】
https://developer.mozilla.org/ja/docs/Web/HTTP/Status

**収入画面**
| API Name      | HTTP Method | Path                | Status Code     | Description     |
|:-----------   |:----------- |:-----------------   |:--------------- |:-------------   |
| GET Incomes   | GET         | /api/v1/incomes     | 200(OK)         | Get Incomes     |
| POST Income   | POST        | /api/v1/income      | 201(Created)    | A New Income    |
| GET Income    | GET         | /api/v1/income/{id} | 200(OK)         | A Get Income    |
| PUT Income    | PUT         | /api/v1/income/{id} | 200(OK)         | A Update Income |
| DELETE Income | DELETE      | /api/v1/income/{id} | 204(NO Content) | A Delete Income |

**支出画面**
| API Name       | HTTP Method | Path                 | Status Code     | Description      |
|:-----------    |:----------- |:-----------------    |:--------------- |:-------------    |
| GET Expences   | GET         | /api/v1/expences     | 200(OK)         | Get Expences     |
| POST Expence   | POST        | /api/v1/expence      | 201(Created)    | A New Expence    |
| GET Expence    | GET         | /api/v1/expence/{id} | 200(OK)         | A Get Expence    |
| PUT Expence    | PUT         | /api/v1/expence/{id} | 200(OK)         | A Update Expence |
| DELETE Expence | DELETE      | /api/v1/expence/{id} | 204(NO Content) | A Delete Expence |

**残高表示**

【現在の残高】
| API Name     | HTTP Method | Path               | Status Code     | Description     |
|:-----------  |:----------- |:-----------------  |:--------------- |:-------------   |
| GET Balance  | GET         | /api/v1/balance    | 200(OK)         | Get Balance     |

【残高の変動履歴】
| API Name             | HTTP Method | Path                       | Status Code     | Description         |
|:-------------------  |:----------- |:------------------------   |:--------------- |:-------------       |
| GET Balance History  | GET         | /api/v1/balance_history    | 200(OK)         | Get Balance History |

**設定**
| API Name       | HTTP Method | Path                 | Status Code     | Description      |
|:-----------    |:----------- |:-----------------    |:--------------- |:-------------    |
| GET settings   | GET         | /api/v1/settings     | 200(OK)         | Get Settings     |
| POST setting   | POST        | /api/v1/setting      | 201(Created)    | A New Setting    |
| GET setting    | GET         | /api/v1/setting/{id} | 200(OK)         | A Get Setting    |
| PUT setting    | PUT         | /api/v1/setting/{id} | 200(OK)         | A Update Setting |
| DELETE setting | DELETE      | /api/v1/setting/{id} | 204(NO Content) | A Delete Setting |
