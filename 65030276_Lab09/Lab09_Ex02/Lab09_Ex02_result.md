# 2.1
<img width="637" alt="Screenshot 2024-03-30 214000" src="https://github.com/anndyyzzz/03376836-OOP-2566-Lab-09/assets/144866059/0824e4ea-ef77-42c6-9228-1059f7f20d20">

# 2.2
<img width="642" alt="Screenshot 2024-03-30 214009" src="https://github.com/anndyyzzz/03376836-OOP-2566-Lab-09/assets/144866059/5fdf9fa0-4ebc-42f1-b98d-b95706517d69">

#### ในการทดลองนี้ เราสร้างอ็อบเจกต์ dcRef จากคลาส DerivedClass และเรามีการแปลงชนิดของ dcRef ไปเป็น BaseClass โดยการใช้ casting (BaseClass) dcRef ซึ่ง BaseClass เป็นคลาสฐานของ DerivedClass จากนั้นเราเรียกใช้เมธอด Info() ผ่านทั้ง dcRef และ bcRef ตามลำดับ ซึ่งจะเห็นว่าผลลัพธ์ที่พิมพ์ออกทางหน้าจอจะเป็น "This is DerivedClass" สำหรับ dcRef.Info() และ "This is DerivedClass" สำหรับ bcRef.Info() แสดงให้เห็นว่าการแปลงชนิดของอ็อบเจกต์จาก DerivedClass เป็น BaseClass ไม่ส่งผลต่อการเรียกใช้เมธอดที่ถูกทับใน DerivedClass ซึ่งเป็นพฤติกรรมที่คาดเดาได้โดยตรงในการสืบทอดแบบไดนามิกใน C#
