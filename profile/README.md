# Kosareva Cloud

Kosareva Cloud даёт компаниям и разработчикам один API к моделям OpenAI, Anthropic, Google, xAI, DeepSeek, Moonshot AI, Qwen, MiniMax, GigaChat, YandexGPT и других вендоров. Ключ один, форматы OpenAI и Anthropic, оплата в рублях. В каталоге более 170 моделей: текст, картинки, видео, эмбеддинги, озвучка, музыка.

**Мы работаем только через настоящий API вендоров и не используем подписки ChatGPT, Claude Code или IDE как канал для API.**

Работаем через российское ИП или через армянское ООО «Kosareva Cloud», налоговый номер 03038101, вы выбираете, что удобнее. Основательница и CEO: Вероника Косарева.

## С чего начать

| Что нужно | Куда идти |
|---|---|
| Вся документация в одном месте | [Kosareva-Cloud/documents](https://github.com/Kosareva-Cloud/documents) |
| Подключить инструмент или написать первый запрос | [Инструкция и примеры](https://github.com/Kosareva-Cloud/documents/blob/main/guides/README.md) |
| Подключить компанию: договор, счёт, данные, боты | [Kosareva Cloud: AI API для бизнеса](https://github.com/Kosareva-Cloud/documents/blob/main/business/README.md) |
| Понять, как мы работаем и чего у нас нет | [Принципы](https://github.com/Kosareva-Cloud/documents/blob/main/principles/README.md) |
| Посмотреть цены | [kosareva.cloud/prices/](https://kosareva.cloud/prices/), для программ [JSON без ключа](https://kosareva.cloud/panel/api/price-catalog) |
| Прочитать документацию API | [kosareva.cloud/docs/](https://kosareva.cloud/docs/) |

## Что мы делаем

- **AI API.** Один ключ на оба формата: `https://api.kosareva.cloud/v1` для OpenAI, `https://api.kosareva.cloud` для Anthropic. Абонентской платы нет, списание по факту. Карта российского банка или СБП от 50 ₽, по счёту от 1 000 ₽.
- **API Guard.** Заменяет заглушками 22 типа данных до отправки в модель и разворачивает ответ обратно. Включается заменой адреса: `https://api.kosareva.cloud/guard/v1` для OpenAI SDK, `https://api.kosareva.cloud/guard` для Anthropic SDK. На обычном `/v1` маскирования нет. [Что находит и чего не находит](https://kosareva.cloud/api-guard/).
- **Ключи «Только модели в РФ».** Такой ключ работает только с моделями, которые запущены в российском ЦОД.
- **Расширение для VS Code.** Даёт модели родному чату и agent mode редактора, ключ хранит в SecretStorage. [Marketplace](https://marketplace.visualstudio.com/items?itemName=kosareva-cloud.kosareva-cloud).
- **Скиллы и справочник.** [Скиллы для агентов](https://kosareva.cloud/skills/), [инструкции по инструментам](https://kosareva.cloud/instrumenty/), [справочник ошибок](https://kosareva.cloud/spravochnik/).
- **Внедрение.** Помогаем с интеграцией, делаем ботов и агентов под задачу. Пилот 1–2 недели, пакеты от 49 000 ₽, работа моделей оплачивается отдельно, условия подтверждаем перед договором. [Описание услуги](https://kosareva.cloud/vnedrenie-ii/).

## Чего у нас нет

Batch API. Полный список в [принципах](https://github.com/Kosareva-Cloud/documents/blob/main/principles/README.md#чего-у-нас-нет).

## Связь

[kosareva.cloud](https://kosareva.cloud) · ceo@kosareva.cloud · Telegram [@kosareva_cloud](https://t.me/kosareva_cloud) · +7 995 154-15-35. Отвечаем в рабочий день.

Уязвимость нашли: [SECURITY.md](https://github.com/Kosareva-Cloud/.github/blob/main/SECURITY.md).

---

## In English

Kosareva Cloud provides one API key for models from OpenAI, Anthropic, Google, xAI, DeepSeek, Moonshot AI, Qwen, MiniMax, GigaChat, YandexGPT and other vendors, in the OpenAI and Anthropic formats. We work only through the real vendor APIs and don't use ChatGPT, Claude Code or IDE subscriptions as an API channel. The catalog holds more than 170 models. Billing is pay-as-you-go in rubles, with no subscription fee. We work through a Russian sole proprietor or through "Kosareva Cloud" LLC, Armenia, tax number 03038101, and you choose whichever suits you better.

API Guard masks 22 data types before a request reaches a model. A "Models in RF only" key restricts access to models in a Russian data center. We also help with integration and build bots and agents.

All documentation is in one place: [Kosareva-Cloud/documents](https://github.com/Kosareva-Cloud/documents). Start here: [connection guide](https://github.com/Kosareva-Cloud/documents/blob/main/guides/README.en.md), [AI API for companies](https://github.com/Kosareva-Cloud/documents/blob/main/business/README.en.md), [principles and what we don't offer](https://github.com/Kosareva-Cloud/documents/blob/main/principles/README.en.md). Contact: ceo@kosareva.cloud.
