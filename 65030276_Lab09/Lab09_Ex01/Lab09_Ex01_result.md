# 1.1
<img width="640" alt="Screenshot 2024-03-30 213741" src="https://github.com/anndyyzzz/03376836-OOP-2566-Lab-09/assets/144866059/bccb12b3-bfc0-4361-97b5-3dab1cee22ee">

# 1.2
<img width="643" alt="Screenshot 2024-03-30 213750" src="https://github.com/anndyyzzz/03376836-OOP-2566-Lab-09/assets/144866059/30cdb51a-6eff-4160-a5d9-a3ace94f868a">

#### ในการทดลองนี้ เราสร้างคลาส BaseClass และ DerivedClass โดย DerivedClass สืบทอดจาก BaseClass ซึ่ง Info() เป็นเมธอดเสมือนที่ถูกสร้างขึ้นใน BaseClass และถูกเขียนทับใน DerivedClass ซึ่งเราใช้คีย์เวิร์ด virtual ใน BaseClass เพื่อให้เป็นเมธอดที่สามารถถูกซ่อนแทนได้ และใช้คีย์เวิร์ด override ใน DerivedClass เพื่อบอกว่าเรากำลังทับเมธอดจาก BaseClass ดังนั้น เมื่อเรียกใช้ Info() ผ่านอ็อบเจกต์ของ DerivedClass จะเรียกใช้เมธอดที่ถูกทับใน DerivedClass และเมื่อเรียกใช้ผ่านอ็อบเจกต์ของ BaseClass จะเรียกใช้เมธอดใน BaseClass ผลลัพธ์ที่พิมพ์ออกทางหน้าจอจะเป็น "This is DerivedClass" สำหรับ dcRef.Info() และ "This is BaseClass" สำหรับ bcRef.Info() ตามลำดับ ซึ่งแสดงให้เห็นถึงการทับเมธอดในการสืบทอดและพฤติกรรมของเมธอดเสมือนในภาษา C#
