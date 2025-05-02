# LightYearsGame

> A simple 2D space shooter built with C++ and SFML.

---

## Requirements

- C++17 compiler (GCC, Clang, MSVC)
- [SFML 2.5+](https://www.sfml-dev.org/) development libraries

---

## Build

1. Clone the repo and enter its folder:
   ```bash
   git clone https://github.com/YourUser/LightYearsGame.git
   cd LightYearsGame
g++ -std=c++17 src/*.cpp -I/path/to/SFML/include \
    -L/path/to/SFML/lib -lsfml-graphics -lsfml-window -lsfml-system \
    -o LightYearsGame
