# 定義寬頻使用 QoE (使用者體驗品質) 的優劣標準

## 概要
本專案旨在定義和評估網路使用中的 QoE（使用者體驗品質）標準。用於提高網路服務質量之決策。

## 階段描述
![QoE分析流程 drawio](https://github.com/Beiiscoming/Defining-QoE-Standards-for-Network-Usage/assets/171532457/526ac88c-62a4-40da-a55e-63fefef91268)

## QoE (Quality of Experience) 計算公式

使用者體驗品質 (Quality of Experience, QoE) 是衡量網路服務品質的重要指標之一。其計算公式如下：

$$
QoE = 100 \times \frac{\text{Packets expected} - \text{Packets lost}}{\text{Packets expected}}
$$

### 公式解釋
- **預期封包數量 (Packets expected)**: 是指在網絡傳輸過程中，根據協議和設計應該成功傳輸到接收端的封包總數量。這個數量通常是在沒有丟失封包的理想情況下預期的數值。
- **丟失封包數量 (Packets lost)** 是指在網絡傳輸過程中，因各種原因未能成功到達接收端的封包數量。這些原因可能包括網絡擁堵、錯誤、干擾等。
- **封包 (Packet)**: 網絡數據通訊中的基本單位，是一小段經過打包處理的數據，包含了需要傳輸的數據及其相關的控制訊息。每個封包在網路中被傳輸，並在目的地重新組裝成原始數據。

### 資料說明
![QoE分析流程-資料說明](https://github.com/Beiiscoming/Defining-QoE-Standards-for-Network-Usage/assets/171532457/6adf622a-f6ff-43c4-9ce7-7c60d01fc3db)


