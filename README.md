# grab-stock.js

# Tests
1.使用指令
	`$node everyday.js yyyy-mm-dd`
  即可抓許當天所有預選個股的資料（預選個股存在everyday.js裡的陣列, 預設為1314 2330 2498）
  ex.	`$node everyday.js 2015-10-17`

2.執行之後同一層目錄會自動產生資料夾 /res
  抓到的股票資料會依照個股代碼存放在不同資料夾
  ex.	/1314
  檔名會記錄個股代碼及日期
  ex.	2015-10-19_2330.json
  
notice:
1.請依照時間格式 `yyyy-mm-dd` 輸入
2.若輸入的日期為週末系統會給予提示並要求輸入其他日期

# Build
1. npm i

