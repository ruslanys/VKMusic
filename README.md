## VKAudioSaver

### Преамбула

У меня была консольная утилита для выкачивания музыки из ВК, которую я когда-то ~~наговнокодил~~ 
быстренько собрал на коленке. Создавал её как раз тогда, когда начался движ с жесткой вычисткой аудио 
композиций по требованиям правообладателей из ВК, дабы спасти библиотеку. 

Выкачал я тогда музыку и ушел в стримиговый сервис. Время шло, ВК отключил API по работе с аудио, 
добавил защиту "от дурака" на веб-сайте, стал вводить ограничения по времени прослушивания (последнее вообще зашквар). 
Стало интересно разобраться в том, как обойти эту "защиту" и реанимировать приложение, так появился апдейт, которым я 
поделился с другом. Как оказалось, консольная утилита вообще непригодна для использования не программистами.

Так появилась версия 2.0 с полноценным UI, автоматической сихнронизацией, кросс-платформенностью, 
~~блек-джеком и шлюхами~~.

Хотелось, чтобы UI выглядел нативно на каждой системе, поэтому был выбран Swing, а не JavaFX.

### Запуск

Либо сделать файл исполняемым:

```$ chmod +x vkaudiosaver-*.jar```

И потом запускать как:

```$ ./vkaudiosaver-*.jar```

Либо всегда:

```$ java -jar vkaudiosaver-*.jar```