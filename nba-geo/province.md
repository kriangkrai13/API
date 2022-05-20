# Province (จังหวัด)

## https://api.nbadigitalservice.com/api/nba-gro

### การดึงข้อมูลของ provinces ทั้งหมด

```http
post /provinces
```

```javascript
ตัวอย่างการส่ง
{
  "tokenKey" : string,
}
```

### การเพิ่มข้อมูลของ provinces

```http
POST /province
```

```javascript
ตัวอย่างการส่ง
{
      "province_name" : string,
       "geo_id" : string,
        "nba_geo_id" : string,
         "nba_zone" : string,
          "province_code" : string,
           "tokenKey" : string,
}
```

### การแก้ไขข้อมูลของ provinces

```http
PUT /province
```

```javascript
ตัวอย่างการส่ง
{
     "province_id" : string,
      "province_name" : string,
       "geo_id" : string,
        "nba_geo_id" : string,
         "nba_zone" : string,
          "province_code" : string,
           "tokenKey" : string,
}
```

### การลบข้อมูลของ provinces

```http
DELETE /province/:id
ส่ง province_id มา
```

