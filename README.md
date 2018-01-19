
# Basic Git
## เป็นการเชื่อมต่อ local กับ Repository โดยการใช้การ remote
* git remote add origin "https://github.com/Smudasay/Soft-D.git"
## เป็นการสร้างโฟลเดอร์ .git  ขึ้นมาโดยใช้คําสั่ง
* git init
## เป็นการเพิ่มไฟล์เข้าไปใน Repository | สามารถใช้ . แทนที่ชื่อไฟล์ จะเป็นการเพิ่มไฟล์ทั้งหมด
* git add README.md
## เป็นการเก็บข้อมูล
* git commit -m "Your Comment"
## เป็นการส่งข้อมูลจาก Local ไปยัง Repository | -u คือ จำ parameter origin master เอาไว้
* git push -u origin master
## เป็นการดึงข้อมูลจาก Repository มายัง Local
* git pull
## เป็นการเอาข้อมูลจาก github ลงคอม หรือเอาจากคอมใส่ guthub
git clone "https://github.com/Smudasay/Soft-D.git"
## เป็นการ Log out 
* git config --global --unset user.name

* git config --global --unset user.email
## discard edit กลับค่าเดิม
* git checkout nameไฟล์
## discard add เพิ่มสถานะ
* ต้อง git add test.txt ตามด้วย git reset HEAD test.txt
## discard commit คือการลกเลิกการ commit
* git reset --soft "HEAD"
