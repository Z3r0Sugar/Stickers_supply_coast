Create by @zer0_sugar

Софт парсит флор стикеров по коллекциям и заносит данные в таблицу с Initial price (stars), Initial price ($), Issued, Date.

СОФТ МОЖЕТ НЕ РАБОТАТЬ С ВКЛЮЧЕННЫМ VPN

В папке есть ВИДЕОГАЙД

1. Получить x-user-data. Открываем Telgram Web - переходим в чат с ботом PalaceNFT - нажимаем F12 - переходим во вкладку Network - нажимаем Ctrl+R - запускаем бота PalaceNFT - Нажимаем Ctrl+F - в поиске вбиваем "palacenft.com/api/" - Enter - нажимаем на подсвеченный вариант - во вкладке Headers в самом низу будет x-user-data - копируем, начиная с user= (само слово x-user-data копировать не нужно)
2. Вставить x-user-data в текстовый файл user_data в формате "user=%7B%22id%22%3A6988..."
3. Запустить софт (откроется консоль с парсингом)
4. После завершения работы появится сообщение "Парсинг завершён. Для закрытия окна нажмите Enter". Нажимаем Enter
5. Открываем последнюю таблицу floor_prices (после кажого запуска скрипта создаётся новая таблица)

Некоторые ячейки могут остаться незаполненными - это значит что данных нет в stickerdom.store
