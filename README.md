# Cryptanalysis

Проект - реализация логики Криптографии.

Цель: Реализация алгоритмов шифрования и дешифрования в виде простейшей программной логики.

Для каждого блока необходим свой README.MD

Планы:
1. Реализация шифрования с ключом. (Известно сообщение и ключ, получить шифрованное сообщение)
2. Реализация дешифрования задачи из пункта 1. (Известно два или три шифрованных сообщения, получить искомые сообщения и ключ.)
3. Рассмотрение алгоритмов рандомизации значений используемых в криптографии.
4. Разработка вычислителя простых чисел и их программный анализ. 
(Анализ чисел будет происходит в рамках ограниченной числовой последовательности.)
Реализовано нахождение простых чисел.
5. Реализация более сложных алгоритмов... (Неизвестно)

Результаты:
1. Реализовано (KeyCrDcr) Шифрование с ключом.
2. Реализован поиск простых чисел (Неоптимальный). (Произведен сбор простых чисел)
3. Реализовано Шифрование, Расшифрование и взлом шифра Цезаря.

Описание модулей:

Пример работы Дешифрования шифра Цезаря. Без частотного анализа.

```
Шифр Цезаря (Расшифрование)
-> Введите шифротекст: ZWDDGEQXJAWFV
Ключ: A Сообщение: ZWDDGEQXJAWFV
Ключ: B Сообщение: YVCCFDPWIZVEU
Ключ: C Сообщение: XUBBECOVHYUDT
Ключ: D Сообщение: WTAADBNUGXTCS
Ключ: E Сообщение: VSZZCAMTFWSBR
Ключ: F Сообщение: URYYBZLSEVRAQ
Ключ: G Сообщение: TQXXAYKRDUQZP
Ключ: H Сообщение: SPWWZXJQCTPYO
Ключ: I Сообщение: ROVVYWIPBSOXN
Ключ: J Сообщение: QNUUXVHOARNWM
Ключ: K Сообщение: PMTTWUGNZQMVL
Ключ: L Сообщение: OLSSVTFMYPLUK
Ключ: M Сообщение: NKRRUSELXOKTJ
Ключ: N Сообщение: MJQQTRDKWNJSI
Ключ: O Сообщение: LIPPSQCJVMIRH
Ключ: P Сообщение: KHOORPBIULHQG
Ключ: Q Сообщение: JGNNQOAHTKGPF
Ключ: R Сообщение: IFMMPNZGSJFOE
Ключ: S Сообщение: HELLOMYFRIEND
Ключ: T Сообщение: GDKKNLXEQHDMC
Ключ: U Сообщение: FCJJMKWDPGCLB
Ключ: V Сообщение: EBIILJVCOFBKA
Ключ: W Сообщение: DAHHKIUBNEAJZ
Ключ: X Сообщение: CZGGJHTAMDZIY
Ключ: Y Сообщение: BYFFIGSZLCYHX
Ключ: Z Сообщение: AXEEHFRYKBXGW
```
.............

# Заметка (Простые числа): 
407343-е простое число это 5913913.

Перед ним число близнец это 5913911 

Забавно, близнецы встречаются и на таком промежутке!

# Заметка (Частоты): 
Таблица частот для Английского алфавита:

| Буква | Частота % |
|:-----:|:---------:|
| E     | 12,7 
| T     | 9,06 
| A     | 8,17 
| O     | 7,51 
| I     | 6,97 
| N     | 6,75 
| S     | 6,33 
| H     | 6,09 
| R     | 5,99 
| D     | 4,25 
| L     | 4,03 
| C     | 2,78 
| U     | 2,76	 
| M     | 2,41 
| W     | 2,36 
| F     | 2,23 
| G     | 2,02 
| Y     | 1,97 
| P     | 1,93 
| B     | 1,49 
| V     | 0,98 
| K     | 0,77 
| X     | 0,15 
| J     | 0,15 
| Q     | 0,10 
| Z     | 0,05 