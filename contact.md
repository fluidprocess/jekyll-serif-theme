---
title: Контакты
layout: contact
bodyClass: page-contact
---

## ООО "Завод ДНМ"
Наше производство находится по адресу:
452607, Российская Федерация, Республика Башкортостан, город Октябрьский, улица Фрунзе, 6.

<!DOCTYPE html>
<html>
    <head>
        <title>API карт 2ГИС</title>
        <script src="https://maps.api.2gis.ru/2.0/loader.js?pkg=full"></script>
        <script type="text/javascript">
            var map;

            DG.then(function () {
                map = DG.map('map', {
                    center: [54.98, 82.89],
                    zoom: 13
                });

                DG.marker([54.98, 82.89]).addTo(map).bindPopup('Вы кликнули по мне!');
            });
        </script>
    </head>
    <body>
        <div id="map" style="width:500px; height:400px"></div>
    </body>
</html>

| Дни      | Время работы производства  |
| --------- | --------------- |
| Понедельник - пятница | 8.30 - 17.00 |
| Суббота  | Выходной  |
| Воскресенье  | Выходной |
