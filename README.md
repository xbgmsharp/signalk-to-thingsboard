# Signal K to MQTT

Signal K server plugin to send all self SignalK numeric data, `navigation.position` and `navigation.attitude` and `navigation.state` to an MQTT broker for [ThingsBoard](https://thingsboard.io).

Coppy the `$ACCESS_TOKEN` as usernane.

Publish telemetry, `v1/devices/me/telemetry`, and attributes, `v1/devices/me/attributes`.

https://thingsboard.io/docs/reference/mqtt-api/#telemetry-upload-api

https://thingsboard.io/docs/reference/mqtt-api/#attributes-api
