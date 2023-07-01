# PartInfoREV2
VBA SolidWork สำหรับ add custom probperty



สำหรับไฟล์ที่จำเป็น

UserForm1
"C:\Macro\material.txt"
"C:\Macro\surfacetreatment.txt"
"C:\Macro\hardness.txt"
"C:\Macro\prepared.txt"
"C:\Macro\checked.txt"
"C:\Macro\approved.txt"
"C:\Macro\brand.txt"
"C:\Macro\save.txt"

UserForm2
"C:\Macro\buffer.txt"

Folder
"C:\Macro"

# การนำไปใช้งาน
1. ไฟล์ต้องอยู่ใน Foder "C:\Macro"
2. เพิ่ม Macro ลงใน SolidWork
3. คลิกขวาที่ ribbon เลือก Customize...
4. เลือก New Tab --> Empty Tab ตั้งชื่อเป็น Macro
5. ที่หน้าต่าง Customize เลือก commands --> Macro --> New Macro Button --> C:\Macro\PartInfoREV2.swp


   
![Untitled1](https://github.com/Jacop1989/PartInfoREV2/assets/31177652/eac93f04-aa6b-4be4-ad61-12456c414aef)

![Untitled2](https://github.com/Jacop1989/PartInfoREV2/assets/31177652/13cb0fff-112c-441b-ab33-4204e353fb17)

![Untitled3](https://github.com/Jacop1989/PartInfoREV2/assets/31177652/b668c4d2-b533-45e6-a22b-1d2bec7133f1)

![Untitled4](https://github.com/Jacop1989/PartInfoREV2/assets/31177652/477462e4-677a-4ef0-a3d9-93f3e316d993)



# วิธีใช้
1. ถ้าเป็นไฟล์ Part เราจะ save ไฟล์ให้เรียบร้อยก่อน ลองดูที่
 ![Untitled5](https://github.com/Jacop1989/PartInfoREV2/assets/31177652/36cb918f-6051-4d2f-9bb7-ffc1efe2341d)
  
## File Properties
![Untitled6](https://github.com/Jacop1989/PartInfoREV2/assets/31177652/004f84a4-256e-43a5-ba27-434adad26fdb)
ตอนนี้ว่างเปล่าไม่มีอะไร
2. ไปที่ Tab Macro ที่เราสร้าง PartInfoREV2 --> Add Custom
![Untitled7](https://github.com/Jacop1989/PartInfoREV2/assets/31177652/48bb301a-f5c7-4739-bc8d-9d77d5c426de)

3. ไป check ที่ File Properties อีกครั้ง

   ![Untitled8](https://github.com/Jacop1989/PartInfoREV2/assets/31177652/05192229-7a45-46eb-84fa-cba9fd141d68)

4. Custom Properties ถูกเพิ่มเข้าไปแล้ว
5. ลองกรอกข้อมูล
   
![Untitled10](https://github.com/Jacop1989/PartInfoREV2/assets/31177652/640b0412-cec8-479c-a3db-065a228e15b4)

6. กรอกเสร็จ กด Save ตัวที่ common ที่เราใช้กับ Part อื่นจะถูกบันทึกลง text file "C:\Macro\save.txt" ถ้าเรามี part ใหม่ให้กด import ตัวที่ common ก็จะเพิ่มให้เรา
   ![Untitled11](https://github.com/Jacop1989/PartInfoREV2/assets/31177652/4b60f228-a66e-420d-bb4f-473577c3dac0)

   ![Untitled12](https://github.com/Jacop1989/PartInfoREV2/assets/31177652/2f9293f7-220f-4e4d-b8e8-6a25f6365927)

