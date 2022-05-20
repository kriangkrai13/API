# Zone (ภูมิภาค)
## https://api.nbadigitalservice.com/api/nba-geo

### การดึงข้อมูลของ Zone ทั้งหมด
```http
post /zone
```

```javascript
ตัวอย่างการส่ง
{
  "tokenKey" : string,
}
```


### การดึงข้อมูลของ Zone-Province ของ NBA ที่จัดขึ้นเอง ทั้งหมด
#### ZoneNBA+จังหวัด
```http
post /join_nba_zone_province
```

```javascript
ตัวอย่างการส่ง
{
  "tokenKey" : string,
}
```