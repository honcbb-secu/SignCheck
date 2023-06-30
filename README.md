# SignCheck
SigCheck 是一個可驗證任何軟體程式數位簽名是否為合法，此程式簽名核心驗證主要採用了Microsoft (微軟)官方所公開提供的"WinVerifyTrust API " 該方法，此程式並非**第三方**或者**微軟官方**所開發(僅為一個資安研究人員Honc) 所開發而成，另外原因也是提供了基本GUI便捷而非透過下指令方式來驗證更為順暢

![image](https://i.imgur.com/HVoTxzs.jpeg)

[![Release](https://img.shields.io/badge/%E9%BB%9E%E6%88%91-%E4%B8%8B%E8%BC%89-brightgreen)](https://github.com/honcbb-secu/SignCheck/releases/download/V1.0/SigCheck.zip)

## Demo

[![ScreenShot](https://i.imgur.com/MVksKr8.jpeg)](https://www.youtube.com/watch?v=pUcM9cL5uu0&feature=youtu.be)

## 更新

SignCheck 會不定時更新

## 注意

SignCheck 雖然可拿來驗證軟體簽章是否合法，但這些資料都只能供當作參考(建議)，畢竟現代越來越多攻擊者的手法不斷的在變化(因此可能繞過這些防毒引擎)，但至少可以讓更多用戶防範(免除風險)。

## 支援

**Windows 系統**

## 分析

SigCheck 使用了Windows 通用的簽名驗證函數(**WinVerifyTrust**)，基本上驗證結果是可信任的

## 安全

程式絕沒有植入**病毒木馬**及**竊取用戶電腦資訊** 任何情況，如果還是**無法放心(請勿使用)** ;另外在此程式並未使用**軟體加密保護技術** 所以基本上防毒是不會判為惡意

## 如何使用？

點選程式內的"**驗證**" 按鈕後瀏覽您要驗證的檔案或.dll 後確認即可顯示驗證結果

## 常見問題

* 程式可驗證那些檔案類型簽章 ? 

    → 『目前僅支援.exe,dll 類型檔案文件』
  
* 偽造簽章或無效簽章，程式驗的出來嗎 ? 

    → 『可以，也請參閱上方demo 影片(當中有經過偽造簽章驗證事例)』
    
 
 ## 聯絡

若有任何問題請聯繫我：honcbb@gmail.com
  
