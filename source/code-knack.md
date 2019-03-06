---
title: Use Code-Knack to run code in posts
date: 2019-03-06
---

GitPress uses [Code-Knack](https://github.com/lyricat/code-knack) as the living code evaluator. It looks like:

```c
#include <stdio.h>

const int MAX = 10;
int cache[MAX] = {0};

int fib(int x) {
  if (x == 1) return 1;
  if (x == 0) return 0;
  if (cache[x] == 0) {
    int ret = fib(x - 1) + fib(x - 2);
    cache[x] = ret;
  }
  return cache[x];
}

int main() {
    int i;
    printf("fibonacci series:\n");
    for (i = 0; i < MAX; ++i) {
        printf("%d ", fib(i));
    }
    return 0;
}
```

Tap "Run" button, it'll calculate a fibonacci series.

---

To support more languages, GitPress enhanced the ability of Code-Knack, to make more languages runnable in browser. All enhancements will be submitted to Code-Knack to make it better.

GitPress also have a plan to support more language runtime environments, include input, graphic output and builtin APIs. I hope the GitPress itself would be a good data source with good designed APIs in the future.



