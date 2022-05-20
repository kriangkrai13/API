# Amphure (อำเภอ)

## https://api.nbadigitalservice.com/api/nba-geo

### การดึงข้อมูลของ amphure ทั้งหมด

```http
post /amphures
```

```javascript
ตัวอย่างการส่ง
{
  "tokenKey" : string,
}
```

### การเพิ่มข้อมูลของ amphure

```http
POST /amphure
```

```javascript
ตัวอย่างการส่ง
{
      "amphur_code" : string,
       "amphur_name" : string,
        "province_id" : string,
           "tokenKey" : string,
}
```

### การแก้ไขข้อมูลของ amphure

```http
PUT /amphure
```

```javascript
ตัวอย่างการส่ง
{
    "amphur_id" : string,
     "amphur_code" : string,
       "amphur_name" : string,
        "province_id" : string,
           "tokenKey" : string,
}

```

### การลบข้อมูลของ amphure

```http
DELETE /amphure/:id
ส่ง amphure_id มา
```

