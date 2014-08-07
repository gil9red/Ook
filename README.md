Interpreter Ook!.
===========

####EN:
Interpreter language Ook!.

| Character         | Meaning                                                                                     |
|-------------------|---------------------------------------------------------------------------------------------|
|     Ook. Ook.     | increment the data pointer (to point to the next cell to the right).                        |
|     Ook! Ook!     | decrement the data pointer (to point to the next cell to the left).                         |
|     Ook. Ook?     | increment (increase by one) the byte at the data pointer.                                   |
|     Ook? Ook.     | decrement (decrease by one) the byte at the data pointer.                                   |
|     Ook! Ook.     | output the byte at the data pointer.                                                        |
|     Ook. Ook!     | accept one byte of input, storing its value in the byte at the data pointer.                |
|     Ook! Ook?     | if the byte at the data pointer is zero, then instead of moving the instruction pointer forward to the next command, jump it forward to the command after the matching ] command.      |
|     Ook? Ook!     | if the byte at the data pointer is nonzero, then instead of moving the instruction pointer forward to the,next command, jump it back to the command after the matching [ command.      |


####RU:
Интерпретатор языка Ook!.

| Команда Ook!          |  Описание команды                                                                       |
|-----------------------|-----------------------------------------------------------------------------------------|
|         Ook. Ook.     | перейти к следующей ячейке                                                              |
|         Ook! Ook!     | перейти к предыдущей ячейке                                                             |
|         Ook. Ook?     | увеличить значение в текущей ячейке на 1                                                |
|         Ook? Ook.     | уменьшить значение в текущей ячейке на 1                                                |
|         Ook! Ook.     | напечатать значение из текущей ячейки                                                   |
|         Ook. Ook!     | ввести извне значение и сохранить в текущей ячейке                                      |
|         Ook! Ook?     | если значение текущей ячейки ноль, перейти вперёд по тексту программы на ячейку, следующую за соответствующей ] (с учётом вложенности)     |
|         Ook? Ook!     | если значение текущей ячейки не нуль, перейти назад по тексту программы на символ,[ (с учётом вложенности)                                       |