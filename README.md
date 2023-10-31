# Team13
### 專題名稱:王翔要記得記帳APP  
組長:c110118229 王翔  
組員:c110118222 邱楊智、c110118224 賴蔚霆  

### 專題簡介:  
現代流行的快時尚或物價的通膨常常造成大眾無法好好存到積蓄，剛賺到的錢將近月底就花光了，因而衍伸出新的詞彙-月光族，這代表著許多人對於財產帳務的控制不太在行才會造成這種情形，因此我們希望製作簡易操作的記帳APP，讓大家能開始重視自己的金錢流向以達到開源節流的目的。你是否曾經和朋友出去旅遊時因為金額分配不均而造成爭執呢?因此本小組希望能夠研發出拆帳功能，透過簡單的步驟快速紀錄，並正確地將金額平均分攤，最後明確的顯示出誰該付錢或收錢不僅守護好大家的感情也守住了荷包。本專案本組預計使用Android studio來設計APP連接SQLite最為後端的資料庫以製作出程式的架構，並透過簡化流程及美術編輯製作出簡易又上手的APP讓大家使用。  

### 分工表
|  *編號*  |  *任務內容*  |  *所需時(天)*  |  *前置任務*  |  *負責人*  |
| :------: |   :------:  |    :------:   |   :------:  |  :------:  |
|     1    |   決定主題   |       1       |      /      |王翔、邱楊智、賴蔚霆|
|     2    |   研擬計畫   |       2       |      1      |王翔、邱楊智、賴蔚霆|
|     3    |   任務分配   |       1       |      1      |王翔、邱楊智、賴蔚霆|
|     4    |   蒐集資料   |       7       |      3      |王翔、邱楊智、賴蔚霆|
|     5    |   資料統整   |       3       |      4      |王翔、邱楊智、賴蔚霆|
|     6    |   程式編寫   |       70      |      5      |王翔、邱楊智、賴蔚霆|
|     7    |   程式測試   |       10      |      6      |王翔、邱楊智、賴蔚霆|
|     8    |  使用者測試  |       7       |      7      |王翔、邱楊智、賴蔚霆|
|     9    |  系統修正    |       5       |      7      |王翔、邱楊智、賴蔚霆|
---
### 甘特圖
```mermaid
gantt
    title 甘特圖
　　決定主題     : a1 , 2023-10-03 , 1d
    研擬計畫     : a2 , after a1 , 2d
    任務分配     : a3 , after a1 , 1d
    蒐集資料     : a4 , after a3 , 7d
    資瞭統整     : a5 , after a4 , 3d
    程式編寫     : a6 , after a5 , 70d
    程式測試     : a7 , after a6 , 10d
    使用者測試   : a8 , after a7 ,7d
    系統修正     : a9 , after a7 , 5d
```
### PERT/CPM圖
![pert](pert_diagram第13組.png "PERT圖") 

### 功能性需求/非功能性需求

|功能性需求|說明|
| :------ | :------ |
| 1.帳號管理|使用者可以進行登入登出的操作(建立個人帳號) |
| 2.收支新增功能|使用者可以進行資料的登入(類型、項目、金額、日期)|
| 3.明細查閱功能|使用者可以查閱每一筆資料的內容|
| 4.拆帳功能|使用者可以查看此功能，進行自訂帳務分攤|
| 5.帳務分析|使用者可以利用此功能，查閱每月支出等統計結果|

|非功能性需求|說明|
| :-|:------|
|1.| APP是隨時都可以使用且穩定的|
|2.| APP要能夠支援不同作業系統|
|3.| 用戶要進行身份驗證，才能繼續操作/使用APP|
|4.| APP介面需要對用戶來說是直觀且容易操作的|  

---
### 功能分解圖(FDD)  

![FDD](功能分解圖.png "FDD圖")  

### 需求分析的文字描述  

一個記帳APP的需求分析簡述如下：  
(1.)用戶須先登入自己的APP帳戶  
(2.)用戶可以新增/刪除帳務項目與金額  
(3.)用戶可以查看帳務明細  
(4.)用戶可以使用拆帳功能將帳務項目與金額以自訂義方式攤給其他成員  
(5.)用戶可以查看帳務報表 

### 使用案例圖  
![使用案例圖](使用案例圖.png "使用案例圖")  

### 使用案例說明
![使用案例1](使用案例1.png "使用案例1") 
![使用案例2](使用案例2.png "使用案例2") 
![使用案例3](使用案例3.png "使用案例3") 
![使用案例4](使用案例4.png "使用案例4") 
![使用案例5](使用案例5.png "使用案例5") 

### 使用Figma劃出第一個使用案例的動態模擬畫面  
![figma](figma project.png "figma") 
### 系統環境圖  
![系統環境圖](系統環境圖.png "系統環境圖") 
### DFD 圖0  
![dfd0](dfd0.png "dfd0")



