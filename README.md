# 專案名稱 : 學校專題 - 打靶系統

開發環境 : Arduino IDE(硬體控制) . VS(網頁前端)

組員 : 110810549 . 110810551

![70](https://user-images.githubusercontent.com/36965820/149462050-26af5bb2-7412-4793-ba1e-4193f72008a3.jpg)


## Arduino程式簡介:

程式分為兩種類型:

1.硬體感應&控制
  ![72](https://user-images.githubusercontent.com/36965820/149460996-b9d64cfd-7ccb-4862-afc6-314f23bbea8d.jpg)


2.WiFi & MQTT(一種IoT間的通訊協定)連接

實際上的MQTT伺服器是用PC架設在同一個WiFi底下 . 不使用外網的公開伺服器
  ![71](https://user-images.githubusercontent.com/36965820/149461015-688cddfc-237c-4f31-b4c3-c3aa66c91550.jpg)

實際上要寫入的實體有:

1.標靶本體

工作內容 : 接收MQTT指令 > 硬體計分 > MQTT回傳分數

2.遙控器

工作內容 : 接收來自電腦的串列埠指令 > 發送MQTT指令 > 接收MQTT分數 > 用串列埠回傳電腦

## 網頁程式簡介:

1.主頁面

2.登入後的主頁面


