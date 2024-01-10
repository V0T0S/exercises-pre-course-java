Изучать язык программирования по традиции начинают с программы "Hello, World!", которая выводит этот текст на экран.

<pre class='hexlet-basics-output'>
  Hello, World!
</pre>

На языке Java эта программа будет выглядеть так:

```java
class App {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

https://replit.com/@hexlet/java-basics-hello-world

Текст *Hello, World!* появится на экране благодаря команде `System.out.println()`, где `println()` — это сокращение от английского *print line*. Она выводит на экран значение, указанное в скобках `("Hello, World!")` — в данном случае строку. Сама строка обрамляется двойными кавычками `""`. Если этого не сделать, то компилятор укажет на синтаксическую ошибку:

```bash
# Например, вот так
App.java:5: error: unclosed character literal
System.out.println('Hello, World!');
```

Сама команда находится внутри нескольких конструкций, которые нужны для работы даже простейших программ на Java.
В данном случае это класс `App` и метод `main()`.

Сейчас мы не будем на них останавливаться, так как для их понимания нужно уметь немного программировать. Поэтому во многих заданиях они даются «как есть», то есть вам не придется их задавать самостоятельно. Когда придет время, мы их разберем.

## JShell

Двигаясь по урокам, вы постоянно будете встречаться с примерами кода и описаниями его работы. Чтобы их лучше понимать и уметь пользоваться языком, нужно постоянно практиковаться и экспериментировать.

Поэтому по возможности запускайте все примеры из теории и проводите эксперименты с непонятными моментами.

С Java проще всего начать на сайте [onecompiler](https://onecompiler.com/jshell), который позволяет запускать построчно код прямо в браузере. Попробуйте перейти туда прямо сейчас и набрать такой код:

```
System.out.println(85 * 3);
```