Урок 1. Способы перейти в режим вставки
=============

**i** - вставить текст слева от текущего
  1. Переходим на точку в первой строке
  2. Нажимаем **i**
  3. Печатаем недостающий текст

```
There is some text missing last .
There is some text missing last word.
```

**I** - вставить текст в начало строки
  1. Переходим любую позицию в первой строке
  2. Нажимаем **I**
  3. Печатаем недостающий текст

```
is some text missing fisrt word.
There is some text missing fisrt word.
```

**a** - вставить текст справа от текущего символа
  1. Переходим на точку в первой строке
  2. Нажимаем **a**
  3. Печатаем недостающий текст

```
variable. = value
variable.property = value
```

**A** - вставить текст справа от текущего символа
  1. Переходим на любую позицию в первой строке
  2. Нажимаем **A**
  3. Печатаем недостающий текст

```
There is some text missing last dot
There is some text missing last dot.
```

**o** - создать новую строку под текущей
  1. Переходим на любую позицию в первой строке
  2. Нажимаем **o**
  3. Печатаем недостающий текст

```
Insert line after this.

Insert line after this.
Yahoo!
```

**O** - создать новую строку над текущей
  1. Переходим на любую позицию в первой строке
  2. Нажимаем **O**
  3. Печатаем недостающий текст

```
Insert line before this.

Yahoo!
Insert line before this
```

**C** - заменить всё до конца строки
  1. Переходим на букцу 'w'
  2. Нажимаем **C**
  3. Печатаем недостающий текст

```
This text is wrong and you should fix it!
This text is right.
```

**3s** - удалить 3 символа и перейти в режим вставки
Oбщий случай: [Кол-во повторений]s
Попытайтесь исправить текст ниже используя эту команду

```
Thiii teooooot is riffht.
This text is right.
```

**ciW** - заменить слово под курсором
  1. Переходим на любую позицию в слове
  2. Нажимаем последовательно **ciW**
  3. Печатаем верное слово

```
This lubw has a few wptfd that mrrf changing usf the change operator.
This line has a few words that need changing using the change operator.
```

**ci"** - заменить текст между кавычками
  1. Переходим на любую позицию в тексте в кавычках
  2. Нажимаем последовательно **ci"**
  3. Печатаем верный текст

```
value = "wrong"
value = "right"

value = "wrong string"
value = "right string"
```

**ci(** - заменить текст между круглыми скобками
  1. Переходим на любую позицию в тексте в скобках
  2. Нажимаем последовательно **ci(**
  3. Печатаем верный текст

```
value = function(wrong)
value = function(right)

value = function(wrong, wrong, wrong)
value = function(param1, param2)
```

**gi** - перейти к последнему месту, где производилось редактирование ) "
