# My-tinytetris
> [reference](https://github.com/taylorconor/tinytetris)<br>
> 因为Linux系统更方便，故基于Linux系统<br>
> 基于`reference`处链接的项目进行更改，增加代码为My-tinytetris.cpp中的113-152行

### 优化内容
- 增加上下左右键操控

### 学到的知识点
- 使用`getch()`函数获取上下左右键时，需要3次。前2次相同，分别是27和91，最后1个不同，分别为上(65)、下(66)、左(68)、右(67)

### My-tinytetris.cpp
You control it with `a` or `←` (left), `d` or `→` (right), `w` or `↑` (rotate),
`s` or `↓` (drop), and `q` (quit). It depends on `curses.h` (so you'll need to compile with
`-lcurses`, and install curses if you don't already have it) and requires C++11.

### build binary My-tinytetris.cpp
`g++ -o My-tinytetris My-tinytetris.cpp -lncurses`

### run
`./My-tinytetris`
