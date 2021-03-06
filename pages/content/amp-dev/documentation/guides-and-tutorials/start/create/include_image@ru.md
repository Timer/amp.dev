---
"$title": Добавление изображений
"$order": '2'
description: Большинство HTML-тегов можно непосредственно использовать в AMP HTML, однако некоторые теги, такие как <img>, заменяются эквивалентными или обладающими расширенной функциональностью тегами AMP HTML
author: pbakaus
contributors:
- bpaduch
---

Большинство тегов HTML может быть использовано непосредственно в AMP HTML, однако некоторые теги, такие как `<img>`, заменяются своим эквивалентом или слегка расширенными персонализированными тегами AMP HTML (также запрещено использование нескольких проблемных тегов, см. [описание тегов HTML в спецификации AMP](../../../../documentation/guides-and-tutorials/learn/spec/amphtml.md)).

Для демонстрации того, как может выглядеть дополнительная разметка, ниже приведен пример кода для встраивания изображения в страницу:

[sourcecode:html]
<amp-img src="welcome.jpg" alt="Welcome" height="400" width="800"></amp-img>
[/sourcecode]

Чтобы узнать о причинах замены тегов `<img>` на [`<amp-img>`](../../../../documentation/components/reference/amp-img.md), а также о других доступных возможностях, ознакомьтесь с разделом [Вставка встроенных фреймов и мультимедийного содержимого](../../../../documentation/guides-and-tutorials/develop/media_iframes_3p/index.md).
