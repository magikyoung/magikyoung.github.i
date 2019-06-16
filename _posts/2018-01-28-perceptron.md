---
title: "Data Wrangling2 Project"
date: 2018-01-28
tags: [data wrfangling, data science, messy data]
header:
  image: "/images/perceptron/percept.jpg"
excerpt: "Put the abstract here"
mathjax: "true"
---

# H1 Heading

## H2 Heading

### H3 Heading

Here's some basic text.

And here's some *italics*

Here's some **bold** text.

Add a  [link](https://github.com/dataoptimal)?

Here's a bulleted list:
* First item
+ Second item
- Third item

THere's a numbered list:
1. First
2. Second
3. Third

Python code block:
```python
    import numpy as np

    def test_function(x, y):
      z = np.sum(x,y)
      return z
```

R code block:
```r
library(tidyverse)
df <- read_csv("some_file.csv")
head(df)
```

C++ code block:
```c++
    #include <iostream>
    using namespace std;
    int main()
    {
      cout<<"abc"<<endl;
      return 0;
    }
```

Here's some inline code `x+y`.

Here's an image:
<img src="{{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg" alt="linearly separable data">

Here's another image using Kramdown:
![alt]({{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg)

Here's some math:

$$z=x+y$$
$$x_{h} = 2 ^ {5} + \frac{1}{x + 3}$$

You can also put it inline $$z=x+y$$
