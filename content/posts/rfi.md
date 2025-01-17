---
title: "我的短波 RFI 解決方案"
date: 2024-10-24T13:59:40+08:00
draft: false
toc: false
images:
tags:
  - 業餘無線電
  - 短波
---
## 前言
> 由於 RF 射頻有許多的變因存在，筆者可行的方法未必 100 % 有用。如有錯誤之處敬請指教。

筆者喜歡玩短波數據模式，因此需把 IC-7300 接到 PC ，但遇到了好幾種干擾，經由不斷的測試以及社群前輩的建議，最終成功讓無線電在 80 米到 6 米發射都不會出現干擾。
## 我的天線與天調
筆者的天線使用重慶火腿生產的 DKGP10 天線，該天線的構造為一個 5.6 米的伸縮桿套上水管並且引出「空中電力線」到它附贈的手動天線調諧器上；但我買了 AH-3 自動天線調諧器，所以直接電力線接到 2 樓的天調。
![picture 0](https://yakumotw.s3.ap-northeast-1.amazonaws.com/e27bd35a781c04c8b5bb9523cc8a704ce1dc62d5f580ca2531e4b6511730720c.jpg)  

筆者天調放置的位置於二樓陽台。
![picture 1](https://yakumotw.s3.ap-northeast-1.amazonaws.com/1730c9ef6c086c9ebf772a37d11f9247c1e93039e416acff60afed2980433d5a.jpg)  

天調的地網。
![圖 0](https://yakumotw.s3.ap-northeast-1.amazonaws.com/c926da06051201c9cf8b2d7fa64af832218465e8536a8eb723aa61a08ed6fd86.jpg)  

拉進室內的書房。

![圖 3](https://yakumotw.s3.ap-northeast-1.amazonaws.com/04edaee4a84df4b0cbc4f2df384733ebc49a6908aa2917bf3f1c5d26e2924b91.jpg)  

## 發射時產生的干擾的症狀
剛開始安裝完成後會產生以下干擾問題。
 
### 電源干擾
由 IC-7300 的電源線灌回電源供應器並且干擾同一個延長線插座的設備。
* 干擾的症狀：
1. 電腦輸出的聲音有電流聲。
2.  SIP 網路電話機聽筒也有哼聲。

### USB 斷線
應該是射頻干擾到 USB 的傳輸。
* 干擾的症狀：
1. 一發射 USB 就斷線。
2. 使用筆電可能會導致觸控板失靈以及螢幕異常，嚴重可能會把筆電觸控板搞壞。
### 接收的干擾
除此之外當 IC-7300 接上電腦，頻譜上會出現大小程度不同的干擾，以筆者的經驗頻率越低干擾越嚴重。
## 筆者的解決方法
經過無數次的實驗與調整，我終於解決了長期以來的問題。
1. 不要跟電腦設備插同一排延長線，改插到旁邊牆壁的插座。
2. 在靠近電供端的電源線繞一個磁環([FT-140-43 磁環](https://world.taobao.com/item/3696064077.htm))。
![picture 2](https://yakumotw.s3.ap-northeast-1.amazonaws.com/4ec77fbfdd83bd3a745630118c6c9e86a30ac924f5560d9e953abd8e263b74d8.jpg)  
> 目前實測雖在 40 米波以下不會產生干擾，但是磁環在發射時會有發熱的現象，因此需注意發射時間。
3. 依照前輩建議把 USB 傳輸線換成 [LINDY](https://s.shopee.tw/3flv2qsqwL) 牌的傳輸線。
4. 最後在 IC-7300 那側以及電腦側的傳輸線上面繞上 [FT-140-43 磁環](https://world.taobao.com/item/3696064077.htm)

![圖 1](https://yakumotw.s3.ap-northeast-1.amazonaws.com/5b891e8346fd24f4d6afcca49344089ae4f7b5acce1ee7fff775ca77cd8acd1b.jpg) 
 
![圖 2](https://yakumotw.s3.ap-northeast-1.amazonaws.com/60cad495ae8da3b488669d11d72cf45535f734a42e9efeb69b95b71b72fa5da7.jpg)  

5. 調整天調地網的長度。


