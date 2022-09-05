## english
```
Dear AYCAP Team,

Please be informed that STH will perform the readiness testing for the AYCAP Internal Network.

The main objective of this readiness testing is we will check if the testers have network-level access to the in-scope IP ranges or not.

Project Name: Penetration Test of AYCAP Internal Network 2022
Project ID: 2022030003

Period:

-   2022-08-10 (22:00 - 00:00) (Readiness Testing)
-   2022-08-15 - 2022-08-19 (22:00 - 04:00) (Penetration Testing)

Location: Bank of Ayudhaya (Krungsri) - Rama 3 Office, 18th floor

Pentester's Source IP Addresses:

-   10.101.27.0/24 [BAY Rama 3, 18th floor]

-   10.101.27.241 
-   10.101.27.242 
-   10.101.27.243

Pentester's Source MAC Address (Wi-Fi):

-   f0:18:98:7a:e2:6d 
-   f8:4d:89:61:e5:11 
-   28:d0:ea:3c:4b:1e

Pentester's Source MAC Address (LAN):

-   3c:22:fb:c0:be:f0 
-   a0:ce:c8:ea:8a:5b 
-   38:2c:4a:78:4b:ae

Target Servers:
```

```
เรียน ทีม MEB,

ขอแจ้งว่าทาง STH ได้เริ่มการ Readiness Testing แล้วครับ

โดยจุดประสงค์ของการทำ Readiness Testing เพื่อจะทดสอบการใช้งานฟังก์ชั่นต่างๆของเป้าหมายที่อยู่ใน scope 

ชื่อโปรเจค: MEB 2022
เลขที่โปรเจค: 2022080007

รายละเอียดระบบสารสนเทศในขอบเขตงาน:

MEB Market - Web Application
URL: https://pentest.mebmarket.com
Test User Accounts:
Test User Account สิทธิ์ Registered User (Reader) 
- user: mebpentest1
- user: mebpentest2

Test User Account สิทธิ์ Seller 
- user: test_001
- user: testRegSel1

Test User Account สิทธิ์ Publisher 
- user: publisherpen1
- user: publisherpen2

MEB Market Backoffice - Web Application
URL: https://pentest.mebmarket.com/632627538
Test User Accounts:
Test User Account สิทธิ์ Super Admin
- user : superadmin@meb.co.th

MEB Coin Backoffice - Web Application
URL: https://pentest-coin.mebmarket.com/backend/Admin
Test User Accounts:
Test User Account สิทธิ์ Super Admin
- user: superadmin@meb.co.th

MEB - Mobile Application (Android และ iOS) และ Mobile Web API
Android: version
iOS:  version 

readAwrite - Web Application
URL: https://pentest.readawrite.com
Test User Accounts:
Test User Account สิทธิ์ Registered User 
- reader normal
email : ptest_001@test.com
username: ptest_001
password: penTest-2022
display name: ptest-normal
 
- reader verify id card
email : ptest_002@test.com
username: ptest_002
password: penTest-2022
display name: ptest-verify-idcard
 
- publisher
email : ptest_pub_001@test.com
username: ptest_pub_001
password: penTest-2022
display name: ptest-publisher

readAwrite Backoffice - Web Application
URL: https://pentest.readawrite.com/web/backend/Admin/index.php
Test User Accounts:
- officer backend
username: ptest_officer1@test.com
permission: root


หมายเลขไอพีของ STH:
35.240.128.238
178.128.122.95


ระยะเวลาการทดสอบ:
- 2022-08-26 (10.00 - 18.00) (Readiness Testing)
- 2022-08-31 ถึง 2022-09-12 (10.00 - 18.00) (Penetration Testing)


```
