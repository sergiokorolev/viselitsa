# Игра Виселица
[Об игре Виселитса](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0))
## Принцип игры
Один из игроков загадывает слово. Второй игрок должен угадать загаданное слово, вводя по одной букве. 
Ошибиться можно не более семи раз.

## Требования
* Установка [Ruby](https://www.ruby-lang.org/en/).
* Гем unicode_utils. Установка гема осуществляется командой в консоли `gem install unicode_utils`

## Начало игры
1. Загадать слова в файле `data/words.txt` по одному в каждой строке.
2. Запустить игру командой `ruby viselitsa.rb`

## Условия игры
* Загаданное слово выбирается в случайном порядке из файла.
* Буквы загаданного слова помечены нижним подчеркиванием "__".
* Необходимо вводить по одной букве. Ошибки записываются в строку "Ошибки".
* Ошибиться можно не более семи раз.
* Правильные ответы (буквы) отображаются в загаданном слове.
* Игра считает одной буквой «Е» и «Ё», а также «И» и «Й».
* Регистр букв не имеет значения.

