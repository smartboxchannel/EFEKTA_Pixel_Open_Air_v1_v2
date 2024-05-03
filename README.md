# EFEKTA_Pixel_Open_Air

Поблагодарить автора: [https://yoomoney.ru/fundraise/P2XLTgJsB6k.231012](https://yoomoney.ru/fundraise/P2XLTgJsB6k.231012)

Thank the author: [https://yoomoney.ru/fundraise/P2XLTgJsB6k.231012](https://yoomoney.ru/fundraise/P2XLTgJsB6k.231012)

Телеграм чат DIY Devices - https://t.me/diy_devices

Продажа DIY Устройств - https://t.me/diydevmart

Только для не коммерческого использования. Запрещается использовать проект или его части в коммерческих целях без согласования с автором проекта.

For non-commercial use only. It is forbidden to use the project or its parts for commercial purposes without the consent of the author of the project.

hello@efektalab.com

Проект zigbee датчика мониторинга углекислого газа, температуры и влажности воздуха c LCD дисплеем EFEKTA Pixel Open Air.

Zigbee project of a carbon dioxide, temperature and humidity monitoring sensor with an EFEKTA Pixel Open Air LCD display.

![EFEKTA Pixel Open Air](https://raw.githubusercontent.com/smartboxchannel/EFEKTA_Pixel_Open_Air/main/Images/001.png) 

![EFEKTA Pixel Open Air](https://raw.githubusercontent.com/smartboxchannel/EFEKTA_Pixel_Open_Air/main/Images/003.png)

![EFEKTA Pixel Open Air](https://raw.githubusercontent.com/smartboxchannel/EFEKTA_Pixel_Open_Air/main/Images/004.png)

Для прошивки необходимо подключить базовую плату к SmartRF04EB и прошить через программу SmartRF Flash Programmer

For firmware, you need to connect the base board to SmartRF04EB and flash it through the SmartRF Flash Programmer program

![EFEKTA Pixel Open Air](https://raw.githubusercontent.com/smartboxchannel/EFEKTA_Pixel_Open_Air/main/Images/009.png)

Для работы устройства в сети zigbee через zigbee2mqtt необходимо установить внешний конвертер.

To operate the device on the zigbee network via zigbee2mqtt, an external converter must be installed.


### JOIN

Чтобы подключить датчик к сети, координатор должен быть включен для приема новых устройств. После этого нужно удерживать нажатой кнопку на датчике около 5 секунд, на дисплее появится сообщение о начале входа в сеть.

To join the sensor to the network, the coordinator must be turned on to receive new devices. After that, you need to hold down the button on the sensor for about 5 seconds, a message will appear on the display about the start of logging in to the network.


### LEAVE

Чтобы отключить датчик от сети zigbee, удерживайте нажатой кнопку на датчике около 10 секунд, и на дисплее появится сообщение о выходе из сети zigbee.

To remove the sensor from the zigbee network, hold down the button on the sensor for about 10 seconds, and a message about disconnecting from the network will appear on the display.

