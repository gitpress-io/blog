---
title: R Lang and UI polish
date: 2020-04-06
---

R Lang and UI polish

R language syntax support has been added to GitPress.io.

and we also polish the UI.

Hope you like it.

## R

```r
recurse_fibonacci <- function(n) {
  if(n <= 1) {
    return(n)
  } else {
    return(recurse_fibonacci(n-1) + recurse_fibonacci(n-2))
  }
}

nterms = as.integer(readline(prompt="How many terms? "))
# check if the number of terms is valid
if(nterms <= 0) {
  print("Plese enter a positive integer")
} else {
  print("Fibonacci sequence:")
  for(i in 0:(nterms-1)) {
    print(recurse_fibonacci(i))
  }
}
```


