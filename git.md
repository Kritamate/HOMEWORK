1.git clone : link git

2.git > ชื่อไฟล์ที่จะสร้าง

3.git add ชื่อไฟล์ที่จะเเอดไปที่ github

4.git commit -m "หมายเหตุ"

5.git push -u origin master 

6.git push (ถ้าใช้git push -u origin master มาเเล้ว )

7.git checkout ชื่อไฟล์ที่ต้องการย้อนกลับเเบบเดิมหลังจากทำการเเก้ไข

8.git reset HEAD ชื่อไฟล์ที่ถูก git add เเล้วจะยกเลิกการ add

9.git reset --soft "HEAD^" (ยกเลิกการ commit)

10.git rm ชื่อไฟล์ที่ต้องการลบ

11.git reset HEAD ชื่อไฟล์ที่ต้องการกู้กลับมาจากที่ลบไปเเล้ว

git add .
git stash  # hide your update
git pull
git stash pop # recover file
git add 
git commit -m "..."
git push 