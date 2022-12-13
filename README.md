# Путеводитель по настройке мода

Здесь вы найдете все основные настройки нашего мода

## Оглавление
- [Общие форматы заполнения](#Общие-форматы-заполнения)
- [Зоны телепортации при перезаходе](#Зоны-телепортации-при-перезаходе)

## Зоны телепортации при перезаходе
Данная настройка не запрещает выход в заданных зонах, она лишь телепортирует игрока в случайную позицию при заходе с выводом уведомления

+ Все файлы находятся по пути: [___NewStory\Configurations\RelogBanOnPositions___](https://github.com/HunKloud/NewStory-DayZ-Doc/tree/main/Server/profiles/NewStory/Configurations/RelogBanOnPositions/)
+ Кроме того все файлы имеют рассширения ___.json___
+ Название файла может быть любым, но желательно что было понятно для какой зоны он сделан
    + Например: ___KordonDungeon.json___

Существует 2 типа зон:
1. В виде прямоугольника
2. В виде сферы

### Прямоугольник

+ **PointMin** - это левая нижняя координата
+ **PointMax** - это правая верхняя координата
+ **Positions** - Список координат, куда будет перемещен игрок при заходе

```json
{
    "PointMin": [ 8813.053711, 68.823990, 1651.510376 ],
    "PointMax": [ 8668.410156, 150.476456, 1797.680054 ],
    "Positions": [
        [ 6423.632813, 80.234993, 1134.679688 ],
        [ 6423.632813, 80.234993, 1134.679688 ]
    ]
}
```

### Сфера

+ **PointMin** - В данном случае это центр сферы
+ **Radius** - Это радиус сферы
+ **Positions** - Список координат, куда будет перемещен игрок при заходе

```json
{
    "PointMin": [ 6317.997559, 92.129951, 731.253906 ],
    "Radius": 100,
    "Positions": [
        [ 6423.632813, 80.234993, 1134.679688 ],
        [ 6423.632813, 80.234993, 1134.679688 ]
    ]
}
```
[Оглавление](#Оглавление)



## Общие форматы заполнения


