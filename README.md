# Что такое VKBotKit?

VKBotKit это Python фреймворк, предназначенный для работы чат-бота в сообществе ВКонтакте.  
VKBotKit спроектирован с целью упростить и структуризировать контент и настроиваемый функционал. Библиотека работает в связке с VK Bots API, а также библиотекой aiohttp.  
VKBotKit - духовный наследник TestCanaryBot.
## Структура фреймворка

* `vkbotkit` - основной функционал фреймворка
* `vkbotkit.objects` - вспомогательные объекты для работы модулей
* `vkbotkit.objects.callback` - инструменты для регистрации обработчиков
* `vkbotkit.objects.data` - обёртки вокруг dict
* `vkbotkit.objects.enums` - вспомогательные списки
* `vkbotkit.objects.exceptions` - исключения
* `vkbotkit.objects.filters` - фильтры
* `vkbotkit.objects.filters.actions` - фильтры для работы с action событиями
* `vkbotkit.objects.filters.events` - фильтры для работы с событиями Longpoll
* `vkbotkit.objects.filters.filter` - базовые фильтры
* `vkbotkit.objects.filters.message` - фильтры для работы с сообщениями
* `vkbotkit.objects.keyboard` - объекты клавиатуры
* `vkbotkit.objects.mention` - объект упоминания
* `vkbotkit.objects.package` - объект события и прикладные объекты для тайпинга
* `vkbotkit.utils` - прикладные инструменты

## Полезные ссылки

* [template](https://github.com/miuruwa/vkbotkit-template)
