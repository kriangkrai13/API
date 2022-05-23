
# Partner
## https://api.nbadigitalservice.com/v1/office

### การดึงข้อมูลของ partner ทั้งหมด
```http
GET /partner
```
### การดึงข้อมูลของ partner ผ่านไอดี
```http
GET /partner/:_id 
_id=62860054821f7b69619f254
```
### การเพิ่มข้อมูล partner
```http
POST /partner
```
Body
| Parameter | Type | Description | Default |
| :--- | :--- | :--- | :--- |
| `partner_name` | `string` | **ชื่อ-นามสกุล** |
| `partner_tel` | `string` | **เบอร์โทรติดต่อ** |
| `partner_level` | `string` | **ระดับ เขต/ภาค** |
| `partner_sublevel` | `string` | **ระดับ เขต/ภาค เช่น 1 2 3 4 เป็นต้น** |
| `partner_address` | `string` | **ที่อยู่** |
| `partner_district` | `string` | **ตำบล** |
| `partner_amphur` | `string` | **อำเภอ** |
| `partner_province` | `string` | **จังหวัด** |
| `partner_username` | `string` | **รหัสผ่านการเข้าสู่ระบบ** |
| `partner_password` | `string` | **ระดับการเข้าถึงข้อมูล**
| `partner_salary` | `number` | **เงินเดือน** |
| `partner_bank` | `string` | **ชื่่อธนาคาร** |
| `partner_bank_number` | `string` | **เลขบัญชี** |
| `partner_start` | `date` | **วันที่เริ่มงาน**| |
| `partner_end` | `date` | **วันที่ออกจากงาน** |
| `partner_status` | `string` | **สถานะการ** |
| `partner_timestamp` | `date` | **วันเวลาที่แก้ไขล่าสุด** | **default: new Date()** |

### การแก้ไขข้อมูล partner
```http
PUT /partner/:_id
_id=62860054821f7b69619f254
```
Body
| Parameter | Type | Description | Default |
| :--- | :--- | :--- | :--- |
| `partner_name` | `string` | **ชื่อ-นามสกุล** |
| `partner_tel` | `string` | **เบอร์โทรติดต่อ** |
| `partner_level` | `string` | **ระดับ เขต/ภาค** |
| `partner_sublevel` | `string` | **ระดับ เขต/ภาค เช่น 1 2 3 4 เป็นต้น** |
| `partner_address` | `string` | **ที่อยู่** |
| `partner_district` | `string` | **ตำบล** |
| `partner_amphur` | `string` | **อำเภอ** |
| `partner_province` | `string` | **จังหวัด** |
| `partner_username` | `string` | **รหัสผ่านการเข้าสู่ระบบ** |
| `partner_password` | `string` | **ระดับการเข้าถึงข้อมูล**
| `partner_salary` | `number` | **เงินเดือน** |
| `partner_bank` | `string` | **ชื่่อธนาคาร** |
| `partner_bank_number` | `string` | **เลขบัญชี** |
| `partner_start` | `date` | **วันที่เริ่มงาน**| |
| `partner_end` | `date` | **วันที่ออกจากงาน** |
| `partner_status` | `string` | **สถานะการ** |
| `partner_timestamp` | `date` | **วันเวลาที่แก้ไขล่าสุด** | **default: new Date()** |

### การลบข้อมูล partner
```http
DELETE /partner/:_id
_id=62860054821f7b69619f254
```

