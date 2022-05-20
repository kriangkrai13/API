# Leavework (การลางานล่วงหน้า)
## https://api.nbadigitalservice.com/v1/office


### การดึงข้อมูลของ leavework ทั้งหมด
```http
GET /leavework
```
### การดึงข้อมูลของ leavework ผ่านไอดี
```http
GET /leavework/:_id 
_id=62860054821f7b69619f254
```

### การเพิ่มข้อมูล leavework
```http
POST /leavework
```
Body
| Parameter | Type | Description | Default |
| :--- | :--- | :--- | :--- |
| `lew_topic` | `string` | **หัวข้อรายงาน** |
| `lew_detail` | `string` | **รายละเอียด** |
| `lew_start` | `date` | **เริ่มลาวันที่** |
| `lew_end` | `date` | **ลาถึงวันที่** |
| `lew_number_day` | `number` | **จำนวนวันที่ลา** |
| `lew_manager_confirm` | `boolean` | **หัวหน้ายืนยัน** | **default: false**|
| `lew_ceo_confirm` | `boolean` | **ผู้บริหารยืนยัน** | **default: false**|
| `lew_timestamp` | `date` | **จังหวัด** | **default: new Date()** |


### การแก้ไขข้อมูล leavework
```http
PUT /leavework/:_id 
_id=62860054821f7b69619f254
```
Body
| Parameter | Type | Description | Default |
| :--- | :--- | :--- | :--- |
| `lew_topic` | `string` | **หัวข้อรายงาน** |
| `lew_detail` | `string` | **รายละเอียด** |
| `lew_start` | `date` | **เริ่มลาวันที่** |
| `lew_end` | `date` | **ลาถึงวันที่** |
| `lew_number_day` | `number` | **จำนวนวันที่ลา** |
| `lew_manager_confirm` | `boolean` | **หัวหน้ายืนยัน** | **default: false**|
| `lew_ceo_confirm` | `boolean` | **ผู้บริหารยืนยัน** | **default: false**|
| `lew_timestamp` | `date` | **จังหวัด** | **default: new Date()** |

### การลบข้อมูล leavework
```http
DELETE /leavework/:_id
_id=62860054821f7b69619f254
```