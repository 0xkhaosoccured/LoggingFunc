# LoggingFunc

The library heading I wrote serves for convenient and beautiful logging of necessary information in your projects. Supports simple multithreading.


## TODO

| Task | Status                        |
|--------|--------------------------------|
| Multithreading    |     ✅         |
| Logs into files   | ✅ |


# EXAMPLES

1. **ERROR Logs**

```cpp #include "include/logging.hpp"

int main() 
{
  int x = 1;
  if (x < 10) {
    logError("Something bad occured");
  }
  std::cin.get();
}

```

2. **SUCCESS Logs**

```cpp #include "include/logging.hpp"
int main() 
{
  int x = 1;
  if (x < 10) {
    logError("Something bad occured");
  }
  std::cin.get();
}

```
