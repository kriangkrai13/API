
# Partner
## https://api.nbadigitalservice.com/v1/office

### การดึงข้อมูลของ employee ทั้งหมด
```http
GET /partner
```
### การดึงข้อมูลของ employee ผ่านไอดี
```http
GET /partner/:_id 
_id=62860054821f7b69619f254
```
### การเพิ่มข้อมูล employee
```http
POST /partner
```
Body
| Parameter | Type | Description |
| :--- | :--- | :--- |
| `partner_name` | `string` | **ชื่อ-นามสกุล** |
| `partner_tel` | `string` | **เบอร์โทรติดต่อ** |
| `partner_level` | `string` | **ระดับ เขต/ภาค** |
| `partner_sublevel` | `string` | **ระดับ เขต/ภาค เช่น 1 2 3 4 เป็นต้น** |
| `partner_address` | `string` | **ที่อยู่** |
| `partner_district` | `string` | **ตำบล** |
| `partner_amphur` | `string` | **อำเภอ** |
| `partner_province` | `string` | **จังหวัด** |
| `partner_username` | `number` | **รหัสผ่านการเข้าสู่ระบบ** |
| `partner_password` | `date` | **ระดับการเข้าถึงข้อมูล**
| `partner_salary` | `date` | **เงินเดือน** |
| `partner_bank` | `string` | **ชื่่อธนาคาร** |
| `partner_bank_number` | `string` | **เลขบัญชี** |
| `partner_start` | `date` | **วันที่เริ่มงาน**| |
| `partner_end` | `date` | **วันที่ออกจากงาน** |
| `partner_status` | `date` | **สถานะการ** |
| `partner_timestamp` | `date` | **วันเวลาที่แก้ไขล่าสุด** |

### การแก้ไขข้อมูล employee
```http
PUT /partner/:_id
_id=62860054821f7b69619f254
```
Body
| Parameter | Type | Description |
| :--- | :--- | :--- |
| `partner_name` | `string` | **ชื่อ-นามสกุล** |
| `partner_tel` | `string` | **เบอร์โทรติดต่อ** |
| `partner_level` | `string` | **ระดับ เขต/ภาค** |
| `partner_sublevel` | `string` | **ระดับ เขต/ภาค เช่น 1 2 3 4 เป็นต้น** |
| `partner_address` | `string` | **ที่อยู่** |
| `partner_district` | `string` | **ตำบล** |
| `partner_amphur` | `string` | **อำเภอ** |
| `partner_province` | `string` | **จังหวัด** |
| `partner_username` | `number` | **รหัสผ่านการเข้าสู่ระบบ** |
| `partner_password` | `date` | **ระดับการเข้าถึงข้อมูล**
| `partner_salary` | `date` | **เงินเดือน** |
| `partner_bank` | `string` | **ชื่่อธนาคาร** |
| `partner_bank_number` | `string` | **เลขบัญชี** |
| `partner_start` | `date` | **วันที่เริ่มงาน**| |
| `partner_end` | `date` | **วันที่ออกจากงาน** |
| `partner_status` | `date` | **สถานะการ** |
| `partner_timestamp` | `date` | **วันเวลาที่แก้ไขล่าสุด** |

### การลบข้อมูล employee
```http
DELETE /partner/:_id
_id=62860054821f7b69619f254
```

