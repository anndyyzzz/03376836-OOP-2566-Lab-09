# 5.1
<img width="640" alt="Screenshot 2024-03-30 215050" src="https://github.com/anndyyzzz/03376836-OOP-2566-Lab-09/assets/144866059/d64bd0de-ee4a-40f1-9ec3-d1a73b8996bd">

# 5.2
<img width="637" alt="Screenshot 2024-03-30 215101" src="https://github.com/anndyyzzz/03376836-OOP-2566-Lab-09/assets/144866059/7e4c4305-f42f-40ae-8dbc-04df6cba7151">

#### ในการทดลองนี้ เราสร้างอ็อบเจกต์ sdRef จากคลาส SecondDerivedClass และทำการแปลงชนิดของ sdRef เป็น BaseClass โดยใช้การ casting (BaseClass) sdRef ซึ่ง BaseClass เป็นคลาสฐานของ SecondDerivedClass แต่เนื่องจากเมธอด Print() ใน SecondDerivedClass ไม่ได้รับการจับคู่ (override) กับเมธอด Print() ใน BaseClass หรือ DerivedClass จึงไม่สามารถเรียกใช้ได้ผ่านทางตัวแปร bcRef ที่ถูกแปลงเป็น BaseClass โดยการแปลงชนิด ผลลัพธ์ที่พิมพ์ออกทางหน้าจอจะเป็น "Hello from SecondDerivedClass" สำหรับ sdRef.Print() และ "Hello from BaseClass" สำหรับ bcRef.Print() โดยใช้การเรียกเมธอดที่เป็นของ BaseClass ที่ถูกแปลงแล้ว
