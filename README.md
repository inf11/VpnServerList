# Vpn_server_list
Бесплатные сервера и их установка для OpenVPN, Outline и Wireguard.
Подключение серверов VpnGate по L2TP в Android, IOS.
Подключение серверов VpnGate в Windows 10 по L2TP, SSTP.

## Для OpenVPN
- [FreeOpenVpn](https://www.freeopenvpn.org/)
- [VpnGate](https://vpngate.net/)
- [ProtonVpn](https://protonvpn.com/)
- [ZenMate](https://zenmate.com/) (7day trial)
- [Vpnunlimited](https://vpnunlimited.com/) (7day trial)

## Для Outline
- https://getoutline.me

## Для Wireguard
- [ProtonVpn](https://protonvpn.com/)
- [Vpnunlimited](https://vpnunlimited.com/) (7day trial)

## Установка OpenVPN
1. Переходим на [Сайт](https://openvpn.net/community-downloads/)
2. Выбираем (32-bit, 64-bit, ARM64), загружаем
3. Устанавливаем, запускаем
4. Выбираем Import.
5. Добавляем файл .ovpn
6. Подключаемся

## Установка Outline
1. Переходим на [Сайт](https://getoutline.org/ru/get-started/#step-3/)
2. Выбираем свою ОС Windows/Mac/Linux/Android/IOS, загружаем
3. Устанавливаем, запускаем
4. Добавляем ключ
5. Подключаем

## Установка Wireguard на серверах ProtonVPN
1. Переходим на [Сайт](https://protonvpn.com/)
2. Входим или создаём аккаунт(Sign in/Create free account)
3. После входа переходим в "Загрузки"
4. Выбераем "Конфигурация WireGuard"
5. "Дайте имя генерируемой конфигурации"(Назовите конфигурацию)
6. "Выберите платформу"(На каком устройстве будет использоваться конфигурация)
7. Выбераем сервер ниже и нажимаем "Создать"
8. Скачиваем файл конфигурации
9. Переходим на [Сайт](https://www.wireguard.com/install/)
10. Выбераем платформу(Android, Windows, Mac, Linux, IOS)
11. Загружаем и запускаем установщик
12. Наживаем "Добавить туннель" выбераем файл конфигурации
13. Подключаемся

## Подключение VpnGate по L2TP в Android
1. Переходи *Настройки - Сеть и интернет - Дополнительно - VPN*
2. Нажимаем +
3. Переходим на [Сайт](https://vpngate.net/)
4. Копируем url & ip любого сервера
5. (переходим обратно)
- Выбираем Тип - L2TP/IPSec PSK
- Название *Любое*
- Адрес *Вставляем url & ip*
- Общий ключ IPSec, имя пользователя, Пароль - *vpn* 
> Указано на сайте VpnGate
- Сохраняем, подключаемся

## Подключение VpnGate по L2TP в IOS
1. Переходим *Настройки - Основные - VPN - Добавить конфигурацию*
2. Переходим на [Сайт](https://vpngate.net/)
3. Копируем url & ip любого сервера
4. (переходим обратно)
- Выбираем Тип - L2TP
- Описание *Любое*
- Сервер *Вставляем url & ip*
- Общий ключ IPSec, имя пользователя, Пароль - *vpn* 
> Указано на сайте VpnGate
- Сохраняем, подключаемся

## Подключение VpnGate по (L2TP & SSTP) в Windows 10
1. Переходим *Настройки - Сеть и Интернет - VPN*
2. Нажимаем *Добавить VPN-подключение*
3. Переходим на [Сайт](https://vpngate.net/)
4. Копируем url & ip любого сервера
5. (переходим обратно)
6. *Поставщик услуг VPN* - Windows
- *Имя подключения* - *Название любое*
- *Имя или адрес сервера* - *Вставляем url & ip*
7. Для L2TP
- *Тип VPN* - *L2TP/IPSec с общим ключом*
- *Общий ключ, Имя пользователя, Пароль* - vpn
8. Для SSTP
- *Тип VPN* - *Протокол SSTP*
- *Имя пользователя, Пароль* - vpn
9. Сохраняем
10. Подключаемся
