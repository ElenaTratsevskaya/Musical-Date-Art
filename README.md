# Musical-Data-Art
Visualization of a song</br>
Inspired by the lyrics of Sting's «Shape of My Heart»
All musical rights remain with the authors and rights holders.</br>

Визуализация создана во время и после Дата арт Воркшопа, проводимого Натальей Киселёвой в январе 2026 года.</br>

<div id="header" align="center">
  <img src="https://repository-images.githubusercontent.com/182914159/fccef180-67ab-11e9-8dac-17c48c79065b" title="google" width="64" height="40"/>&nbsp;
  <img src="https://i.pinimg.com/736x/1d/61/41/1d6141338deef1c59eb93c19f8a11eb0.jpg" title="google" width="80" height="40"/>&nbsp;
  <img src="https://w7.pngwing.com/pngs/619/922/png-transparent-microsoft-excel-illustration-microsoft-excel-microsoft-office-macos-excel-rectangle-logo-microsoft.png" title="excel" width="40" height="40"/>&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/25/RAWGraphs_Logo.svg/120px-RAWGraphs_Logo.svg.png" title="RAWGraphs" width="40" height="40"/>&nbsp; 
  <img src="https://user-images.githubusercontent.com/71708626/110930907-702e6d80-8308-11eb-8b03-9c4ad447bcf8.png" title="powerBI" width="40" height="40"/>&nbsp;
  <img src="https://assets.asana.biz/transform/ba9b63a3-f255-4088-b5fe-14ab4628f50b/logo-app-figma" title="figma" width="40" height="40"/>&nbsp;
   <img src="https://yt3.googleusercontent.com/ytc/AIdro_ndHAWH35Na3q5Y5FOXEFbKsyd-cVVZQgeQGJq1ru3Z1g=s900-c-k-c0x00ffffff-no-rj" title="p5js" width="40" height="40"/>&nbsp;
  </div><br>

Задача состояла в том, чтобы получить постер с Дата-Артом, созданным по выбранной песне либо мелодии.</br>
По-желанию можно было для визуализации взять песню на свой вкус, но до ЗУМа обязательно скачать mid(MIDI)-файл и mp3, чтобы использовать не заготовку спикера, а своё.</br>

Далее,</br>
1️⃣ mid-файл превращали в csv с помощью скрипта в Collab.</br>
2️⃣ Обрабатывали датасет в Google Sheets и/или в Excel. Здесь важно "завернуть данные в круг", получить значения для колонок X и Y с помощью функций cos() и sin(), что является основой визуала.</br>
3️⃣ Затем создание Дата-Арта. Я использовала Power BI, пробовала rawgraphs и Tableau. Это самый творческий этап, т.к. можно настраивать цветовую палитру, в Power BI ещё и экспериментировать с размером маркера.</br>
4️⃣ Однако самая магическая часть — превращение в p5js csv-файла в Дата-Арт с наложением mp3. Без выбора цветовой палитры.</br></br>

©️ У данного алгоритма есть автор. Более детально не расскажу.</br>
Воркшоп доступен ссылке [Креативный плакат своими руками](https://datavisualizationstudio.com/musicworkshop)<br>

Я выбрала песню, с которой у меня многое связано.</br></br>

✴️ Свои готовые варианты собрала в Figma.</br>

<img width="1920" height="1080" alt="STING Shape of my heart_1" src="https://github.com/user-attachments/assets/74578cef-cfbe-45f8-a5b3-c4d07112bf1d" /></br></br>


---

Далее отдельно визуализация в BI инструментах.</br>
Интересный момент,</br> 
один и тот же исходник Power BI и p5js превращают в круг расположенный зеркально и с поворотом в 180 градусов.</br>
Это корректируется в Figma.</br>

**Визуализация в Tableau**</br>
В этом инструменте круг располагается так, что начало/нонец песни относительно максимума по оси Y сдвинут против часовой стрелки на 90 градусов.</br>
Для визуализации используется Circle</br>
В категорийный признак взят параметр "Высота ноты (pitch)". Размер маркера задаёт duration_secs.</br>

Поcтер доступен ссылке [Tablau public](https://public.tableau.com/app/profile/elena.tratcevskaia/viz/musicdateartposter/Dashboard1)<br>

<div id="header" align="center"><img align="center" width="500" height="600" src="https://allwebs.ru/images/2026/01/31/c9ebf6a72890d2237e0327ac2b431b46.png"> </br>
</div><br>

**Визуализация в Power BI**</br>
За основу берётся Bubble chart (Пузырьковая диаграмма)</br>
В категорийный признак взят параметр "Высота ноты (pitch)"</br>
<div id="header" align="center"><img align="center" width="900" height="450" src="https://allwebs.ru/images/2026/01/30/040aac9f35dd57281be23b8e70989ff4.png"> </div><br>

**Визуализация в rawgraphs**</br>
Он-лайн редактор. На сайте визуализация не сохраняется, только возможность скачивания. Скачать можно файлы различного формата в том числе и svg для удобства дальнейшей обработки в Figma.</br>
Есть возможность настраивать цвет и размер кружка. За основу берётся Bubble chart (Пузырьковая диаграмма).</br>
В категорийный признак взят параметр "Высота ноты (pitch)"</br>
<div id="header" align="left"><img align="left" width="600" height="1200" src="https://allwebs.ru/images/2026/01/30/389f36dbb4e007b0030f7bfe6173fdc0.png"> </br>
</div><br>




