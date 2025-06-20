
# README.md สำหรับเว็บไซต์ Wong Nok - สูตรอาหาร
*******************************************************************************************************************************************************************
เว็บไชด์ wong nok  เป็นเว็บไชด์แชร์สูตรอาหารเขียนด้วยโปรแกรม html,css,javascrip, node js, mysql

เว็บไซด์ Wong Nok  เป็นเว็บไซต์สูตรอาหารไทยและนานาชาติที่ออกแบบมาสำหรับคนรักการทำอาหารทุกระดับ โดยมีฟีเจอร์ต่างๆ เช่น:

แสดงสูตรอาหารแนะนำ

หมวดหมู่สูตรอาหาร

สูตรอาหารยอดนิยม

สูตรอาหารทำเร็ว

ระบบค้นหาสูตรอาหาร

*******************************************************************************************************************************************************************

## 🎨 ฟีเจอร์หลัก

### 1. ระบบนำทาง

-   เมนู responsive ที่ปรับตามขนาดหน้าจอ
    
-   ช่องค้นหาสูตรอาหาร
    
-   ปุ่มเข้าสู่ระบบ/สมัครสมาชิก
    

### 2. Hero Banner

-   ส่วนแนะนำเว็บไซต์พร้อมภาพพื้นหลังสวยงาม
    
-   ตัวกรองค้นหาสูตรอาหาร (เวลาเตรียมอาหาร, ระดับความยาก)
    

### 3. ส่วนแสดงสูตรอาหาร

-   **สูตรอาหารแนะนำ**: แสดงในรูปแบบการ์ด responsive
    
-   **หมวดหมู่สูตรอาหาร**: แสดงเป็นกริดวงกลม
    
-   **สูตรอาหารยอดนิยม**: แสดงเป็นลิสต์เรียงลำดับ
    
-   **สูตรอาหารทำเร็ว**: แสดงในรูปแบบ compact
    

### 4. Footer

-   ข้อมูลเกี่ยวกับเว็บไซต์
    
-   ลิงก์ด่วน
    
-   ไอคอนโซเชียลมีเดีย
  *******************************************************************************************************************************************************************

## 📱 Responsive Design

เว็บไซต์ถูกออกแบบให้รองรับทุกระดับหน้าจอ:

-   **Desktop**: แสดงเนื้อหาเต็มรูปแบบ
    
-   **Tablet**: ปรับเลย์เอาต์สำหรับหน้าจอขนาดกลาง
    
-   **Mobile**: เมนูแบบฮัมเบอร์เกอร์และปรับเลย์เอาต์ให้เหมาะกับมือถือ
    
*******************************************************************************************************************************************************************

## ✨ ฟีเจอร์ในอนาคต

-   ระบบล็อกอิน/สมัครสมาชิกจริง
    
-   ระบบคอมเมนต์และให้คะแนนสูตรอาหาร
    
-   ระบบบันทึกสูตรอาหารโปรด
    
-   ระบบแชร์สูตรอาหารผ่านโซเชียลมีเดีย
 
*******************************************************************************************************************************************************************
🛠️ เทคโนโลยีที่ใช้

-   **Frontend**: HTML5, CSS3, JavaScript
    
-   **Fonts**: Sarabun,kanit (จาก Google Fonts) 
    
-   **Icons**: Font Awesome 6
    
-   **Responsive Design**: รองรับทุกระดับหน้าจอ (Mobile, Tablet, Desktop)
    

****************************************************************************************************************************************************************
-โครงสร้างเพจและการใช้งาน-

wong-nok/

├── client/                  # ส่วน Frontend

│   ├── public/              # ไฟล์สาธารณะ

│   ├── src/                 # ซอร์สโค้ดหลัก

│   │   ├── assets/          # ไฟล์สื่อ

│   │   ├── components/      # คอมโพเนนต์

│   │   ├── pages/           # หน้าเว็บ

│   │   └── styles/          # สไตล์

├── server/                  # ส่วน Backend

│   ├── controllers/         # ควบคุมการทำงาน

│   ├── models/              # โมเดลข้อมูล

│   ├── routes/              # เส้นทาง API

│   └── config/              # การตั้งค่า

├── docker-compose.yml       # คอนฟิก Docker

└── README.md                # เอกสารนี้


(http://127.0.0.1:5500/html+css..html)    เพจหลัก 

 (http://127.0.0.1:5500/remember.html) สมัครสมาชิก

(http://127.0.0.1:5500/loginwongnok.html) เข้าสู่ระบบเป็นสมาชิกแล้ว

(http://127.0.0.1:5500/my_recipes.html)  หน้าสูตรอาหารสมาชิก

(http://127.0.0.1:5500/%E0%B8%B7new_recipes.html)  หน้าสร้างสูตรใหม่ของสมาชิก


(http://127.0.0.1:5500/tom-yumkok.html) สูตรอาหารแนะนำต้มยำกุ้ง

(http://127.0.0.1:5500/padthai.html) สูตรอาหารแนะนำผัดไทย

(http://127.0.0.1:5500/green-curry-chicken.html) สูตรอาหารแนะนำแกงเขียวหวานไก่


(http://127.0.0.1:5500/som-tum-thai.html) สูตรอาหารแนะนำส้มตำไทย

(http://127.0.0.1:5500/Recipe%20Gallery%20Page.html) หน้ารวมสูตรอาหาร

(http://127.0.0.1:5500/Food%20Categories%20.html)  รวมหมวดอาหาร


(http://127.0.0.1:5500/thai%20food.html)  สูตรอาหารไทยแบ่งตามภาค


(http://127.0.0.1:5500/international-food.html) สูตรอาหารนานาชาติ
   
(http://127.0.0.1:5500/healthy-food.html ) สูตรอาหารสุขภาพ

(http://127.0.0.1:5500/dessert.html) สูตรของหวาน

(http://127.0.0.1:5500/drink%20fd.html) สูตรเครื่องดื่ม

(http://127.0.0.1:5500/dish%20meal.html) สูตรอาหารอาหารจานเดียว

(http://127.0.0.1:5500/pad-kung.html ) สูตรอาหารนิยม ข้าวผัดกุ้ง

(http://127.0.0.1:5500/ducury.html) สูตรอาหารนิยมแกงเผ็ดเป็ดย่าง


(http://127.0.0.1:5500/%E0%B8%B7noder.html) สูตรอาหารนิยมยำวุ้นเส้นกุ้งสด 


(http://127.0.0.1:5500/pork%20cury.html) สูตรอาหารนิยมผัดกระเพราหมู


(http://127.0.0.1:5500/cury%20cheken.html) สูตรอาหารนิยมต้มข่าไก่


(http://127.0.0.1:5500/egg.html)   สูตรอาหารทำเร็ว ไข่ดาวกรอบ

(http://127.0.0.1:5500/sesar.html ) สูตรอาหารทำเร็วสลัดซีซาร์



*****************************ส่วนอื่นๆจะพัฒนาในลำดับต่อไปครับ*********************************************************************************************

## 🚀 วิธีติดตั้งและรันโปรเจกต์

1.ติดตั้ง dependencies:


npm install

cd client && npm install

cd ../server && npm install

2.ตั้งค่าฐานข้อมูล MySQL ในไฟล์ server/config/database.js

3.รันเซิร์ฟเวอร์:


#backend

cd server && npm start

#frontend (ใน terminal อื่น)

4.การใช้งาน Docker


docker-compose up --build

5.เปิดไฟล์ index.html ในเบราว์เซอร์

หรือสามารถเปิดผ่าน Live Server ใน VS Code ได้




(https://github.com/hnume/500990-wongnok-recipes/blob/main/Recording%202025-05-23%20200614.mp4)

การrun node js  

(https://github.com/hnume/500990-wongnok-recipes/blob/main/%E0%B8%81%E0%B8%B2%E0%B8%A3run%20page2.mp4)

การ run page โดยการเปิดผ่าน VS code 

88888888888 คลิ๊กที่ View raw และบันทึก วีดีโอ
*******************************************************************************************************************************************************************
🏗️ สถาปัตยกรรมระบบ



![deepseek_mermaid_20250523_b0c977](https://github.com/user-attachments/assets/1e14a616-c303-481b-b0b3-b83491e2ad01)



    
    A[Client] -->|HTTP Requests| B[Node.js Server]
    B -->|Query| C[MySQL Database]
    B -->|API Calls| D[External Services]

















## 🤝 การมีส่วนร่วม

สามารถ Fork และ Submit Pull Request ได้ที่  [ git clone https://github.com/hnume/500990-wongnok-recipes.git)


## 📜 ใบอนุญาต

โปรเจกต์นี้อยู่ภายใต้ใบอนุญาต (https://www.facebook.com/thwich.paks.i?locale=th_TH)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

พัฒนาโดย [นายทวิช ศรีจันทร์] · © 2023 Wong Nok
เว็บไชด์ wong nok เป็นเว็บไชด์แชร์สูตร อาหารด้วยโปรแกรม html css javascrip node js mysql










****************************************องค์ความรู้อื่นๆ************************************************************************

# Web development 101 series - Source code

Project นี้เป็น project ที่รวม source code สำหรับประกอบหัวข้อ Web development 101 series

ประกอบไปด้วยหัวข้อทั้งหมด 12 เรื่อง
✅✅✅✅✅✅✅✅✅✅✅✅

## Full documentation
สามารถตามอ่านกันได้ที่
(https://docs.mikelopster.dev/c/web101/intro)

## Video session
|ตอนที่|หัวข้อ|วิดีโอ|เอกสาร|
|---|----------|---|---|
|ตอนที่ 1| Introduction to Web dev | [![intro-to-web-dev](https://img.youtube.com/vi/LSzYxSiZxNs/mqdefault.jpg)](https://youtu.be/LSzYxSiZxNs) [ดู video](https://youtu.be/LSzYxSiZxNs)| done
| ตอนที่ 2| First step with HTML | [![first-step-with-html](https://img.youtube.com/vi/bPsj3DP98Uc/mqdefault.jpg)](https://youtu.be/bPsj3DP98Uc) [ดู video](https://youtu.be/bPsj3DP98Uc)| done
|ตอนที่ 3 | Basic CSS | [![basic-css](https://img.youtube.com/vi/KCYxFXIAn_4/mqdefault.jpg)](https://youtu.be/KCYxFXIAn_4) [ดู video](https://youtu.be/KCYxFXIAn_4) | done
| ตอนที่ 4 | CSS Responsive | [![css-responsive](https://img.youtube.com/vi/4f5Nd0AtLp0/mqdefault.jpg)](https://youtu.be/4f5Nd0AtLp0) [ดู video](https://youtu.be/4f5Nd0AtLp0) | in progress
| ตอนที่ 5 | Javascript (Basic programming) | [![basic-javascript](https://img.youtube.com/vi/XQdyV_x4UKA/mqdefault.jpg)](https://youtu.be/XQdyV_x4UKA) [ดู video](https://youtu.be/XQdyV_x4UKA) | in progress
| ตอนที่ 6 | Javascript - DOM and Event |  [![dom-event-javascript](https://img.youtube.com/vi/XjK3cRbjblw/mqdefault.jpg)](https://youtu.be/XjK3cRbjblw) [ดู video](https://youtu.be/XjK3cRbjblw) | done
| ตอนที่ 7 | Nodejs - Introduction Backend | [![nodejs-backend](https://img.youtube.com/vi/sn1UUN4ADFE/mqdefault.jpg)](https://youtu.be/sn1UUN4ADFE) [ดู video](https://youtu.be/sn1UUN4ADFE) | done
| ตอนที่ 8 | Mysql - Basic database | [![mysql-database](https://img.youtube.com/vi/ofWRV8dpVqo/mqdefault.jpg)](https://youtu.be/ofWRV8dpVqo) [ดู video](https://youtu.be/ofWRV8dpVqo) | done
| ตอนที่ 9 | Express - REST API | [![express-rest-api](https://img.youtube.com/vi/C5kv44Srv7w/mqdefault.jpg)](https://youtu.be/C5kv44Srv7w) [ดู video](https://youtu.be/C5kv44Srv7w) | done
| ตอนที่ 10 | Express - API connect Mysql | [![api-connect-mysql](https://img.youtube.com/vi/Gjwnucvv3iY/mqdefault.jpg)](https://youtu.be/Gjwnucvv3iY) [ดู video](https://youtu.be/Gjwnucvv3iY) | done
| ตอนที่ 11 | Javascript - Integration API | [![javascript-integration-api](https://img.youtube.com/vi/A_fo3sRr_Go/mqdefault.jpg)](https://youtu.be/A_fo3sRr_Go) [ดู video](https://youtu.be/A_fo3sRr_Go) | done
| ตอนที่ 12 | What's next : Git, Web framework, Web deployment | [![whats-next-web-dev](https://img.youtube.com/vi/Ieh55Nykr3Q/mqdefault.jpg)](https://youtu.be/Ieh55Nykr3Q) [ดู video](https://youtu.be/Ieh55Nykr3Q) | done




