Получение полного русского названия страны в PHP по ISO-коду.
Поддерживаются только двухбуквенные коды.

Подключение осуществляется добавлением зависимости в composer.json:

```JSON
{
    "require": {
        "perk11/russianisocc": "*"
    }
}
```
После этого необходимо выполнить команду:

```bash
composer update perk11/russianisocc
```

Пример использования:

```PHP        
$countryCodes=new RussianISOCC\CountryCodes;
echo $countryCodes->getCountryNameByTwoLetterCode('RU');
```