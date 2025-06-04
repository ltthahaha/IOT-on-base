![image](https://github.com/user-attachments/assets/cdbbbdf1-1f84-470d-8262-7ef0dcbbe5f3)
此自助洗浴系统以Arduino Uno为核心控制模块，外接DHT11温湿度传感器、LM35温度传感器、水位测量模块、人体感应模块、触摸传感器等一系列模块来获取浴室的环境和状态信息，并可以做到自动控制相应的设备来达到智能洗浴的目的。 外加RFID-RC522模块来识别用户身份。通过ESP8266WiFi模块来实现数据上传到OneNet云平台，OneNet整理数据并显示到数据流中。微信小程序通过调用OneNet API接口来获取到设备最新数据，在小程序页面进行实时展示并且可以下发命令来对浴室的设备进行控制和管理。Web端调用OneNet API接口来实现对浴室环境各项数据的实时查看并进行数据的管理。![image](https://github.com/user-attachments/assets/cf0d2a46-05ec-4743-b3a2-7fe5d24d09a9)

