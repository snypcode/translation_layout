### Перевод раскладки с ENG -> RUS и наоборот.

Пример, ввели текст на русском в английской раскладке и переписывать неохота:

_Ghbdtn? rfr ltkf& xnj yjdjuj& -> Привет, как дела? что нового?_

> В работе с файлом результат работы сохраняется в текущую папку скрипта.

### Ключи:
```--rus```    текст русской раскладки на английскую

```--eng```    текст английской раскладки на русскую

```--path```   путь к файлу формата *.txt

### Пример:
```bash
./start.py --eng "Ntrcn"
./start.py --rus "Еуче"
./start.py "GHbdtn"
./start.py --rus --path /home/user/file.txt
./start.py --eng --path /home/user/file.txt
```
