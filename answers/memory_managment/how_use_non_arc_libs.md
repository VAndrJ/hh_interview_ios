## Что делать, если проект написан с использованием ARC, а нужно использовать классы сторонней библиотеки написанной без ARC?

[**Вернутся к списку вопросов**](https://github.com/Torlopov-Andrey/hh_interview_ios/blob/master/readme.md)

В настройках для модулей использующих ручное управление памятью надо добавить флаг: `-fno-objc-arc`
