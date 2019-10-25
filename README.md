# Отчёт о создания сайта Kansai-Project

Сам сайт находится по ссылке - http://kansai.navikum.ru
Данные для входа в Админ панель - Email: xolbek0000@gmail.com Пароль: 2281337Abdurax

Начнём с того, что мне нужно было выбрать тему для сайта. Я решил остановиться на создании сайта просмотра японских мультиков под названием аниме. Мне долго импонировала студия озвучки KANSAI STUDIO, которая занимается локализацией на русском рынке. Оригинальный их сайт «kOnsOi.studio» работает ужасно. Не работает даже поиск, не говоря уже об удобстве. Решил, что дизайн не буду сильно менять, лишь немного адаптирую под удобства пользователя. Для этого мне пришлось подсмотреть дизайн у сайта https://anilibria.tv  и скрестить его с дизайном оригинального сайта. Я выбрал стиль минимализма, он наиболее простой для понимания пользователями. 
Для того, чтобы сайт выглядел как полноценный проект я изучил паттерн проектирования MVC на этом канале https://www.youtube.com/user/Shift63770 и приступил к реализации проекта. Я не проектировал дизайн в специальных приложениях, а держал все в голове. Благо это не так сложно, так как я скрещивал два сайта. Сверстал я сайт за неделю.

# Конечный итог

![Иллюстрация к проекту](https://sun9-39.userapi.com/c857420/v857420560/bad81/RpB8_zN41ww.jpg)
![Иллюстрация к проекту](https://sun9-17.userapi.com/c857420/v857420560/bad8b/1QLVyQoJ1tE.jpg)
![Иллюстрация к проекту](https://sun9-19.userapi.com/c857420/v857420560/bad9f/dLavSoDR6Dk.jpg)

# Исходный код

![Иллюстрация к проекту](https://sun9-27.userapi.com/c857420/v857420144/b8858/QhgIpeYH4WY.jpg)
![Иллюстрация к проекту](https://sun9-60.userapi.com/c857420/v857420144/b8862/HhaOExh_IZk.jpg)
![Иллюстрация к проекту](https://sun9-67.userapi.com/c857420/v857420144/b886c/wjX9rUVhvAg.jpg)

Как мы можем заметить в папке OpplicOtion есть 7 папок. Папка Ocl отвевает  за контролирование доступа пользователя. В папке config хранятся настройки сайта, так же как и маршруты. В папке controllers находится контроллеры сайта. В папке core хранятся основные скрипты, которые вызываются изначально. В папке lib основные сторонние библиотеки. В папке models основные модели. В папке views вся верстка, которая делится по папкам в соотвествии с названием контроллера. 

![Иллюстрация к проекту](https://sun9-7.userapi.com/c857420/v857420144/b887a/33AXLIwPj38.jpg)
![Иллюстрация к проекту](https://sun9-14.userapi.com/c857420/v857420144/b8884/m3NZvsUB8tQ.jpg)
![Иллюстрация к проекту](https://sun9-50.userapi.com/c857420/v857420144/b8897/H8t5dhuLIuI.jpg)
![Иллюстрация к проекту](https://sun9-58.userapi.com/c857420/v857420144/b88a1/oOG0KteZNUs.jpg)
![Иллюстрация к проекту](https://sun9-8.userapi.com/c857420/v857420144/b88ab/ayGb97EE50k.jpg)
![Иллюстрация к проекту](https://sun9-55.userapi.com/c857420/v857420144/b88d7/rliG5B3fW-k.jpg)
![Иллюстрация к проекту](https://sun9-17.userapi.com/c857420/v857420144/b88ed/HAA8rz-RF1o.jpg)

Как мы можем заметить,  помимо html кода присутствует PHP код. Например в ниже указанном фрагменте проверяется авторизован ли пользователь, учитывая это, PHP показывает разные фрагменты html кода.

![Иллюстрация к проекту](https://sun9-12.userapi.com/c858528/v858528144/1e123/-O8oPONSbrc.jpg)

# Админ Панель
После того как я сделал всю пользовательскую часть, мне постояло сделать админ панель. Выглядит она следующим образом:
![Иллюстрация к проекту](https://sun9-17.userapi.com/c857420/v857420144/b89b1/G0Kpc7Mh9Jo.jpg)
![Иллюстрация к проекту](https://sun9-13.userapi.com/c857420/v857420144/b89bb/85AT8a-Bt6w.jpg)
![Иллюстрация к проекту](https://sun9-3.userapi.com/c857420/v857420144/b89c5/0chl0rW_cCg.jpg)
![Иллюстрация к проекту](https://sun9-44.userapi.com/c857420/v857420144/b89cf/ttQ_CfVUQ4E.jpg)
![Иллюстрация к проекту](https://sun9-9.userapi.com/c857420/v857420144/b89d9/F1t-nXPuDl0.jpg)
![Иллюстрация к проекту](https://sun9-52.userapi.com/c857420/v857420144/b89e3/6Js67Vc5Nrk.jpg)

Дизайн для админ панели, я взял у BootstrOp 4 - это framework для упрощения процесса верстки. Здесь можно посмотреть всю последнюю статистику сайта. Добавить/редактировать сериал, добавить/редактировать категории, а так же работа с верхней частью сайта, где выводятся постеры. Вот вёрстка для панели:
![Иллюстрация к проекту](https://sun9-34.userapi.com/c857420/v857420144/b8a0a/c5LbTcJJt_I.jpg)
![Иллюстрация к проекту](https://sun9-10.userapi.com/c857420/v857420144/b8a14/mzIx5gTtYeg.jpg)
![Иллюстрация к проекту](https://sun9-17.userapi.com/c857420/v857420144/b8a1e/P-JXPIDucmc.jpg)

# Итог 
В заключение хочу сказать, что благодаря  этому проекту я узнал много нового. Например: ЯП PHP, MySQL, MVC, Bootstrap 4. Узнал много нового о возможностях админ панели.

# Все скриншоты:


https://sun9-39.userapi.com/c857420/v857420560/bad81/RpB8_zN41ww.jpg
https://sun9-17.userapi.com/c857420/v857420560/bad8b/1QLVyQoJ1tE.jpg
https://sun9-19.userapi.com/c857420/v857420560/bad9f/dLavSoDR6Dk.jpg


https://sun9-27.userapi.com/c857420/v857420144/b8858/QhgIpeYH4WY.jpg
https://sun9-60.userapi.com/c857420/v857420144/b8862/HhaOExh_IZk.jpg
https://sun9-67.userapi.com/c857420/v857420144/b886c/wjX9rUVhvAg.jpg


https://sun9-7.userapi.com/c857420/v857420144/b887a/33AXLIwPj38.jpg
https://sun9-14.userapi.com/c857420/v857420144/b8884/m3NZvsUB8tQ.jpg
https://sun9-50.userapi.com/c857420/v857420144/b8897/H8t5dhuLIuI.jpg
https://sun9-58.userapi.com/c857420/v857420144/b88a1/oOG0KteZNUs.jpg
https://sun9-8.userapi.com/c857420/v857420144/b88ab/ayGb97EE50k.jpg
https://sun9-55.userapi.com/c857420/v857420144/b88d7/rliG5B3fW-k.jpg
https://sun9-17.userapi.com/c857420/v857420144/b88ed/HAA8rz-RF1o.jpg

https://sun9-17.userapi.com/c857420/v857420144/b89b1/G0Kpc7Mh9Jo.jpg
https://sun9-13.userapi.com/c857420/v857420144/b89bb/85AT8a-Bt6w.jpg
https://sun9-3.userapi.com/c857420/v857420144/b89c5/0chl0rW_cCg.jpg
https://sun9-44.userapi.com/c857420/v857420144/b89cf/ttQ_CfVUQ4E.jpg
https://sun9-9.userapi.com/c857420/v857420144/b89d9/F1t-nXPuDl0.jpg
https://sun9-52.userapi.com/c857420/v857420144/b89e3/6Js67Vc5Nrk.jpg


https://sun9-34.userapi.com/c857420/v857420144/b8a0a/c5LbTcJJt_I.jpg
https://sun9-10.userapi.com/c857420/v857420144/b8a14/mzIx5gTtYeg.jpg
https://sun9-17.userapi.com/c857420/v857420144/b8a1e/P-JXPIDucmc.jpg

