# Get Tuya Local Key

Follow [Home Assistant Tuya](https://www.home-assistant.io/integrations/tuya/) docs

After account is created and device is added you need the `Device ID` to get the `local_key`

https://eu.iot.tuya.com/ --> `Cloud` --> `API Explorer` then `Device Management` --> `Query Device Details`

Insert `device_id` then click `Submit Request`

```
{
  "result": {
    "active_time": 1703973253,
    "category": "cs",
    "create_time": 1669042865,
    "custom_name": "",
    "icon": "smart/icon/zx718955gthz35wkc/wqss012sf3a211w34f.png",
    "id": "***********************",
    "ip": "***********************",
    "is_online": true,
    "lat": ""***********************",",
    "local_key": "Hf*****************",
    "lon": ""***********************",",
```
