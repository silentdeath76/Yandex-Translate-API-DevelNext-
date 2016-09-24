# Yandex Translate API (DevelNext)

Скачать уже собранный пакет: [yandex](https://yadi.sk/d/0WFXkixfvYpkg)

Подключить пакет "Yandex Translate API" и "HTTP Client".

##### Пример использования:

```php
$yandex = new YandexTranslate('youre token');
$yandex->translate("Hello yandex!", "en-ru"); // Вернет переведенный текст или произойдет иключение
```

Токен можно получить [тут](https://tech.yandex.ru/keys/get/?service=trnsl)