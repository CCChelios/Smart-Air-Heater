# Smart-Air-Heater-ESPHome

![image](https://user-images.githubusercontent.com/34306652/206859126-79191782-733e-4495-9d56-a73d8bc7acbb.png)

Этот проект демонстрирует умный контроллер обогревателя, созданный с использованием фреймворка ESPHome. Контроллер обеспечивает точное регулирование температуры и плавное управление нагревательными элементами с помощью постепенной модуляции ШИМ.

## Возможности

- **Точность температуры:** Обогреватель поддерживает температуру в помещении с точностью до 0.1 градуса Цельсия.
- **Плавное управление нагревом:** Нагревательные элементы регулируются с помощью плавной модуляции ШИМ, обеспечивая плавное и стабильное повышение температуры.

## Компоненты

- Микроконтроллер: ESP8266 или ESP32
- Датчик температуры: DS18B20 или DHT22
- Нагревательный элемент: [Укажите детали вашего нагревательного элемента]

## Функциональность

- **Удаленное управление:** Обогреватель можно включать и выключать удаленно через платформу умного дома или приложение.
- **Регулирование температуры:** Используя данные с датчика температуры, обогреватель поддерживает заданную температуру. Если текущая температура опускается ниже установленной, обогреватель включается для нагрева окружающей среды.
- **Расписание:** Обогреватель может быть настроен на работу по расписанию, позволяя включаться утром и выключаться ночью.

## Интеграция в систему умного дома

- **Home Assistant:** Интегрируйте обогреватель в вашу систему умного дома через MQTT или нативную интеграцию ESPHome в Home Assistant.
- **Удаленное управление:** Управляйте и мониторьте обогреватель удаленно через платформу умного дома или приложение. Отслеживайте текущую температуру и статус обогревателя.

## Меры безопасности

- **Защита от перегрева:** Датчик температуры предотвращает перегрев, отключая обогреватель при слишком высокой температуре.

## Дополнительные функции

- **Дисплей:** Добавьте светодиоды или OLED-дисплей для визуализации текущей температуры и статуса обогревателя.
- **Интеграция с другими устройствами:** Интегрируйте обогреватель с другими умными устройствами, такими как термостаты или системы автоматизации.

## Схема подключения

Вставьте здесь схему подключения, чтобы помочь пользователям правильно соединить компоненты.

## Начало работы

Следуйте этим шагам, чтобы настроить контроллер обогревателя:

1. Загрузите прошивку ESPHome на ваш микроконтроллер.
2. Подключите датчик температуры и нагревательный элемент согласно предоставленной схеме подключения.
3. Настройте прошивку ESPHome с вашими Wi-Fi данными и желаемыми настройками.
4. Загрузите конфигурацию и отслеживайте устройство в панели управления ESPHome.

## Планы на будущее

Укажите будущие улучшения или функции, которые вы планируете добавить в контроллер обогревателя.

## Лицензия

Этот проект распространяется под лицензией [MIT License](LICENSE).
