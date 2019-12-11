# Сеть [(back)](./readme.md)

* Что такое сетевой протокол?
* Модель OSI
  * Что такое модель OSI?
  * Для чего она была разработана?
  * На какие уровни она делится? Что включает в себя зона ответственности каждого из уровней?
  * Какие PDU используются на каждом уровне модели?
  * Как уровни взаимодействуют друг с другом? Знает ли уровень о наличии других уровней (может ли обращаться напрямую)?
* Транспортные протоколы
  * Что такое однонаправленное сообщение (unicast)?
  * Что такое широковещательная передача (broadcast)?
  * Что такое TCP? Как он работает?
  * Что такое мультиплексирование?
  * Что такое UDP? Как он работает?
  * В чем разница между TCP и UDP?
  * В каком случае предпочтительнее использовать TCP, а в каком UDP?
* HTTP
  * Что такое HTTP?
  * Из каких частей состоит HTTP-сообщение?
  * Какие основные методы протокола существуют? Что делает каждый из них?
  * Для чего нужны коды состояния HTTP-ответа? На какие подуровни делятся коды состояния?
  * Что такое клиент-серверный протокол?
  * Что такое юзер-агент?
  * Что такое прокси?
  * В чем разница между HTTP 1.1, HTTP 2 и HTTPS?
  * Можно ли управлять состоянием в HTTP?
  * Что такое сессии?
* Сокеты
  * Что такое сокет в контексте сетей?
  * Почему сокет считается абстрактным объектом?
  * Что такое unix domain socket?
* Общение с сервером
  * Что такое AJAX и COMET?
  * Что такое XMLHttpRequest?
    * С какими данными может работать?
    * С какими протоколами используется?
    * Можно ли отправить запрос синхронно?
    * Можно ли ограничить время продолжительности запроса?
    * Как возобновить прерванный запрос?
  * Что такое polling и long polling?
  * Что такое WebSocket?
    * Для чего используется данная технология?
    * В чем отличия от unix domain socket?
    * По какому протоколу отправляются данные? Как он работает?
    * Что такое websocket frame? Как они работают и какие типы существуют?
    * В каких случаях соединение по сокету будет закрыто?
    * Как возобновить разорванное соединение? Как восстановить загрузку файла с того же места, на котором прервалось соединение?
    * Что такое PING/PONG?
    * Какие есть альтернативы, если данная технология не поддерживается браузером?
  * Что такое Server-Side Events?
    * В чем отличия от WebSockets?
    * По какому протоколу передаются данные?
    * В каком формате сервер отправляет сообщения?
    * Как возобновляется соединение с сервером, если оно было потеряно? Как возобновить соединение с последнего полученного сообщения?
    * Какие есть события у Server-Side Events? Можно ли создавать кастомные события?
  * Как работает метод `fetch` в JavaScript?
    * Как задавать опции и заголовки объекту запроса?
    * В чем отличия от XMLHttpRequest?
    * Как отправлять/получать cookie с помощью `fetch`?
    * Какой статус он выставляет при 400-ых и 500-ых ошибках?
    * Для чего используется свойство `ok` в ответе?
  * Для чего нужен протокол JSONP?
    * Как обрабатывать ответ от сервера?
    * Как отлавливать и обрабатывать ошибки?
    * Как реализовать COMET функциональность с помощью JSONP?


### Ресурсы
* [Talk, Функции уровней модели OSI](https://www.youtube.com/watch?v=7cIC-o2wODs)
* [AJAX и COMET, learn js](https://learn.javascript.ru/ajax)
* [Using fetch, MDN](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)
* [HTTP, MDN](https://developer.mozilla.org/ru/docs/Web/HTTP/Overview)
* [Что такое HTTP](https://7bloggers.ru/chto-takoe-http/)