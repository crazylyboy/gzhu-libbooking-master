# gzhu-libbooking-master
图书馆自习室自动预约
`cfg.json`设置如下：  
```json
{
  "username": "账号",
  "password": "密码",
  "room": "101或者103",
  "habit": [
    {
      "seat_id": "101-001",
      "bt": "08:30:00",
      "et": "12:30:00"
    },
    {
      "seat_id": "101-001",
      "bt": "13:00:00",
      "et": "17:00:00"
    },
    {
      "seat_id": "101-001",
      "bt": "18:00:00",
      "et": "20:00:00"
    }
  ]
}
```
意思就是预定101-001座位的三次，可以根据需要自行删减。但格式一定要对
