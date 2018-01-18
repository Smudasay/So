# คำสั่งพื้นฐาน การใช้ Git
## เป็นการเชื่อมต่อ local กับ Repository โดยการใช้การ remote

   git remote add origin "Ck1"
## เป็นการสร้างโฟลเดอร์ .git  ขึ้นมาโดยใช้คําสั่ง
   git init
## เป็นการเพิ่มไฟล์เข้าไปใน Repository | สามารถใช้ . แทนที่ชื่อไฟล์ จะเป็นการเพิ่มไฟล์ทั้งหมด
    git add README.md
## การเก็บข้อมูล
    git commit -m "Your Comment"
## การส่งข้อมูลจาก Local ไปยัง Repository | -u คือ จำ parameter origin master เอาไว้
   git push -u origin master
## การดึงข้อมูลจาก Repository มายัง Local
   git pull 
## Log out
git config --global --unset user.name
git config --global --unset user.email

