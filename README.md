# Использование

Пока наиболее удобно так:

* git clone git@github.com:afelix/csso.git
* открыть в браузере файл csso.html
* проверять

Неудобно:

* git clone git@github.com:afelix/csso.git
* node ccli.js файл.css
* в ccli.js раскомментировать нужный формат вывода и комментировать ненужный

# Done

### Мелкое

* убирает лишние whitespace;
* убирает комментарии;
* убирает лишние ';';
* убирает неправильный @charset;
* убирает пустые блоки;
* оптимизирует цвет;
* оптимизирует числа;
* склеивает margin и padding;
* склеивает multiline строки;
* font-weight normal и bold => 400 и 700;
* не трогает expression.

### Крупное

* убирает всё, что не попадает в computed stylesheet;
* группирует selector и property в структуры с меньшей длиной в символах;
* порядок, в котором следуют оригинальные selector, сохраняется;
* позволяет комментариями управлять обработкой.

# TODO

### Мелкое

* более удобный command-line;
* документировать код.

### Крупное

* добавить возможность глобального управления обработкой;
* невалидный CSS?
* мануал.
