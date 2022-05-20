# Salary (การจ่ายเงินเดือน เขต/ภาค)
## https://api.nbadigitalservice.com/v1/office/partner


### การดึงข้อมูลของ salary ทั้งหมด
```http
GET /salary
```
### การดึงข้อมูลของ salary ผ่านไอดี
```http
GET /salary/:_id 
_id=62860054821f7b69619f254
```

### การเพิ่มข้อมูล salary
```http
POST /salary
```
Body
| Parameter | Type | Description | Default |
| :--- | :--- | :--- | :--- |
| `salary_owner` | `string` | **_id เจ้าของรายงาน** |
| `salary_amount` | `string` | **จำนวนเงิน** |
| `salary_pic` | `string` | **รูปภาพสลิปหรือหลักฐานการโอน** |
| `salary_date` | `string` | **ประจำวันที่** |**default: new Date()** |
| `salary_payroll_date` | `date` | **วันที่จ่ายเงิน** |**default: new Date()** |


### การแก้ไขข้อมูล salary
```http
PUT /salary/:_id 
_id=62860054821f7b69619f254
```
Body
| Parameter | Type | Description | Default |
| :--- | :--- | :--- | :--- |
| `salary_owner` | `string` | **_id เจ้าของรายงาน** |
| `salary_amount` | `string` | **จำนวนเงิน** |
| `salary_pic` | `string` | **รูปภาพสลิปหรือหลักฐานการโอน** |
| `salary_date` | `string` | **ประจำวันที่** |**default: new Date()** |
| `salary_payroll_date` | `date` | **วันที่จ่ายเงิน** |**default: new Date()** |

### การลบข้อมูล salary
```http
DELETE /salary/:_id
_id=62860054821f7b69619f254
```