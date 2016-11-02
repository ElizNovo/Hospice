
<h2>Необходимо: </h2><br>
<br>

Наш проект будет разрабатываться на основе инструмента по автоматизации процессов - Gulp и с использованием препроцессора Sass (подробное описание то, что вошло в сборку  - <a href="http://webdesign-master.ru/blog/tools/2016-08-19-optimizedhtml.html">тут</a><br>
А так же, т к мы работаем в команде, нам обязательно понадобиться система контроля версий Git.
<br>
Перед тем как приступать к проекту и для полного понимания что мы делаем, необходимо посмотреть следующие видео (смотрим и параллельно устанавливаем все это себе на компьютер): <br>
<br>

1. Что такое Gulp - <a href="http://webdesign-master.ru/blog/tools/2016-03-09-gulp-beginners.html">идем сюда</a><br>
2. Что такое Git - <a href="https://geekbrains.ru/courses/66">идем сюда</a><br>
3. Что такое Sass - <a href="http://webdesign-master.ru/blog/tools/2016-06-04-sass.html">идем сюда</a><br>
<br>
Далее, необходимо зарегистрироваться на <a href="http//gitHub.com ">GitHub.com </a> и подписаться на всех участников этого проекта. <br>
<br>
После, скачиваем себе подготовленную мной сборку <a href="">по этой ссылке</a> 	<br>
Чтобы запустить сборку, в консоле переходим в папку где находится у вас сборка, устанавливаем все модули командой npm i, и когда все установиться  прописываем gulp(запуститься локальный сервер)<br>
Все стили пропысываем только в файлах с расширением .sass (не .css) <br>

<br>

<h2>Методология: </h2><br>
<br>

В этом проекте во избежания ошибок, путаницы и т. д. придерживаемся следующих правил: <br>
<br>
1. Так как мы используем bootsrap сетку, необходимо четко сохранять ее структуру: .container-->.row-->.col-md-..!!! Между этими звеняьми не должно быть других тегов, иначе можем поломать структуру и поведения блоков <br>
Для примера как НАДО можете посмотреть  <a href="https://landing.fxopen.com/forex-accounts/">тут</a> <br>
<br>
2. Названия классов задаем через тире "-" (например: .header-logo) <br>
<br>
3. Все верстаем через Sass(нам будет хорошая практика),используем табуляцию(TAB) для отсупов, а не пробел! <br>
<br>
4. Размер шрифта указываем в "em" (конвертатор тут - <a href="http://pxtoem.com/">px to em</a>)
5. Кодим семантически правильно! Используем современные теги и стили(HTML5 и CSS3) Например, где у нас предполагается header - используем тег header а не div с классом .header! <br>
<br>
6. Название классам даем английские с учетом чем этот класс является( Например: блок, который описывает приемущества можно обозвать advantages, и ни в коем случае priemush'estva) <br>
<br>
7. Отделяем комментариями блоки HTML и CSS для наглядности<br>
пример: <br>
<h2>html code</h2> <br>
< !-- begin header --> <br>
< header> <br>
	
< /header> <br>
< !-- end header --> <br>
<br>
<h2>css code</h2> <br>
/ *========================================= <br>
/ *=            Section last-news          = <br>
/ *========================================*/ <br>
<br>
//сюда пишем стили<br>
//кто пользуется sublime text, можно поставить плагин для создания таких комментариев(<a href="https://packagecontrol.io/packages/Comment-Snippets">ссылка на этот плагин</a>), только он не совсем корректно работает для Sass-->нужно экранировать каждую строчку коммента /* <br>
<br>
/ *=====  End of Section last-news  ======*/ <br>
<br>
<br>
Очень удобная штука для верстки - <a href="http://zencoder.ru/web-development/pixel-perfect/">PixelPerfect</a>. Это расширение для браузера, которое поможет верстать максимально приближенно к макету <br>
Пока вроде все что пришло в голову, задаем вопросы что непонятно!


