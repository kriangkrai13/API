# Event_Report (รายละเอียดการส่งมอบงานให้ศูนย์ เขต/ภาค)
## https://api.nbadigitalservice.com/v1/office/partner


### การดึงข้อมูลของ event_report ทั้งหมด
```http
GET /event_report
```
### การดึงข้อมูลของ event_report ผ่านไอดี
```http
GET /event_report/:_id 
_id=62860054821f7b69619f254
```

### การเพิ่มข้อมูล event_report
```http
POST /event_report
```
Body
| Parameter | Type | Description | Default |
| :--- | :--- | :--- | :--- |
| `evr_event_id` | `string` | **_id ของ event หลัก** |
| `evr_partner_id` | `string` | **_id ของศูนย์ (เขต/ภาค)** |
| `evr_detail` | `string` | **รายละเอียดรายงาน** |
| `evr_timestamp` | `date` | **วันที่ทำรายการ** |**default: new Date()** |


### การแก้ไขข้อมูล event_report
```http
PUT /event_report/:_id 
_id=62860054821f7b69619f254
```
Body
| Parameter | Type | Description | Default |
| :--- | :--- | :--- | :--- |
| `evr_event_id` | `string` | **_id ของ event หลัก** |
| `evr_partner_id` | `string` | **_id ของศูนย์ (เขต/ภาค)** |
| `evr_detail` | `string` | **รายละเอียดรายงาน** |
| `evr_timestamp` | `date` | **วันที่ทำรายการ** |**default: new Date()** |

### การลบข้อมูล event_report
```http
DELETE /event_report/:_id
_id=62860054821f7b69619f254
```