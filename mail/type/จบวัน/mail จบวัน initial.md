[[check mail]] ด้วย
## Eng 
- {porj} => เอามาจากไหนวะ ? -> เอามาจาก google calendar

- Note ใส่แค่ชองโหว่ที่เจอวันนั้น ถ้าเจอช่องโหว่เดิมเพิ่มเติมจากการ test เขียนว่า (New Instance)
```
Dear {proj} Team,
 
Please be informed that the penetration test of ${proj_name} has finished for ${today ex:2022-06-28}.

Today we found the following issues.

1. Broken Access Control (New Instance)
Overall risk: ${High}
Impact factor: ${High}
Likelihood factor: ${Medium}


```

## Thai
```
เรียน ทีม {team},

ขอแจ้งว่าทาง STH หยุดดำเนินการ Penetration Test ระบบ {ระบบ} {optional:รอบ 2} ประจำวันที่ {day:2022-07-08} แล้วครับ

โดยวันนี้พบช่องโหว่ดังต่อไปนี้
1. Design Flaw in Asset Tracker [Very Low]
[...]



```


## Last Day
- ไม่ต้องระบุวัน
```
Please be informed that the penetration test of ${proj_name} has finished.
```