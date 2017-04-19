goit-webinar-proj

Live page at: https://axzerk.github.io/goit-webinar-proj/build

1 - Исходники лежат в папке src, там я думаю понятно по папкам внутри где что.

2 - (@import "tools";) - этот импорт без сборщика работать не будет, скопируйте все переменные из media и color-map в один .scss файл и его импортируйте вместо tools, или прописывайте полный путь до tools.scss относительно текущей папки.

3 - В папке build лежит результат работы, полный index.html с разметкой и картинки, там же собраный style.css.


