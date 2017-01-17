# Е и ё в русской рифме

В&nbsp;поэтическом корпусе НКРЯ во&nbsp;всех словах, написание которых допускает _ё_, использована буква _е_. Это связано с&nbsp;тем, что&nbsp;тексты для&nbsp;корпуса были взяты из&nbsp;изданий серии «Библиотека поэта», в&nbsp;которых изначально отсутствовала буква _ё_. Кроме того, имеет место произношение [е] на&nbsp;месте [о] в&nbsp;заимствованных словах из&nbsp;церковнославянского, что&nbsp;отражает исторические особенности поэтической традиции, например, _звездной_ — _бездны_. Такое произношение уходит из&nbsp;привычной поэтической речи в&nbsp;инструментарий нарочитой архаизации в&nbsp;первой трети XIX&nbsp;века. Реальный процесс перехода к&nbsp;новому поэтическому языку происходил примерно в&nbsp;1820-х годах.
Для&nbsp;автоматического распознавания рифм было важно определиться с&nbsp;точной датой перехода от&nbsp;одного типа рифм к&nbsp;другим, так как для&nbsp;поздних рифм мы&nbsp;использовали автоматическую проверку слов, в&nbsp;которых присутствует гласный _е_ по&nbsp;словарю слов с&nbsp;_ё_ (Чумаков 2009).
Чтобы определить точный&nbsp;год смены парадигмы, мы&nbsp;выгрузили все рифмы с&nbsp;буквой _е_ в&nbsp;позиции ударения в&nbsp;период с&nbsp;1820-го по&nbsp;1840-й&nbsp;год. Всего таких рифменных пар было 49 840. Далее все такие рифменные пары мы&nbsp;разметили вручную, отмечая:

- Использована&nbsp;ли буква _е_ на&nbsp;месте современной _ё_, то есть образована&nbsp;ли рифма ударным гласным \[е\] (_изображенным_ — _блаженным_);
- Произносится&nbsp;ли в&nbsp;обоих случаях [о] на&nbsp;месте буквы _е_, то есть образована&nbsp;ли рифма ударным гласным [о] (_найдет_ — _лед_).

По&nbsp;умолчанию, мы&nbsp;считали, что&nbsp;глагольные формы на&nbsp;_-ет_, в&nbsp;которых произносится [о] (_печет_, _кладет_), не&nbsp;могли произноситься с&nbsp;гласным [е], равно как и&nbsp;местоимения _ее_, _нее_ и&nbsp;тому подобные.
По&nbsp;результатам разметки мы&nbsp;сформировали таблицу, где для&nbsp;каждого года выписали два значения — процент рифм с&nbsp;ударным гласным [е], процент рифм с&nbsp;ударным гласным [о]. По&nbsp;полученным значениям мы&nbsp;построили график.

![Image](e_yo.png)

На&nbsp;графике точки пересечения линий приходятся на&nbsp;несколько периодов, однако логично предположить, что&nbsp;истинной точкой перехода является 1828-й&nbsp;год. Остальные выбросы можно считать случайными за&nbsp;счет некоторого несбалансированного фактора (например, из-за превалирования стихотворений некого автора в&nbsp;определенном году). Случайность выбросов также доказывается сглаженными линиями на&nbsp;графике, построенными по&nbsp;усредненным значениям.
Таким образом, 1828-й&nbsp;год был выбран точкой изменения в&nbsp;работе программы. После 1828-го года происходит проверка слов с&nbsp;буквой _е_ под&nbsp;знаком ударения в&nbsp;словаре слов с&nbsp;_ё_. Для&nbsp;достижения наибольшей точности можно было&nbsp;бы использовать ручную разметку, например, с&nbsp;привлечением краудсорсинга. Однако в&nbsp;настоящем исследовании мы&nbsp;ставили цель достичь наибольшей полноты, а&nbsp;не&nbsp;точности анализа, а&nbsp;кроме того, исходные данные корпуса были переданы нам конфиденциально. По&nbsp;этим причинам мы&nbsp;отказались от&nbsp;ручной разметки и&nbsp;считали, что&nbsp;для наших задач достаточно только автоматической разметки.
