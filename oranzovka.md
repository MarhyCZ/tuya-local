<!-- New Device issue for make-all/tuya-local, ready to paste once issues reopen.
     Title: Request support for Oranžovka E27 and E14 1600-4000K smart bulbs
     Each "###" section matches a field of the New Device form. -->

### Log message

```text
Adding Smart bulb Oranzovka E27 device with product id ewxuxtzrwf4zxyqj
Device matches rgbcw_lightbulb with quality of 100%. LOCAL DPS: {"updated_at": 1794510680.2697675, "20": true, "21": "white", "22": 1000, "23": 1000, "24": "000003e803e8", "25": "000e0d0000000000000000c80000", "26": 0, "34": true, "41": true}
Device matches rgbcw_lightbulb with quality of 100%. LOCAL DPS: {"updated_at": 1794519919.7428842, "20": true, "21": "colour", "22": 175, "23": 0, "24": "000003e803e8", "25": "000e0d0000000000000000c80000", "26": 0, "34": true, "41": true}
```

### Product ID

ewxuxtzrwf4zxyqj (E27 11W), 6wji4o0vr9crq0y8 (E14 5W)

### Product Name

Oranžovka smart WiFi LED bulb E27 11W 1600-4000K / E14 5W 1600-4000K

### DPS information

```text
{
"result": {
"model": "{\"modelId\":\"e1n2jmno\",\"services\":[{\"actions\":[],\"code\":\"\",\"description\":\"\",\"events\":[],\"name\":\"\",\"properties\":[{\"abilityId\":20,\"accessMode\":\"rw\",\"code\":\"switch_led\",\"description\":\"\",\"extensions\":{\"iconName\":\"icon-dp_power\",\"attribute\":\"641\"},\"name\":\"开关\",\"typeSpec\":{\"type\":\"bool\"}},{\"abilityId\":21,\"accessMode\":\"rw\",\"code\":\"work_mode\",\"description\":\"\",\"extensions\":{\"iconName\":\"icon-dp_mode\",\"attribute\":\"640\"},\"name\":\"工作模式\",\"typeSpec\":{\"type\":\"enum\",\"range\":[\"white\",\"colour\",\"scene\",\"music\"]}},{\"abilityId\":22,\"accessMode\":\"rw\",\"code\":\"bright_value\",\"description\":\"\",\"extensions\":{\"iconName\":\"icon-liangdu1\",\"attribute\":\"640\"},\"name\":\"白光亮度\",\"typeSpec\":{\"type\":\"value\",\"max\":1000,\"min\":10,\"scale\":0,\"step\":1}},{\"abilityId\":23,\"accessMode\":\"rw\",\"code\":\"temp_value\",\"description\":\"\",\"extensions\":{\"iconName\":\"icon-dp_half\",\"attribute\":\"640\"},\"name\":\"冷暖值\",\"typeSpec\":{\"type\":\"value\",\"max\":1000,\"min\":0,\"scale\":0,\"step\":1}},{\"abilityId\":24,\"accessMode\":\"rw\",\"code\":\"colour_data\",\"description\":\"彩光颜色、亮度、饱和度调节\",\"extensions\":{\"iconName\":\"icon-dp_mode\",\"attribute\":\"512\"},\"name\":\"彩光\",\"typeSpec\":{\"type\":\"string\",\"maxlen\":255}},{\"abilityId\":25,\"accessMode\":\"rw\",\"code\":\"scene_data\",\"description\":\"灯光情景\",\"extensions\":{\"iconName\":\"icon-dp_mode\",\"attribute\":\"512\"},\"name\":\"场景\",\"typeSpec\":{\"type\":\"string\",\"maxlen\":255}},{\"abilityId\":26,\"accessMode\":\"rw\",\"code\":\"countdown\",\"description\":\"\",\"extensions\":{\"iconName\":\"icon-a_nav_timer\",\"attribute\":\"640\"},\"name\":\"倒计时\",\"typeSpec\":{\"type\":\"value\",\"max\":86400,\"min\":0,\"scale\":0,\"step\":1,\"unit\":\"s\"}},{\"abilityId\":27,\"accessMode\":\"wr\",\"code\":\"music_data\",\"description\":\"通过APP内置律动算法实现灯光律动\",\"extensions\":{\"iconName\":\"icon-dp_mic\",\"attribute\":\"128\"},\"name\":\"音乐灯\",\"typeSpec\":{\"type\":\"string\",\"maxlen\":255}},{\"abilityId\":28,\"accessMode\":\"wr\",\"code\":\"control_data\",\"description\":\"用于实时下发数据实现实时预览效果\",\"extensions\":{\"iconName\":\"icon-dp_box2\",\"attribute\":\"640\"},\"name\":\"调节\",\"typeSpec\":{\"type\":\"string\",\"maxlen\":255}},{\"abilityId\":29,\"accessMode\":\"rw\",\"code\":\"debug_data\",\"description\":\"用于gamma调试，需配合支持gamma调试的面板使用\",\"extensions\":{\"iconName\":\"icon-dp_tool\",\"attribute\":\"128\"},\"name\":\"调试\",\"typeSpec\":{\"type\":\"string\",\"maxlen\":255}},{\"abilityId\":30,\"accessMode\":\"rw\",\"code\":\"rhythm_mode\",\"description\":\"不同时间段的色温、亮度根据人体节律自动调整\",\"extensions\":{\"iconName\":\"icon-dp_time3\",\"attribute\":\"640\"},\"name\":\"生物节律\",\"typeSpec\":{\"type\":\"raw\",\"maxlen\":255}},{\"abilityId\":31,\"accessMode\":\"rw\",\"code\":\"sleep_mode\",\"description\":\"温馨的灯光渐灭陪您进入甜美的梦乡\",\"extensions\":{\"iconName\":\"icon-dp_sleep\",\"attribute\":\"640\"},\"name\":\"灯光助眠\",\"typeSpec\":{\"type\":\"raw\",\"maxlen\":255}},{\"abilityId\":32,\"accessMode\":\"rw\",\"code\":\"wakeup_mode\",\"description\":\"柔和的灯光渐亮伴您迎接新的一天\",\"extensions\":{\"iconName\":\"icon-dp_sun\",\"attribute\":\"640\"},\"name\":\"灯光唤醒\",\"typeSpec\":{\"type\":\"raw\",\"maxlen\":255}},{\"abilityId\":33,\"accessMode\":\"rw\",\"code\":\"power_memory\",\"description\":\"用于设置断电再上电灯亮起的状态（不记忆APP关灯动作）\",\"extensions\":{\"iconName\":\"icon-dp_lightning\",\"attribute\":\"640\"},\"name\":\"断电记忆\",\"typeSpec\":{\"type\":\"raw\",\"maxlen\":255}},{\"abilityId\":34,\"accessMode\":\"rw\",\"code\":\"do_not_disturb\",\"description\":\"适用于经常停电的区域，避免停电再来电时亮灯打扰用户。开启通电勿扰，APP上关灯后需要连续两次上电才会亮灯\",\"extensions\":{\"iconName\":\"icon-dp_sleep\",\"attribute\":\"640\"},\"name\":\"停电勿扰\",\"typeSpec\":{\"type\":\"bool\"}},{\"abilityId\":35,\"accessMode\":\"rw\",\"code\":\"switch_gradient\",\"description\":\"开灯渐亮关灯渐暗\",\"extensions\":{\"iconName\":\"icon-dp_mode\",\"attribute\":\"0\"},\"name\":\"开关渐变\",\"typeSpec\":{\"type\":\"raw\",\"maxlen\":128}},{\"abilityId\":41,\"accessMode\":\"rw\",\"code\":\"remote_switch\",\"description\":\"\",\"extensions\":{\"iconName\":\"icon-dp_power2\"},\"name\":\"遥控器开关\",\"typeSpec\":{\"type\":\"bool\"}},{\"abilityId\":82,\"accessMode\":\"rw\",\"code\":\"candle_mode_data\",\"description\":\"模拟烛光效果\",\"extensions\":{\"iconName\":\"icon-huoyan\",\"attribute\":\"0\"},\"name\":\"模拟烛光\",\"typeSpec\":{\"type\":\"raw\",\"maxlen\":128}},{\"abilityId\":210,\"accessMode\":\"rw\",\"code\":\"random_timing\",\"description\":\"灯光随机亮灭模拟有人在家的场景\",\"extensions\":{\"iconName\":\"icon-dp_time3\",\"attribute\":\"128\"},\"name\":\"灯光看家\",\"typeSpec\":{\"type\":\"raw\",\"maxlen\":255}}]}]}"
},
"success": true,
"t": 1794749289759,
"tid": "66353403e0f811f1a9bd72eab2d043f9"
}
```

### Information about how the device functions

Tunable white bulb, 1600-4000K, with an extra red-only LED ("red mode"). Product page: https://svitimprotebe.cz/eshop/chytra-wifi-led-zarovka-oranzovka-e27-12w-1600-4000k/

It matches `rgbcw_lightbulb` at 100%, but three things differ:

- Colour temperature range is 1600-4000K, not 2700-6500K. The Smart Life app shows 1600K at temp_value 0.
- `colour` mode only drives a red LED (no green or blue). Brightness in red mode is the V part of dp 24: setting 20% in the app changed dp 24 to `000003e800cc`, dp 22 stayed at 175. Other hues stay red.
- dp 41 is `remote_switch` (enables the optional remote), not reversed do-not-disturb.

I made a config based on `rgbcw_lightbulb` with the 1600-4000K range, without Music, and with dp 41 as a Remote switch. yamllint and `tests/test_device_config.py` pass:
https://github.com/MarhyCZ/tuya-local/blob/oranzovka-cct-bulb/custom_components/tuya_local/devices/oranzovka_e2711w_lightbulb.yaml

I can open it as a PR when PRs are accepted again.

The E14 5W version (product id 6wji4o0vr9crq0y8, Tuya model string "Chytrá WiFi LED žárovka ORANŽOVKA E14 5W 1600-4000K") has the same data model; only the modelId differs. Its QueryThingsDataModel result:

```text
{
"result": {
"model": "{\"modelId\":\"e1ntscag\",\"services\":[{\"actions\":[],\"code\":\"\",\"description\":\"\",\"events\":[],\"name\":\"\",\"properties\":[{\"abilityId\":20,\"accessMode\":\"rw\",\"code\":\"switch_led\",\"description\":\"\",\"extensions\":{\"iconName\":\"icon-dp_power\",\"attribute\":\"641\"},\"name\":\"开关\",\"typeSpec\":{\"type\":\"bool\"}},{\"abilityId\":21,\"accessMode\":\"rw\",\"code\":\"work_mode\",\"description\":\"\",\"extensions\":{\"iconName\":\"icon-dp_mode\",\"attribute\":\"640\"},\"name\":\"工作模式\",\"typeSpec\":{\"type\":\"enum\",\"range\":[\"white\",\"colour\",\"scene\",\"music\"]}},{\"abilityId\":22,\"accessMode\":\"rw\",\"code\":\"bright_value\",\"description\":\"\",\"extensions\":{\"iconName\":\"icon-liangdu1\",\"attribute\":\"640\"},\"name\":\"白光亮度\",\"typeSpec\":{\"type\":\"value\",\"max\":1000,\"min\":10,\"scale\":0,\"step\":1}},{\"abilityId\":23,\"accessMode\":\"rw\",\"code\":\"temp_value\",\"description\":\"\",\"extensions\":{\"iconName\":\"icon-dp_half\",\"attribute\":\"640\"},\"name\":\"冷暖值\",\"typeSpec\":{\"type\":\"value\",\"max\":1000,\"min\":0,\"scale\":0,\"step\":1}},{\"abilityId\":24,\"accessMode\":\"rw\",\"code\":\"colour_data\",\"description\":\"彩光颜色、亮度、饱和度调节\",\"extensions\":{\"iconName\":\"icon-dp_mode\",\"attribute\":\"512\"},\"name\":\"彩光\",\"typeSpec\":{\"type\":\"string\",\"maxlen\":255}},{\"abilityId\":25,\"accessMode\":\"rw\",\"code\":\"scene_data\",\"description\":\"灯光情景\",\"extensions\":{\"iconName\":\"icon-dp_mode\",\"attribute\":\"512\"},\"name\":\"场景\",\"typeSpec\":{\"type\":\"string\",\"maxlen\":255}},{\"abilityId\":26,\"accessMode\":\"rw\",\"code\":\"countdown\",\"description\":\"\",\"extensions\":{\"iconName\":\"icon-a_nav_timer\",\"attribute\":\"640\"},\"name\":\"倒计时\",\"typeSpec\":{\"type\":\"value\",\"max\":86400,\"min\":0,\"scale\":0,\"step\":1,\"unit\":\"s\"}},{\"abilityId\":27,\"accessMode\":\"wr\",\"code\":\"music_data\",\"description\":\"通过APP内置律动算法实现灯光律动\",\"extensions\":{\"iconName\":\"icon-dp_mic\",\"attribute\":\"128\"},\"name\":\"音乐灯\",\"typeSpec\":{\"type\":\"string\",\"maxlen\":255}},{\"abilityId\":28,\"accessMode\":\"wr\",\"code\":\"control_data\",\"description\":\"用于实时下发数据实现实时预览效果\",\"extensions\":{\"iconName\":\"icon-dp_box2\",\"attribute\":\"640\"},\"name\":\"调节\",\"typeSpec\":{\"type\":\"string\",\"maxlen\":255}},{\"abilityId\":29,\"accessMode\":\"rw\",\"code\":\"debug_data\",\"description\":\"用于gamma调试，需配合支持gamma调试的面板使用\",\"extensions\":{\"iconName\":\"icon-dp_tool\",\"attribute\":\"128\"},\"name\":\"调试\",\"typeSpec\":{\"type\":\"string\",\"maxlen\":255}},{\"abilityId\":30,\"accessMode\":\"rw\",\"code\":\"rhythm_mode\",\"description\":\"不同时间段的色温、亮度根据人体节律自动调整\",\"extensions\":{\"iconName\":\"icon-dp_time3\",\"attribute\":\"640\"},\"name\":\"生物节律\",\"typeSpec\":{\"type\":\"raw\",\"maxlen\":255}},{\"abilityId\":31,\"accessMode\":\"rw\",\"code\":\"sleep_mode\",\"description\":\"温馨的灯光渐灭陪您进入甜美的梦乡\",\"extensions\":{\"iconName\":\"icon-dp_sleep\",\"attribute\":\"640\"},\"name\":\"灯光助眠\",\"typeSpec\":{\"type\":\"raw\",\"maxlen\":255}},{\"abilityId\":32,\"accessMode\":\"rw\",\"code\":\"wakeup_mode\",\"description\":\"柔和的灯光渐亮伴您迎接新的一天\",\"extensions\":{\"iconName\":\"icon-dp_sun\",\"attribute\":\"640\"},\"name\":\"灯光唤醒\",\"typeSpec\":{\"type\":\"raw\",\"maxlen\":255}},{\"abilityId\":33,\"accessMode\":\"rw\",\"code\":\"power_memory\",\"description\":\"用于设置断电再上电灯亮起的状态（不记忆APP关灯动作）\",\"extensions\":{\"iconName\":\"icon-dp_lightning\",\"attribute\":\"640\"},\"name\":\"断电记忆\",\"typeSpec\":{\"type\":\"raw\",\"maxlen\":255}},{\"abilityId\":34,\"accessMode\":\"rw\",\"code\":\"do_not_disturb\",\"description\":\"适用于经常停电的区域，避免停电再来电时亮灯打扰用户。开启通电勿扰，APP上关灯后需要连续两次上电才会亮灯\",\"extensions\":{\"iconName\":\"icon-dp_sleep\",\"attribute\":\"640\"},\"name\":\"停电勿扰\",\"typeSpec\":{\"type\":\"bool\"}},{\"abilityId\":35,\"accessMode\":\"rw\",\"code\":\"switch_gradient\",\"description\":\"开灯渐亮关灯渐暗\",\"extensions\":{\"iconName\":\"icon-dp_mode\",\"attribute\":\"0\"},\"name\":\"开关渐变\",\"typeSpec\":{\"type\":\"raw\",\"maxlen\":128}},{\"abilityId\":41,\"accessMode\":\"rw\",\"code\":\"remote_switch\",\"description\":\"\",\"extensions\":{\"iconName\":\"icon-dp_power2\",\"attribute\":\"0\"},\"name\":\"遥控器开关\",\"typeSpec\":{\"type\":\"bool\"}},{\"abilityId\":82,\"accessMode\":\"rw\",\"code\":\"candle_mode_data\",\"description\":\"模拟烛光效果\",\"extensions\":{\"iconName\":\"icon-huoyan\",\"attribute\":\"0\"},\"name\":\"模拟烛光\",\"typeSpec\":{\"type\":\"raw\",\"maxlen\":128}},{\"abilityId\":210,\"accessMode\":\"rw\",\"code\":\"random_timing\",\"description\":\"灯光随机亮灭模拟有人在家的场景\",\"extensions\":{\"iconName\":\"icon-dp_time3\",\"attribute\":\"128\"},\"name\":\"灯光看家\",\"typeSpec\":{\"type\":\"raw\",\"maxlen\":255}}]}]}"
},
"success": true,
"t": 1794764050812,
"tid": "c47eddeae11a11f1a9ef72eab2d043f9"
}
```
