Run Ubunt 20 แล้วติดตั้ง Application Apache2 และ Git
ทำการ pull ตัว Repository จาก GitHub ของตัวเองมา Run
เริ่มต้นด้วยการสมัคร github และสร้าง repository Sync กับโปรไฟล์บน Visual Studio code ไฟล์ index.html เป็นไฟล์หน้าเว็บที่จะแสดงชื่อ นามสกุล และรหัสนักศึกษา
เปิด Ubuntu แล้วติดตั้ง Application apache2 และ git แล้วหา Ip ของเราด้วยคำสั่ง ip a แล้วนำ ip ของเราไปใส่ใน Web browser
ถ้าไม่ได้ที่ต้องการให้ start หรือ restart apache2 ก่อน  
เราก็ทำการนำ file เว็บที่เราทำมา erplace ที่ /var/www/html/index.html โดย sudo mv index.hyml1 /var/www/html.index
