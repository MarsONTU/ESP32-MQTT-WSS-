# ESP32-MQTT-WSS-
ESP32连接到云端平台EMQX cloud实现”发布与订阅“
https://cloud.emqx.com/console/
注册好emqx cloud的账号后可以选择免费试用的版本，完成配置后会给你分配自己的服务器

<img src="https://user-images.githubusercontent.com/75484275/222433676-20796081-550c-43d2-a362-866ac90e0c5f.png" width="300px">

连接地址就是例程中uri内yourxxxxx代替的部分，当然别忘记在配置菜单中设置你的wifi ssid和password。
例程会在MQTT连接成功后自动订阅名为/topic/qos0和/topic/qos1的Topic，并且在订阅成功后向服务器发送/topic/qos0的数据
建议下载MQTTX客户端进行调试
