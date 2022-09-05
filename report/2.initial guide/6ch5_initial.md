## step
- [ ] copy ตัวอย่างมา
#### ลบ
- [ ] ลบคำอธิบาย
- [ ] ลบ Affect system, IP Address/Domein เอาจากใน bug track มาใส่
- [ ] ลบ step to reproduce
- [ ] ลบ recommended solution
- [ ] ลบ risk rating ประเมิน 
- [ ] เอาสีออก
#### ต้องใส่
- [ ] ใส่ Affect system, IP Address/Domein เอาจากใน bug track มาใส่
- [ ] ใส่ step to reproduce
- [ ] ใส่ recommended solution
- [ ] ใส่ overall,impact,likelyhood และ description
- [ ] ใส่สีใหม่ 
- [ ] ใส่ cvss ใหม่

## 1.Finding
- ตอนเริ่มอธิบายควรเล่าว่าต้องเข้าไปที่ URL อะไร หรือถ้าเป็นแอปมือถือ ต้องใช้เปิดใช้งานหน้าจอแอปเข้าไปที่เมนูที่มีช่องโหว่ยังไง
- ชื่อช่องโหว่ ใช้ชื่อเดียวกันกับใน Bug Tracker
- เวลาเขียน อธิบายช่องโหว่ ควรมีส่วนประกอบ 3 อย่างคือ
	1. แนะนำ background ของระบบหรือฟีเจอร์ ที่มีช่องโหว่ว่าคืออะไร เป็นยังไง
	2. อธิบายช่องโหว่ที่เจอว่าจากสิ่งที่เราเกริ่นไปในข้อแรกนั้นมีปัญหาอะไร
	3. พิสูจน์ด้วยหลักฐานว่า ช่องโหว่ที่เราอธิบายมีอยู่จริง
- **White Box** ต้องใส่ชื่อไฟล์และโค้ดที่มีช่องโหว่ด้วย (ถ้ามีหลายจุด เลือกตัวอย่างโค้ดมา 1 จุดที่รุนแรงสูงสุด)
```
URL: https://sdh.com/forget-password
File: /sdh/src/UserForgetPasswordPOST.js
```

## 2.Recommended Solutions 
มีใน template ถ้าไม่มีลองถามดู 
เขียน example ของปัญหาด้วยก็ดี for example

## 3.Risk Rating
- ควรจะประเมินเองทุกครั้ง 

**Impact factor:** 
ถ้าโดนโจมตีจะเกิดอะไรขึ้น มีใน template ถ้าเป็นอันแปลกๆเขียนเอง (อ่านก่อนเสมอ)
สั้นๆง่ายๆว่า จะเกิดอะไรขึ้น

**Likelihood factor:** 
condition ในการโจมตี มีใน template ถ้าเป็นอันแปลกๆเขียนเอง (อ่านก่อนเสมอ)
เช่น ต้อง login และเป็น admin



**cvss** [https://www.first.org/cvss/calculator/3.1](https://www.first.org/cvss/calculator/3.1 "https://www.first.org/cvss/calculator/3.1")
- AV(attack vector) -> ส่วนมากโจมตีจากเว็บเป็น tcp
- AC(attack complexity) ->ถ้าต้อง chain หลายช่องโหว่เป็น  High
- PR(privilege require)-> ถ้าต้องเป็น admin ก็ high
- User Interactive(UI)-> ต้องรอ  user มาทำบางอย่างเพื่อให้ exploit ทำงานไหม
- Scope(s)-> สามารถโจมตีเป้าหมายนอก scope เช่นเว็บอื่นๆ
- Confidnetiality(C)-> กระทบใน component อื่น ข้อมูลความลับ
- Integrity(I)-> ข้อมูลที่บันทึกไปจะเสียหาย ไม่ได้เป็นไปตามที่ design ไว้
- Avilablity(A)-> กระทบ performance ของระบบ