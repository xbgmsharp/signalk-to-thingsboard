# Signal K to MQTT

Signal K server plugin to send all self SignalK numeric data, `navigation.position` and `navigation.attitude` and `navigation.state` to an MQTT broker for [ThingsBoard](https://thingsboard.io).

Coppy the `$ACCESS_TOKEN` as usernane.

Publish telemetry, `v1/devices/me/telemetry`, and attributes, `v1/devices/me/attributes`.

https://thingsboard.io/docs/reference/mqtt-api/#telemetry-upload-api

https://thingsboard.io/docs/reference/mqtt-api/#attributes-api

Attributes
![Screenshot 2022-04-03 at 23 08 14](https://user-images.githubusercontent.com/1498985/161448817-f5e0fea8-12c9-42ca-862b-d97611f16d60.png)

Telemetry
![Screenshot 2022-04-03 at 23 09 37](https://user-images.githubusercontent.com/1498985/161448823-cd3c4b63-862d-4d4c-98fd-585b8af69ffe.png)

Route Map TimeSeries
![Screenshot 2022-04-03 at 23 10 05](https://user-images.githubusercontent.com/1498985/161448824-b079f9e1-e336-4c1e-ac4a-9eb3e5685a0a.png)
