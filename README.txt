<資訊之芽第二階段大作業>

->第1個for迴圈
	//將256 * 256 * 256種顏色依照其編碼規則壓縮成216種顏色，不包含在這216種顏色中的則以灰階處理，輸出彩色空白。

->第2個for迴圈
	//顏色越淺，其RGB的值越大，將顏色的RGB相加後的值壓縮成24種，輸出灰階空白。

->第3個for迴圈
	//將上下左右的RGB值與目前的RGB值的差取算術平均，大於40輸出"."，否則輸出空白。

->第4個for迴圈
	//將”第1個for迴圈”往左翻轉後輸出彩色空白。

->第5個for迴圈
	//將”第2個for迴圈”往左翻轉後輸出灰階空白。
