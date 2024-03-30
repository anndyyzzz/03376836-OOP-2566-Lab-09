# 4.1
<img width="635" alt="Screenshot 2024-03-30 214732" src="https://github.com/anndyyzzz/03376836-OOP-2566-Lab-09/assets/144866059/bc7cc274-d8a3-4df9-835b-5da8e4fe4fa2">

# 4.2
<img width="640" alt="Screenshot 2024-03-30 214746" src="https://github.com/anndyyzzz/03376836-OOP-2566-Lab-09/assets/144866059/8e347135-2270-47d4-9427-92de485ec99d">

#### ในการทดลองนี้ เราสร้างอ็อบเจกต์ sdRef จากคลาส SecondDerivedClass และทำการแปลงชนิดของ sdRef เป็น BaseClass โดยใช้การ casting (BaseClass) sdRef ซึ่ง BaseClass เป็นคลาสฐานของ SecondDerivedClass แต่เนื่องจากเมธอด Print() ใน SecondDerivedClass ไม่ได้รับการจับคู่ (override) กับเมธอด Print() ใน BaseClass หรือ DerivedClass จึงไม่สามารถเรียกใช้ได้ผ่านทางตัวแปร bcRef ที่ถูกแปลงเป็น BaseClass โดยการแปลงชนิด ดังนั้น ผลลัพธ์ที่พิมพ์ออกทางหน้าจอจะเป็น "Hello from SecondDerivedClass" สำหรับ sdRef.Print() แต่สำหรับ bcRef.Print() จะไม่สามารถเรียกใช้เมธอด Print() ใน SecondDerivedClass ได้ ซึ่งทำให้โปรแกรมไม่สามารถคอมไพล์ได้ถูกต้องโดยมีข้อผิดพลาดที่เกิดขึ้นในบรรทัดที่ bcRef.Print() นั่นเอง
