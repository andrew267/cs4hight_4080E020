# 網路硬體
```
Layer1 --->  repeater(1-1), hub(1-N)
Layer2 --->  bridgr, switch
Layer3 --->  router,L3-Switch
Layer4 --->  L4 switch
Layer7 --->  L7 switch, proxy
```
# 網路協定
### OSI MODEL
```
第7層 應用層（Application Layer）提供為應用軟體而設的介面，以設定與另一應用軟體之間的通訊。例如: HTTP，HTTPS，FTP，TELNET，SSH，SMTP，POP3.HTML.等。

第6層 表達層（Presentation Layer）把資料轉換為能與接收者的系統格式相容並適合傳輸的格式。

第5層 會議層（Session Layer）負責在資料傳輸中設定和維護電腦網路中兩台電腦之間的通訊連接。

第4層 傳輸層（Transport Layer）把傳輸表頭（TH）加至資料以形成資料包。傳輸表頭包含了所使用的協定等傳送資訊。例如:傳輸控制協定（TCP）等。

第3層 網路層（Network Layer）決定資料的路徑選擇和轉寄，將網路表頭（NH）加至資料包，以形成封包。網路表頭包含了網路資料。例如:網際網路協定（IP）等。

第2層 資料連結層（Data Link Layer）負責網路尋址、錯誤偵測和改錯。當表頭和表尾被加至資料包時，會形成影格。資料連結串列頭（DLH）是包含了實體位址和錯誤偵測及改錯的方法。資料連結串列尾（DLT）是一串指示資料包末端的字串。例如乙太網、無線區域網路（Wi-Fi）和通用分組無線服務（GPRS）等。

第1層 實體層（Physical Layer）在局部區域網路上傳送資料框（data frame），它負責管理電腦通訊裝置和網路媒體之間的互通。包括了針腳、電壓、線纜規範、集線器、中繼器、網卡、主機介面卡等。
```
```
0: Network Unreachable（無法到達目的網路）//
1: Host Unreachable（無法到達目的主機）
2: Protocol Unreachable（通訊協定不存在）
3: Port Unreachable（無法到達連接埠）
4: Fragmentation Needed and DF set（資料需分割並設定不可分割位元）
5: Source Route Failed（來源路徑選擇失敗）
6: Destination Network Unknown（無法識別目的地網路）
7: Destination Host Unknown（無法識別目的地主機）
8: Source Host Isolated（來源主機被隔離）
9: Communication with Destination Network Administratively Prohibited（管理上禁止和目的地網路通訊）
10: Communication with Destination Host Administratively Prohibited（管理上禁止和目的地主機通訊）
11: Network Unreachable for Type of Service（無法到達此型態的網路服務）
12: Host Unreachable for Type of Service（無法到達此型態的主機服務）
```