# Programming Environment

| Language | Compiler version | Compile commands                                  |
| -------- | ---------------- | ------------------------------------------------- |
| C        | gcc11.3.0        | gcc -x c -g -O2 -std=gnu11 -static ${files} -lm   |
| C++      | g++11.3.0        | g++ -x c++ -g -O2 -std=gnu++20 -static ${files}   |
| Python3  | PyPy3 7.3.5      | pypy3 -m py_compile ${files}                      |
| Java     | Openjdk 17.0.5   | javac -encoding UTF-8 -sourcepath . -d . ${files} |
