# แบบทดสอบ K'Suwijak

### Tech Stack

| - **Tech**            | **Required ?** | - |
|-----------------------|----------------| - |
| PHP ^8.0              |            Yes | - |
| Laravel Framework 9.x |            Yes | - |
| ORM                   |            Yes | - |
| MySQL8                |            Yes | - |
| MongoDB (เลือกใช้แทน MySQL)              |              - | พิจารณาเป็นพิเศษ |
| CI                    |              - | พิจารณาเป็นพิเศษ |
| Design Pattern        |              - | พิจารณาเป็นพิเศษ |
| VueJS                 |              - | พิจารณาเป็นพิเศษ |
| Dockerfile            |              - | พิจารณาเป็นพิเศษ |
| Docker Compose file   |              - | พิจารณาเป็นพิเศษ |


### Requirement
ระบบตะกร้าสินค้า


ให้ติดตั้งก่อนเริ่มโครงการ
```
https://github.com/zipzoft/interview-shopping-cart
```

จำเป็นต้อง implement interface 3 รายการจากด้านล่างนี้
```
ZipzoftInterview\ShoppingCart\CartInterface
ZipzoftInterview\ShoppingCart\CashierInterface
ZipzoftInterview\ShoppingCart\UserInterface
```

- มีสองหน้า คือ หน้าหลัก และหน้าตะกร้าสินค้าของฉัน
- ไม่จำเป็นต้องออกแบบสวย
- ไม่มีระบบจ่ายเงิน
- ไม่มีระบบสมาชิก ใช้วิธีแยก Session
- แสดงรายการสินค้าในหน้าหลัก
  - แสดงชื่อ, ราคา, เนื้อหาสินค้า 
- สามารถเลือกสินค้าจากหน้าหลัก นำมาใส่ตะกร้าสินค้าได้
- ส่งงานโดยส่ง Pull request มาที่ repository นี้ได้เลย
