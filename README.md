# MyArchiver - Архиватор на основе алгоритма Хаффмана
## Описание
Архиватор на основе алгоритма Хаффмана может сжимать данные, а именно текстовые файлы. Также он может обратно разжимать текстовые файлы. Архиватор можно вызвать из командной строки, и в результате сжатия и расжатия результат будет записываться в изначально определённые файлы.
## Сборка программы в командной строке
Компилятор gcc должен быть установлен в командной строке. Открываем её, и пишем:
```
cd project
```
Вместо слова project нужно написать путь к папке с файлами проекта

Затем в компиляторе нужно написать следующее:
```
gcc -c *.c
gcc -o program *.o
program
```
Вместо слова program нужно написать имя программы (можно придумать любое, и далее его использовать)
## Работа проекта
В этой программе можно сделать два действия: сжать и разжать файл
### Сжатие файла
В командной строке нужно написать следу
