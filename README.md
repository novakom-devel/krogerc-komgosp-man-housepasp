Документація базується на документ-генераторі [**Daux.io**](https://dauxio.github.io/).

## Інсталяція

Насамперед необхідно, щоб у вас був встановлена мова програмування [PHP](https://php.net) (гілка 7.X версія не нижче 7.2) та його розширення [composer](https://getcomposer.org/). Далі зайдіть в папку `krogerc-komgosp-man-housepasp`, та виконайте команду, після якої будуть встановлені всі необхідні додатки.

```
composer update
```

## Старт динамічної документації

Для старту документації, необхідно виконати

```
./serve
```

Після чого можна зайти з браузера за адресою `http://<ваш хост>:8086/`

## Генерація статичної документації

Є можливість сгенерувати статичну HTML-документацію.

```
bin/daux generate
```

Після виконання в директорії `static` буде розміщено корінь із всіма сторінками. Для браузінгу відкривайте сторінку `index.html` у браузеру.

## Підтримка

Якщо знайшли помилку або маєте пропозиції щодо покращення документації, то просимо вас повідомити:

- [GitHub issue](https://github.com/novakom-devel/krogerc-komgosp-man-housepasp/issues)
- на електрону пошту <a href="mailto:novakom.devel@gmail.com?subject=Krogerc komgosp manual issue">novakom.devel@gmail.com</a>
- завести заявку у [центрі звернень криворізького русерсного центру](https://krmisto.gov.ua/ua/komcentr/register/internal.html) тільки для зареєстрованих користувачів
