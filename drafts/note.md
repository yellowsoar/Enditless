<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Note 編修說明書](#note-編修說明書)
	- [編修流程](#編修流程)
		- [(Mac) iD 編輯器 + Chrome](#mac-id-編輯器-chrome)
			- [找到要解決的 Note](#找到要解決的-note)
			- [確認 Note 內容的「資料正確性」](#確認-note-內容的資料正確性)
				- [實際踏察](#實際踏察)
				- [真實存在性](#真實存在性)
				- [門牌號碼確認](#門牌號碼確認)
				- [其他待補](#其他待補)
			- [編輯圖資](#編輯圖資)
			- [解決 Note](#解決-note)
- [關於本文件](#關於本文件)

<!-- /TOC -->
<!-- 目錄由 markdown-toc 產生
https://atom.io/packages/markdown-toc -->

# Note 編修說明書

## 編修流程

### (Mac) iD 編輯器 + Chrome
**注意!  
因介面與翻譯會隨使用者的作業系統、軟體版本而有所不同，  
故僅供 Windows 使用者參考。**

#### 找到要解決的 Note
1. 開啟 OSM 網站：  
[http://www.openstreetmap.org/#map=9/23.7414/120.599](http://www.openstreetmap.org/#map=9/23.7414/120.599)  
1. 開啟 Note 圖層：  
![](img/1.png)
1. 選擇尚未解決的 Note（紅色圖示）  
![](img/2.png)

>**或直接開啟有 Note 圖層的 OSM 網站並跳到此步驟  
（差別在於後者網址多了 ``&layers=N``）**

---

#### 確認 Note 內容的「資料正確性」

##### 實際踏察
步行或利用交通工具到達現場後進行踏查。

##### 真實存在性
利用 DuckDuckGO, Bing, Yahoo, Google 等搜尋引擎，確認所回報之內容是否真實存在。
1. DuckDuckGO [https://duckduckgo.com/](https://duckduckgo.com/)
1. Bing [https://www.bing.com/](https://www.bing.com/)
1. Yahoo [https://tw.yahoo.com/](https://tw.yahoo.com/)
1. Google [https://www.google.com](https://www.google.com)

##### 門牌號碼確認
1. 全國門牌地址定位服務(TGOS)  
[http://tgos.nat.gov.tw/tgos/Web/Address/TGOS_Address.aspx](http://tgos.nat.gov.tw/tgos/Web/Address/TGOS_Address.aspx)
1. 地籍圖資網路便民服務系統  
[http://easymap.land.moi.gov.tw/R02/Index](http://easymap.land.moi.gov.tw/R02/Index)
1. 村里街路門牌查詢(內政部戶政司)  
[http://www.ris.gov.tw/doorplateX/](http://www.ris.gov.tw/doorplateX/)
1. 門牌整合檢索系統(台北市政府民政局)  
[http://houseno.civil.taipei/](http://houseno.civil.taipei/)

##### 其他待補
因此資料正確性的科技應用能力

---

#### 編輯圖資
1. 若確認 Note 內容無誤或已取得正確資訊，右鍵點擊左上角的「Edit」標籤，然後以新標籤頁打開連結編輯 OSM。注意：編輯時請盡可能只編輯 Note 內容，即本次變更組合（ChangeSet）只包含編修 Note 所需要的變更。
![](img\3.png)
1. 編輯完畢要上傳時，請複製 Note 的網址貼上到註解（comment）然後按下儲存。![](https://hackpad-attachments.s3.amazonaws.com/osmtw.hackpad.com_5FCtyE3QsJE_p.192101_1435937982257_2015-07-03_23-38-36.png)
1. 上傳完畢後請右鍵點擊左側「View on OSM」圖示，並複製連結然後關閉分頁。![](https://hackpad-attachments.s3.amazonaws.com/osmtw.hackpad.com_5FCtyE3QsJE_p.192101_1435938165359_2015-07-03_23-41-47.png)

---

#### 解決 Note

1. 回到 Note 分頁，貼上剛剛複製的 Changeset 連結，然後按「Comment & Resolve」。![](https://hackpad-attachments.s3.amazonaws.com/osmtw.hackpad.com_5FCtyE3QsJE_p.192101_1435938344157_2015-07-03_23-43-56.png)
1. 如果 Note 已經被編輯但沒有被解決掉，請比照第八步驟貼上相關的 Changeset 連結然後按下「Comment & Resolve」，如果 Changeset 內容太龐大請貼上相關的 OSM 物件連結。
1. 如果 Note 資訊不足無法編輯，請在討論留下所缺乏的資訊，然後按下「Comment」。![](https://hackpad-attachments.s3.amazonaws.com/osmtw.hackpad.com_5FCtyE3QsJE_p.192101_1435938856477_2015-07-03_23-51-43.png)
1. 以上如有不夠詳盡之處請再補述。

# 關於本文件
**本文件改自：**  
https://osmtw.hackpad.com/Note-5FCtyE3QsJE
