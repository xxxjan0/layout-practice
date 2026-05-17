## Задание 1:
1) Написал <span class="website"><a href="#" target="_blank">САХАЛИНТЕХ</a></span> и не мог понять, а чо не работает text-align: center, а потом вспомнил, что это строчный вариант, сделал display block, потом удалил его и поменял span на div, всё четко
2) Кнопка работала только если нажать ее прям в центре (в радиусе ссылки). Вообще вложенность кликабельных элементов - признак говнокода, но в нашем случае без JS решил оставить так. Исправил проблему перестановкой button внутрь ссылки.
   Было: <div class="btn_div"><button class="btn"><a class="a_btn" target="_blank" href="#">Кнопка</a></button></div>
   Стало:  <div class="btn_div"><a class="a_btn" target="_blank" href="#"><button class="btn">Кнопка</button></a></div>
