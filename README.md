# GTest Example for Ubuntu
- `install_setup_gtest.sh` - install, compile and setup gtest (run once on computer)
- `sample1.h` and `sample1.cpp` source files which needed to test (`Factorial(int)` and `IsPrime(int)` functions)
- `tests/` - tests for source files.

### Run tests
```bash
cd tests/ 
cmake CMakeLists.txt # pic. 1
make # pic. 2
./runTests # pic. 3
```
Pic. 1

![image](https://github.com/SUPERustam/gtest_example/assets/64551202/76fdcbf8-4cfa-430d-b346-78734a48cb7a)

Pic. 2

![image](https://github.com/SUPERustam/gtest_example/assets/64551202/64c44c19-b65e-4296-8f7a-28e79cec6e45)

Pic. 3

![image](https://github.com/SUPERustam/gtest_example/assets/64551202/8ba7888b-1f8a-41ce-85ab-6b7332e2ce62)

## Links:
1. Documentation of GTest: https://google.github.io/googletest/
2. Introduction to GTest: https://google.github.io/googletest/primer.html
3. GTest FAQ: https://google.github.io/googletest/faq.html
4. More samples from GTest repository: https://github.com/google/googletest/tree/main/googletest/samples
