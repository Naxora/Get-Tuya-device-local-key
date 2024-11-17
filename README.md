# Get Tuya Local Key

Follow [Home Assistant Tuya](https://www.home-assistant.io/integrations/tuya/) docs

After account is created and device is added you need the `Device ID` to get the `local_key`

Device ID can be found: https://eu.iot.tuya.com/ --> `Cloud` --> `Development` then `Open Project` --> `Devices`

You need to create project if you don't have one: [Tuya Docs](https://developer.tuya.com/en/docs/iot/config-cloud-project?id=Kat2eytbffx3v)

Get local_key: https://eu.iot.tuya.com/ --> `Cloud` --> `API Explorer` then `Device Management` --> `Query Device Details`

If you get `No permissions. Your subscription to cloud development plan has expired.`: [Tuya Docs](https://support.tuya.com/en/help/_detail/Kc3n6kr7kllhc)

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
