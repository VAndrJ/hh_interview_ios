## Что такое `селектор (selector)`?

[**Вернутся к списку вопросов**](https://github.com/Torlopov-Andrey/hh_interview_ios/blob/master/readme.md)

Селектор - это имя метода закодированное специальным образом, используемым objective-c для быстрого поиска. Указание компилятору на селектор происходит при помощи директивы @selector(метод)

```objective-c
First* f = [[First alloc] init];
if([f respondsToSelector:@selector(setName:)]){
  NSLog (@"Метод поддерживается");
}
```
В этом примере создается экземпляр класса `First *f` (наследник `NSObject`), после с помощью метода respondsToSelector проверяем может ли класс ответить на метод `setName`.
