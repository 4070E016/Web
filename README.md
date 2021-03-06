# OWASP TOP 10  
  2017 必考  
  TOC - About OWASP  
  FW- Foreword 前言  
  I- Introduction 簡介  
  RN - Release Notes 發布說明
  Risk - Application Security Risks 應用程序安全風險  
  T10 - OWASP Top 10 Application Security Risks – 2017 應用軟體安全風險-2017  
  A1:2017 - Injection 注入   
  A2:2017 - Broken Authentication 失效的身分認證  
  A3:2017 - Sensitive Data Exposure 敏感信息洩漏  
  A4:2017 - XML External Entities (XXE) XML 外部實體(XXE)  
  A5:2017 - Broken Access Control 失效的訪問控制  
  A6:2017 - Security Misconfiguration 安全配置錯誤  
  A7:2017 - Cross-Site Scripting (XSS) 跨站腳本(XSS)  
  A8:2017 - Insecure Deserialization 不安全的反序列化  
  A9:2017 - Using Components with Known Vulnerabilities 使用含有已知漏洞組件  
  A10:2017 - Insufficient Logging & Monitoring 不足的日誌紀錄和監控  
    +D - What’s Next for Developers 開發人下一步做什麼?  
    +T - What’s Next for Security Testers 安全測試下一步做什麼?  
    +O- What’s Next for Organizations 企業組織下一步做什麼?  
    +A- What’s Next for Application Managers 應用程序管理者下一步做什麼?  
    +R - Note About Risks 關於風險的備註說明  
    +RF- Details About Risk Factors 關於顯因素的詳細說明  
    +DAT - Methodology and Data 方法論與數據  
    +ACK - Acknowledgements 致謝  
  
  A1:2017-注入:將不受信任的資料作為命令或查詢的一部分發送到解析器時,會產生諸如SQL注入、NoSQL注入、OS 注入和LDAP注入的注入缺陷。攻擊者的惡意資料可以誘使解析器在沒有適當授權的情況下執行非預 期命令或訪問資料。  
  A2:2017-失效的身份認證:通常,通過錯誤使用應用程式的身份認證和會話管理功能,攻擊者能夠破譯密碼、金鑰或會話權杖,或者利用其它開發缺陷來暫時性或永久性冒充其他使用者的身份。  
  A3:2017-敏感性資料:許多Web應用程式和API都無法正確保護敏感性資料,例如:財務資料、醫療資料和PII資料。 攻擊者可 以通過竊取或修改未加密的資料來實施信用卡詐騙、身份盜竊或其他犯罪行為。未加密的敏感性資料容易受到破壞,因此,我們需要對敏感資料加密,這些資料包括:傳輸過程中的資料、存儲的資料 以及瀏覽器的交互資料。  
  A3:2017-敏感性資料洩露:許多Web應用程式和API都無法正確保護敏感性資料,例如:財務資料、醫療資料和PII資料。 攻擊者可以通過竊取或修改未加密的資料來實施信用卡詐騙、身份盜竊或其他犯罪行為。未加密的敏感性資料容易受到破壞,因此,我們需要對敏感資料加密,這些資料包括:傳輸過程中的資料、存儲的資料 以及瀏覽器的交互資料。  
  A4:2017-XML外部實體(XXE):許多較早的或配置錯誤的XML處理器評估了XML檔中的外部實體引用。 攻擊者可以利用外部實體竊 取使用URI檔處理器的內部檔和共用檔、監聽內部掃描埠、執行遠端代碼和實施拒絕服務攻擊。  
 A5:2017-失效的訪問控制:未對通過身份驗證的使用者實施恰當的存取控制。攻擊者可以利用這些缺陷訪問未經授權的功能或數 據,例如:訪問其他使用者的帳戶、查看敏感檔、修改其他使用者的資料、更改存取權限等。  
 A6:2017-安全配置錯誤:安全配置錯誤是最常見的安全問題,這通常是由於不安全的預設配置、不完整的臨時配置、開源雲存儲、錯誤的HTTP標頭配置以及包含敏感資訊的詳細錯誤資訊所造成的。因此,我們不僅需要對所有的作業系統、框架、庫和應用程式進行安全配置,而且必須及時修補和升級它們。  
 A7:2017-跨站腳本(XSS):當應用程式的新網頁中包含不受信任的、未經恰當驗證或轉義的資料時,或者使用可以創建 HTML或 JavaScript 的瀏覽器 API 更新現有的網頁時,就會出現 XSS 缺陷。 XSS 讓攻擊者能夠在受害者的瀏覽器 中執行腳本,並劫持使用者會話、破壞網站或將使用者重定向到惡意網站。
 A8:2017-不安全的反序列化:不安全的反序列化會導致遠端代碼執行。 即使反序列化缺陷不會導致遠端代碼執行,攻擊者也可以 利用它們來執行攻擊,包括:重播攻擊、注入攻擊和特權升級攻擊。    
 A9:2017-使用含有已知漏洞的元件:元件(例如:庫、框架和其他軟體模組)擁有和應用程式相同的許可權。如果應用程式中含有已知漏洞的元件被攻擊者利用,可能會造成嚴重的資料丟失或伺服器接管。同時,使用含有已知漏洞的組件的應用程式和API可能會破壞應用程式防禦、造成各種攻擊並產生嚴重影響。    
 A10:2017-不足的日誌記錄和監控:不足的日誌記錄和監控,以及事件回應缺失或不正確集成,使攻擊者能夠進一步攻擊系統、保持持續性或轉向更多系統,以及篡改、提取或銷毀資料。大多數缺陷研究顯示,缺陷被檢測出的時間超過200天,且通常通過外部檢測方檢測,而不是通過內部流程或監控檢測。  
 
 https://www.owasp.org/images/7/72/OWASP_Top_10-2017_%28en%29.pdf.pdf  
 https://www.owasp.org/images/5/58/OWASP_Top_10_2017_%E4%B8%AD%E6%96%87%E7%89%88v1.2.pdf  
 
 
 2013 

# 黑箱VS白箱測試 (必考題)
  Blackbox whilebox
  
 # 漏洞掃描
 
# 滲透測試 

# WAF
