# 3.1
<img width="638" alt="Screenshot 2024-03-30 214510" src="https://github.com/anndyyzzz/03376836-OOP-2566-Lab-09/assets/144866059/38379591-18f7-4683-af56-93cd6716dccd">

# 3.2
<img width="634" alt="Screenshot 2024-03-30 214524" src="https://github.com/anndyyzzz/03376836-OOP-2566-Lab-09/assets/144866059/a391e4ea-b763-497f-be1f-f2d1ea27990a">

### ในการทดลองนี้ เราสร้างอ็อบเจกต์ sdRef จากคลาส SecondDerivedClass และทำการแปลงชนิดของ sdRef เป็น BaseClass โดยใช้การ casting (BaseClass) sdRef ซึ่ง BaseClass เป็นคลาสฐานของ SecondDerivedClass จากนั้นเราเรียกใช้เมธอด Print() ผ่านทั้ง sdRef และ bcRef ตามลำดับ ผลลัพธ์ที่พิมพ์ออกทางหน้าจอจะเป็น "Hello from SecondDerivedClass" สำหรับ sdRef.Print() และ "Hello from SecondDerivedClass" สำหรับ bcRef.Print() แสดงให้เห็นว่าการแปลงชนิดของอ็อบเจกต์จาก SecondDerivedClass เป็น BaseClass ไม่ส่งผลต่อการเรียกใช้เมธอดที่ถูกทับใน SecondDerivedClass ซึ่งเป็นพฤติกรรมที่คาดเดาได้โดยตรงในการสืบทอดแบบไดนามิกใน C#
