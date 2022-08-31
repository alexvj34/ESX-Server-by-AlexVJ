### Это сборка сервера сделана на ESX фреймворке, она полностью готова к работе. Вам нужно лишь настроить ваши адреса, ключи и закачать базу данных данного сервера на свой ресурс. Это классическая сборка со всеми необходимыми инструментами, включая админский инструментарий с основными админискими командами и правами доступа.
### This is an ESX server build, ready to go. You only need to set up your addresses, keys and upload the database of this server to your resource. This is a classic build with all the necessary tools.

- Редактируйте файл `server.cfg` в нем замените `"insert the key here"` на ваши ключи доступа
- `set steam_webApiKey` тут вставьте ваш steamapikey
- `sv_licenseKey` Вставьте сюда ваш сгенерированный лицензионный ключ
- `sv_hostname` и `sets sv_projectName` Название хоста и название проекта
- `set mysql_connection_string` Тут нужно указать ключ для подключения базы данных
- Далее идут прописанные модули на сервере через команды `ensure/start`. При добавлении своих модулей, не забудьте их также прописать в файле `server.cfg`
- В папке `resources\[esx]` лежат все модули данной сборки и так же, в эту папку вам необходимо заливать ваши модули
- Чтобы загрузить базу данных этой сборки в ваш интерфейс, используейте файл `ESX Server RP by AlexVJ SQL DB.sql`

