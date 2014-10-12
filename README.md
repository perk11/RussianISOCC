Получение полного русского названия страны в PHP по ISO-коду.
Поддерживаются только двухбуквенные коды.
Пример использования:

```PHP        
$countryCodes=new RussianISOCC\CountryCodes;
echo $countryCodes->getCountryNameByTwoLetterCode('RU');
```