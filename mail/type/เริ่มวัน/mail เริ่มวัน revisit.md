## Thai
```
เรียน ทีม {XXXXX},

ขอแจ้งว่าทาง STH เริ่มดำเนินการ Revisited Penetration Test ระบบ {ระบบ} ประจำวันที่ {2022-07-20} แล้วครับ

โดยการทดสอบ นี้เป็นส่วนหนึ่งของโครงการ Penetration Test of {proj name} (Project ID: {projID})

รายละเอียดระบบสารสนเทศในขอบเขตงาน:
{part name} - Web Application
URL: {URL}                   [{IP}]
XXXXX - Mobile Application API
URL: {URL}                   [{IP}]
URL: {URL}                   [{IP}]

Test Account:
{username without password}

หมายเลขไอพีของ STH:
35.240.128.238
178.128.122.95

ระยะเวลาการทดสอบ:
{2022-07-XXXXX - 2022-07-XXXXX}

หมายเหตุ:
รบกวนช่วยทำการแจ้งบุคคลที่ดูแลระบบ (SOC/Network/DB/Server) ทราบว่าจะมีการทำ PenTest
ถ้าหากพบ security alert (SOC/SIEM/WAF/IPS) จาก IP ของ STH สามารถปล่อยผ่านได้เลยครับ
รบกวนทำการสำรองข้อมูลและระบบ (backup หรือ snapshot) ก่อนและระหว่างการทำ PenTest
รบกวนทางผู้พัฒนาแอปหรือดูแลระบบไม่ทำการแก้ไขโค้ดหรือการตั้งค่าระบบระหว่างการทดสอบ PenTest


ถ้ามีปัญหาฉุกเฉินเกี่ยวกับระบบสามารถติดต่อ 090-321-8841 (ณนันท์ แสวงธีรกูล) ได้เลยครับ
```


## Eng

```
Dear {team} Team,

Please be informed that the {optional xx2ndxx} revisited penetration test of {project name} has started for {xxxx-xx-xx}.

Below is the targets and scope for this revisited penetration test krub.

Target :

-   {target name} (Android)
	- {version}         [{ip}]

-   {target name} (iOS)
	- {version}         [{ip}]

-   {target application}
	- {http://xxxxxxx}  [{ip}]


User Accounts:
-   {user1 with out password}
-   {user2 with out password}

Api endpoint:
-   {http://xxxxx}

Swagger API:
-   {http://xxxxx}

Scope:
-   {Gray Box Application Penetration Testing}
-   {UAT Environment}

Pentester’s Source IP / External:
- 35.240.128.238
- 178.128.122.95

Period:
-   {xxxx-xx-xx}

Location:
-   {xxxOff-site location in the facilities of STHxxx}

Notes:

-   Please notify system, database, and network admins regarding the pentest activity.
-   Please backup application code and data before/during the pentest activity.
-   Please do not modify any back-end source code in the target applications.

In case of emergency, please call(+66) 090-321-8841(Nanun).
```