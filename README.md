# email_domens

Обнаружение сайта организации на основе его почтового домена.
Часто встречается, что сайт организации и почтовый домен сотрудников имеют один и тот же адрес.
• вычленяем домен из email
• убираем известные почтовые сервисы и возможные опечатки/ошибки в адресе почты (set "mails")
• отправляем запросы, чтобы проверить доступность сайта
• убираем те, что пришли с проблемными статусами, с текстом в заголовке о продаже или неоплате домена

Получаем таблицу 
+ с id организации</n>
• уникальным доменами, принадлежащими её сотрудникам

• адресом, на который могло перенаправить запрос (адрес сайта)

• кодом статуса

• заголовком сайта (для возможной разметки организации по виду деятельности, исходя из текста)
