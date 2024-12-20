---
title: More features of zola-thesis theme
date: 2023-11-17
---

## Gallery

{{ gallery() }}

<!-- ok, warning, error, info -->
{% note(type="info", display="block", markdown=true) %}
This is an info block used for sharing information related the topic
{% end %}


Lorem ipsum  dolor sit amet,  consectetur adipiscing elit. Fusce  suscipit aliquam
consequat. Nunc  auctor, massa  molestie lacinia  dapibus, quam  augue condimentum
metus, et  auctor odio  nulla eu  augue. Lorem ipsum  dolor sit  amet, consectetur
adipiscing elit. Sed nec eros  scelerisque, consequat tortor quis, euismod tortor.
Aenean sed massa  magna. Mauris interdum mauris nec magna  eleifend, vitae lacinia
ex tempor. Nam facilisis ultricies orci, ac lobortis ex feugiat in.

<!-- ok, warning, error, info -->
{% note(type="warning", display="block", markdown=true) %}
this  is the warning block
{% end %}

## Code Blocks

```c
#include <stdio.h>

int main() {
    printf("Hello, World\n");
}
```

<!-- ok, warning, error, info -->
{% note(type="error", display="block", markdown=true) %}
this is the error block
{% end %}

## Note

<!-- ok, warning, error, info -->
{% note(type="ok", display="block", markdown=true) %}
OK block
{% end %}

Lorem ipsum  dolor sit amet,  consectetur adipiscing elit. Fusce  suscipit aliquam
consequat. Nunc  auctor, massa  molestie lacinia  dapibus, quam  augue condimentum
metus, et  auctor odio  nulla eu  augue. Lorem ipsum  dolor sit  amet, consectetur
adipiscing elit. Sed nec eros  scelerisque, consequat tortor quis, euismod tortor.
Aenean sed massa  magna. Mauris interdum mauris nec magna  eleifend, vitae lacinia
ex tempor. Nam facilisis ultricies orci, ac lobortis ex feugiat in.

---


Lorem ipsum  dolor sit amet,  consectetur adipiscing elit. Fusce  suscipit aliquam
consequat. Nunc  auctor, massa  molestie lacinia  dapibus, quam  augue condimentum
metus, et  auctor odio  nulla eu  augue. Lorem ipsum  dolor sit  amet, consectetur
adipiscing elit. Sed nec eros  scelerisque, consequat tortor quis, euismod tortor.
Aenean sed massa  magna. Mauris interdum mauris nec magna  eleifend, vitae lacinia
ex tempor. Nam facilisis ultricies orci, ac lobortis ex feugiat in.

