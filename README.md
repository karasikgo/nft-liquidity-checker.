# NFT Liquidity Checker — учебная демонстрация

Сайт принимает только тестовые коды формата `DEMO-1234` и отправляет такой код в Telegram через сервер.
Настоящие API-ключи, пароли и другие секреты не принимаются.

## Публикация на Render

1. Создайте GitHub-репозиторий и загрузите в него все файлы проекта.
2. На Render выберите **New → Web Service** и подключите репозиторий.
3. Укажите:
   - **Runtime:** Node
   - **Build Command:** `npm install`
   - **Start Command:** `npm start`
4. В разделе **Environment** добавьте переменные:
   - `BOT_TOKEN` — токен Telegram-бота
   - `CHAT_ID` — ваш Telegram Chat ID
5. Нажмите **Create Web Service**. После публикации Render выдаст ссылку на сайт.

Не помещайте токен бота в HTML, JavaScript на клиенте, GitHub или публичные сообщения.
Если токен случайно стал публичным, перевыпустите его через BotFather.

## Локальный запуск

Требуется Node.js 18 или новее.

```bash
npm start
```

Откройте `http://localhost:3000` в браузере.
