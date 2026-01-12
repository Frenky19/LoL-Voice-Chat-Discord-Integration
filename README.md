# Rift Talk — Desktop Application

## Открытый исходный код можно посмотреть тут: https://github.com/Frenky19/RiftTalk

## Установка
1. Распакуйте все файлы в одну папку
2. Запустите **Start.bat** или **RiftTalk.exe**

## Примечание по безопасности
- Приложение подписано **самоподписанным сертификатом**
- Windows может показать предупреждение **"Unknown Publisher"**
- Это **нормально** для self-signed приложений
- Нажмите **"Подробнее" → "Выполнить в любом случае"**

## Возможности
- ✅ Встроенный интерфейс (браузер не нужен)
- ✅ Подписанный EXE (self-signed)
- ✅ Нет консольного окна
- ✅ Автоматический запуск сервера
- ✅ Автоматическое подключение к голосовым каналам команды

## Первый запуск
1. Примите предупреждение безопасности, если оно появилось
2. Откроется окно приложения с интерфейсом
3. Нажмите **"Привязать Discord"** и завершите авторизацию
4. Запустите **League of Legends** (League Client должен быть открыт)
5. Заходите в матч — **в момент начала игры** приложение автоматически закинет вас в голосовой канал вашей команды (если тиммейты тоже используют приложение)

## Как это работает
- На старте матча создаются временные голосовые каналы для **Blue/Red**
- Участникам выдаются роли/доступы и выполняется подключение к каналу команды
- После окончания матча:
  - пользователи удаляются из временных каналов
  - роли/доступы снимаются
  - временные каналы удаляются

## Важно
- Discord-аккаунт должен быть **привязан**
- Вы должны находиться на нужном Discord-сервере (где работает бот)
- Если Discord недоступен — приложение не сможет работать (strict mode)

## Troubleshooting
- Предупреждение безопасности/SmartScreen: это ожидаемо → **"Подробнее" → "Выполнить в любом случае"**
- Если не закинуло в канал:
  - приложение запущено?
  - Discord запущен и вы залогинены?
  - аккаунт привязан?
  - вы на нужном сервере?
  - попробуйте перезапустить приложение и Discord

## License

```
MIT License

Copyright (c) 2026 Frenky19

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```