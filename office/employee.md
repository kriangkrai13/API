
# Employee
## https://api.nbadigitalservice.com/v1/office

### การดึงข้อมูลของ employee ทั้งหมด
```http
GET /employee
```
### การดึงข้อมูลของ employee ผ่านไอดี
```http
GET /employee/:_id 
_id=62860054821f7b69619f254
```
### การเพิ่มข้อมูล employee
```http
POST /employee
```
Body
| Parameter | Type | Description |
| :--- | :--- | :--- |
| `emp_name` | `string` | **ชื่อ-นามสกุลพนักงาน** |
| `emp_tel` | `string` | **เบอร์โทรติดต่อ** |
| `emp_address` | `string` | **ที่อยู่ของพนักงาน** |
| `emp_iden` | `string` | **เลขบัตรประชาชน (ไม่ต้องใส่เครื่องหมาย "-")** |
| `emp_username` | `string` | **ข้อมูลการเข้าสู่ระบบ** |
| `emp_password` | `string` | **รหัสผ่านการเข้าสู่ระบบ** |
| `emp_department` | `string` | **ระดับการเข้าถึงข้อมูล** |
| `emp_position` | `string` | **ตำแหน่งหน้าที่** |
| `emp_salary` | `number` | **เงินเดือนพนักงาน** |
| `emp_start` | `date` | **วันที่เริ่มงาน**|
| `emp_end` | `date` | **วันที่ออกจากงาน** |
| `emp_bank` | `string` | **ชื่่อธนาคาร** |
| `emp_bank_number` | `string` | **เลขบัญชี** |
| `emp_pic` | `string` | **รูปพนักงาน** |
| `emp_status` | `string` | **สถานะการ** |
| `emp_timestamp` | `date` | **วันเวลาที่แก้ไขล่าสุด** |

### การแก้ไขข้อมูล employee
```http
PUT /employee/:_id
_id=62860054821f7b69619f254
```
Body
| Parameter | Type | Description |
| :--- | :--- | :--- |
| `emp_name` | `string` | **ชื่อ-นามสกุลพนักงาน** |
| `emp_tel` | `string` | **เบอร์โทรติดต่อ** |
| `emp_address` | `string` | **ที่อยู่ของพนักงาน** |
| `emp_iden` | `string` | **เลขบัตรประชาชน (ไม่ต้องใส่เครื่องหมาย "-")** |
| `emp_username` | `string` | **ข้อมูลการเข้าสู่ระบบ** |
| `emp_password` | `string` | **รหัสผ่านการเข้าสู่ระบบ** |
| `emp_department` | `string` | **ระดับการเข้าถึงข้อมูล** |
| `emp_position` | `string` | **ตำแหน่งหน้าที่** |
| `emp_salary` | `number` | **เงินเดือนพนักงาน** |
| `emp_start` | `date` | **วันที่เริ่มงาน**|
| `emp_end` | `date` | **วันที่ออกจากงาน** |
| `emp_bank` | `string` | **ชื่่อธนาคาร** |
| `emp_bank_number` | `string` | **เลขบัญชี** |
| `emp_pic` | `string` | **รูปพนักงาน** |
| `emp_status` | `string` | **สถานะการ** |
| `emp_timestamp` | `date` | **วันเวลาที่แก้ไขล่าสุด** |

### การลบข้อมูล employee
```http
DELETE /employee/:_id
_id=62860054821f7b69619f254
```

