## Climate Component
### Configuration variables:
**name** (Optional): Name to use in the frontend<br />
**device_code** (Required): ......<br />
**controller_send_service** (Required): ......<br />
**temperature_sensor** (Optional): **entity_id** for a temperature sensor<br />
**humidity_sensor** (Optional): **entity_id** for a humidity sensor<br />
**power_sensor** (Optional): ...... (Accepts On/Off)<br />

### Example:
```yaml
climate:
  - platform: smartir
    name: Office AC
    device_code: 1000
    controller_send_service: switch.broadlink_send_packet_192_168_10_59
    temperature_sensor: sensor.temperature
    humidity_sensor: sensor.humidity
    power_sensor: binary_sensor.ac_power
```

### Available codes for climate devices:
#### Toyotomi
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1000|AKIRA GAN/GAG-A128 VL|Broadlink

#### Panasonic
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1020|CS-CE7HKEW<br>CS-CE9HKEW<br>CS-CE12HKEW|Broadlink
1021|CS-RE9GKE<br>CS-RE12GKE|Broadlink
1022|CS-Z25TK|Broadlink

#### General Electric
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1040|Unknown model|Broadlink

#### LG
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1060|R09AWN<br>R24AWN<br>E09EK|Broadlink
1061|Unknown model|Broadlink

#### Hitachi
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1080|Unknown model|Broadlink
1081|RAS-10EH3|Broadlink

#### Daikin
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1100|Unknown model|Broadlink
1101|FTXS20LVMA<br>FTXS25LVMA<br>FTXS35LVMA<br>FTXS46LVMA<br>FTXS50LVMA<br>FTXS60LVMA<br>FTXS71LVMA<br>FTXS85LVMA<br>FTXS95LVMA|Broadlink

#### Mitsubishi Electric
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1120|MSZ-GL25VGD<br>MSZ-GL35VGD<br>MSZ-GL42VGD<br>MSZ-GL50VG<br>MSZ-GL60VGD<br>MSZ-GL71VGD<br>MSZ-GL80VGD|Broadlink
1121|Unknown model|Broadlink

#### Actron
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1140|Unknown model|Broadlink

#### Carrier
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1160|Unknown model|Broadlink

#### Gree
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1180|Unknown model|Broadlink
1181|Unknown model|Broadlink

#### Tosot
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1200|Unknown model|Broadlink

#### Sungold
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1220|Unknown model|Broadlink

#### Consul
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1240|Unknown model|Broadlink

#### Toshiba
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1260|RAS-13NKV-E / RAS-13NAV-E<br>RAS-13NKV-A / RAS-13NAV-A<br>RAS-16NKV-E / RAS-16NAV-E<br>RAS-16NKV-A / RAS-16NAV-A|Broadlink

#### Fujitsu
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1280|AR-RBE1E|Broadlink
1281|Unknown model|Broadlink

#### Sharp
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1300|Unknown model|Broadlink

#### Haier
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1320|Unknown model|Broadlink

#### Tadiran
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1340|Unknown model|Broadlink

#### Springer
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1360|Split Hi Wall Maxiflex|Broadlink

#### Midea
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1380|Unknown model|Broadlink

#### Samsung
| Code | Supported Models | Controller |
| ------------- | -------------------------- | ------------- |
1400|Unknown model|Broadlink