# GEO (ภูมิภาค)
## https://api.nbadigitalservice.com/api/nba-geo

### การดึงข้อมูลของ GEO ทั้งหมด
```http
post /geo
```

```javascript
ตัวอย่างการส่ง
{
  "tokenKey" : string,
}
```

### การดึงข้อมูลของ GEO ของ NBA ที่จัดขึ้นเอง ทั้งหมด
```http
post /nba-geo
```

```javascript
ตัวอย่างการส่ง
{
  "tokenKey" : string,
}
```

### การดึงข้อมูลของ GEO-Province ทั้งหมด
```http
post /join_geo_province
```

```javascript
ตัวอย่างการส่ง
{
  "tokenKey" : string,
}
```
### การดึงข้อมูลของ GEO-Province ของ NBA ที่จัดขึ้นเอง ทั้งหมด
```http
post /join_nba_geo_province
```

```javascript
ตัวอย่างการส่ง
{
  "tokenKey" : string,
}
```

### การดึงข้อมูลของ GEO-Province-Amphur ของ NBA ที่จัดขึ้นเอง ทั้งหมด
#### ภูมิภาคของnba+จังหวัด+อำเภอ
```http
post /join_nba_geo_province_amphur
```

```javascript
ตัวอย่างการส่ง
{
  "tokenKey" : string,
}
```

### การดึงข้อมูลของ GEO-Province-Amphur+District ของ NBA ที่จัดขึ้นเอง ทั้งหมด
#### ภูมิภาคของnba+จังหวัด+อำเภอ+ตำบล
```http
post /join_nba_geo_province_amphur_district
```

```javascript
ตัวอย่างการส่ง
{
  "tokenKey" : string,
}
```
