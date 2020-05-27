---
title: "How does Affinity Propagation work?"
date: 2018-01-28
tags: [data science, clustering, unsupervised data]
header:
  image: "/images/perceptron/percept.jpg"
excerpt: "Data Science,Machine Learning, Clustering, Affinity Propagation"
mathjax: "true"
---

# How does Affinity Propagation work?

## The Math and Intuition behind it.

### H3 Heading

Affinity propagation (AP) is a centroid based clustering algorithm similar to k Means or K medoids, which does not require the estimation of the number of clusters before running the algorithm. Affinity propagation finds “exemplars” i.e. members of the input set that are representative of clusters.

And here's some *italics*

**The math behind the algorithm**

AP takes as input the similarities between the data points and identifies exemplars based on certain criteria. Messages are exchanged between the data points until a high-quality set of exemplars are obtained.
let us try to understand this algorithm with the help of an example. We have information about the preferences of five participants.

What about a [link](https://github.com/dataoptimal)?

Here's a bulleted list:
* First item
+ Second item
- Third item

Here's a numbered list:
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

Here's some inline code `x+y`.

Here's an image:
<img src="{{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg" alt="linearly separable data">

Here's another image using Kramdown:
![alt]({{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg)

Here's some math:

$$z=x+y$$

You can also put it inline $$z=x+y$$

