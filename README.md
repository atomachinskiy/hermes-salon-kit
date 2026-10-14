# Hermes для салона: настройка в одну фразу

Набор для участников воркшопа «Нейросети для бьюти-бизнеса»: инструкция, по которой агент Hermes настраивает себя сам, и 12 скиллов под стратегию, маркетинг и контент салона.

## Как запустить

Вставьте в чат Hermes и отправьте:

> Настрой себя по инструкции https://raw.githubusercontent.com/atomachinskiy/hermes-salon-kit/main/SETUP.md

Агент сам поставит скиллы, включит картинки через подписку ChatGPT, проверит поиск и браузер, переведёт голосовые на русский. Google и Telegram он подключит вместе с вами: подскажет, какую кнопку нажать. Если Hermes попросит одобрение, нажмите «Одобрить».

## Скиллы

| Скилл | Язык | Для чего |
|---|---|---|
| product-marketing | EN | Паспорт салона: услуги, клиенты, позиционирование |
| swot-analysis | EN | Сильные и слабые стороны, возможности и угрозы |
| price-check | RU | Маржа по услугам и три сценария цены |
| customer-journey-map | EN | Путь клиента до повторного визита |
| analiz-konkurentov | RU | Офферы, цены и каналы конкурентов |
| campaign-plan | EN | Маркетинговый план: цели, аудитории, сообщения, каналы, календарь |
| kontent-plan | RU | Контент-план и готовые посты |
| social | EN | Посты для Instagram и VK, сценарии коротких видео |
| offers | EN | Спецпредложения без скидок |
| sms | EN | Рассылки: приветствие, после визита, возврат клиента |
| generaciya-kreativov | RU | Тексты креативов и брифы |
| carousel-writer-sms | EN | Текст карусели по слайдам |

Скиллы на английском работают и по-русски.

## Источники и лицензии

Скиллы взяты без изменений из открытых репозиториев, тексты лицензий в папке `LICENSES`.

- https://github.com/coreyhaines31/marketingskills (MIT): product-marketing, social, offers, sms
- https://github.com/phuryn/pm-skills (MIT): swot-analysis, customer-journey-map
- https://github.com/ilyautov/small-business-ru (Apache-2.0): price-check
- https://github.com/anthropics/knowledge-work-plugins (Apache-2.0): campaign-plan
- https://github.com/atomachinskiy/hermes-marketing-skills (MIT): analiz-konkurentov, kontent-plan, generaciya-kreativov
- https://github.com/blacktwist/social-media-skills (MIT): carousel-writer-sms
