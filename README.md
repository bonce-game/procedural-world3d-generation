# GenerationMap3dTilesInUnity
## Процедурная генерация уровня пользовательскими 3d тайлами.

## Как работает:
При старте программа считывает цвет всех сторон 3д тайла и сопоставляет с цветом других тайлов. Если цвета схожи, значит тайлы совместимы. Далее происходит подстановка возможных тайлов друг к другу. 

Можно использовать к уже сделанному тайловому участку, если это нужно. Программа произведёт генерацию вокруг этого места.

## Небольшая инструкция:
1) Добавьте скрипты в проект и добавьте их к объекту на сцене
2) Добавляйте 3д тайлы
3) Установите ширину и длину карты
4) Настраивайте веса тайлов
5) Наблюдайте.

При нажатии на "D" карта будет перегенерированна
