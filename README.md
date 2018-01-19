# Basic Git
### เป็นการเชื่อมต่อ local กับ Repository โดยการใช้การ remote
* git remote add origin "https://github.com/Smudasay/Soft-D.git"
### เป็นการสร้างโฟลเดอร์ .git  ขึ้นมาโดยใช้คําสั่ง
* git init
### เป็นการเพิ่มไฟล์เข้าไปใน Repository | สามารถใช้ . แทนที่ชื่อไฟล์ จะเป็นการเพิ่มไฟล์ทั้งหมด
* git add README.md
### เป็นการเก็บข้อมูล
* git commit -m "Your Comment"
### เป็นการส่งข้อมูลจาก Local ไปยัง Repository | -u คือ จำ parameter origin master เอาไว้
* git push -u origin master
### เป็นการดึงข้อมูลจาก Repository มายัง Local
* git pull
### เป็นการเอาข้อมูลจาก github ลงคอม หรือเอาจากคอมใส่ guthub
git clone "https://github.com/Smudasay/Soft-D.git"
### เป็นการ Log out 
* git config --global --unset user.name

* git config --global --unset user.email
### discard edit กลับค่าเดิม
* git checkout nameไฟล์
### discard add เพิ่มสถานะ
* ต้อง git add test.txt ตามด้วย git reset HEAD test.txt
### discard commit คือการลกเลิกการ commit
* git reset --soft "HEAD"
### ลบไฟล์
git rm HEAD test.txt
### recovery เอาไฟล์ที่ลบกลับมา
* git reset HEAD test.txt
* git checkout test.txt
### เป็นการเพิ่มไฟล์โดยไม่ทับไฟล์เก่า
* git add .
* git tash //hide your update 
* git pull
* git stash pop //recover file
* git add .
* git commit -m "cccc"
* git push
### branch เป็นทำการที่ทำงานแยกกัน แต่เราสามารถมารสมกันได้
* git branch Say //สร้าง branch
* git checkout
* git checkout -b Say //สร้าง branch
* git branch -a //list branch

* git branch dev //create branch

* git merge Say //รวม
* git branch -d Say //ลบ branch
# คำสั่งหลักๆ ในการใช้ add
* git add .
* git commit -m "SSSSS"
* git push

