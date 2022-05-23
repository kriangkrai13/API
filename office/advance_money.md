# advance_money (การเบิกเงินล่วงหน้า)
## https://api.nbadigitalservice.com/v1/office


### การดึงข้อมูลของ advance_money ทั้งหมด
```http
GET /advance_money
```
### การดึงข้อมูลของ advance_money ผ่านไอดี
```http
GET /advance_money/:_id 
_id=62860054821f7b69619f254
```

### การเพิ่มข้อมูล advance_money
```http
POST /advance_money
```
Body
| Parameter | Type | Description | Default |
| :--- | :--- | :--- | :--- |
| `avm_owner` | `string` | **_id เจ้าของรายงาน** |
| `avm_amount` | `number` | **จำนวนเงิน** |
| `avm_status` | `string` | **สถานะรายงาน** | **default: waiting**|
| `avm_timestamp` | `date` | **วันที่ทำรายการ** |**default: new Date()** |


### การแก้ไขข้อมูล advance_money
```http
PUT /advance_money/:_id 
_id=62860054821f7b69619f254
```
Body
| Parameter | Type | Description | Default |
| :--- | :--- | :--- | :--- |
| `avm_owner` | `string` | **_id เจ้าของรายงาน** |
| `avm_amount` | `number` | **จำนวนเงิน** |
| `avm_status` | `string` | **สถานะรายงาน** | **default: waiting**|
| `avm_timestamp` | `date` | **วันที่ทำรายการ** |**default: new Date()** |

### การลบข้อมูล advance_money
```http
DELETE /advance_money/:_id
_id=62860054821f7b69619f254
```
