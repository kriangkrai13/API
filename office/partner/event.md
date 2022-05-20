# Event (การส่งมอบงานให้ศูนย์ เขต/ภาค)
## https://api.nbadigitalservice.com/v1/office/partner


### การดึงข้อมูลของ event ทั้งหมด
```http
GET /event
```
### การดึงข้อมูลของ event ผ่านไอดี
```http
GET /event/:_id 
_id=62860054821f7b69619f254
```

### การเพิ่มข้อมูล event
```http
POST /event
```
Body
| Parameter | Type | Description | Default |
| :--- | :--- | :--- | :--- |
| `event_owner` | `string` | **_id เจ้าของรายงาน** |
| `event_topic` | `string` | **หัวข้อรายงาน** |
| `event_detail` | `string` | **รายละเอียดรายงาน** |
| `event_status` | `string` | **สถานะ** | **default: sent**|
| `event_timestamp` | `date` | **วันที่ทำรายการ** |**default: new Date()** |


### การแก้ไขข้อมูล event
```http
PUT /event/:_id 
_id=62860054821f7b69619f254
```
Body
| Parameter | Type | Description | Default |
| :--- | :--- | :--- | :--- |
| `event_owner` | `string` | **_id เจ้าของรายงาน** |
| `event_topic` | `string` | **หัวข้อรายงาน** |
| `event_detail` | `string` | **รายละเอียดรายงาน** |
| `event_status` | `string` | **สถานะ** | **default: sent**|
| `event_timestamp` | `date` | **วันที่ทำรายการ** |**default: new Date()** |

### การลบข้อมูล event
```http
DELETE /event/:_id
_id=62860054821f7b69619f254
```