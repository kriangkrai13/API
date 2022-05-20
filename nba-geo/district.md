# District (จังหวัด)

## https://api.nbadigitalservice.com/api/nba-gro

### การดึงข้อมูลของ district ทั้งหมด

```http
post /districts
```

```javascript
ตัวอย่างการส่ง
{
  "tokenKey" : string,
}
```

### การเพิ่มข้อมูลของ district

```http
POST /district
```

```javascript
ตัวอย่างการส่ง
{
      "district_code" : string,
       "district_name" : string,
         "post_code" : string,
          "amphur_id" : string,
           "province_id" : string,
            "tokenKey" : string,
}
```

### การแก้ไขข้อมูลของ district

```http
PUT /district
```

```javascript
ตัวอย่างการส่ง
{
     "district_id" : string,
      "district_code" : string,
       "district_name" : string,
         "post_code" : string,
          "amphur_id" : string,
           "province_id" : string,
            "tokenKey" : string,
}
}
```

### การลบข้อมูลของ provinces

```http
DELETE /district/:id
ส่ง district_id มา
```

