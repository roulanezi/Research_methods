---
title: Vectors
weight: 3
---

A vector is a collection of elements, a basic data structure. Vectors are crucial in RStudio. The data types contained by a vector could be logical, integer, or  character. 
</br>

To create a vector in R you should use a very useful function, the `c()` function. The c stands for **c**ombine, because multiple elements are combined into a vector.

```{r vector, message=FALSE, warning=FALSE, paged.print=FALSE}
x <-c(1,2,3,4,5,6,7,8,9,10)
```

```{r x, message=FALSE, warning=FALSE, paged.print=FALSE}
x
```

An important property of vectors is their length 

```{r length, message=FALSE, warning=FALSE, paged.print=FALSE}
length(x)
```


Additionally, you may create a vector using the `seq()` function. The seq() function generates a sequence of numbers. For example is you want to generate a sequence of numbers from 0 to 30 incremented by 3 you write

```{r seq, message=FALSE, warning=FALSE, paged.print=FALSE}
seq(from=0, to=30, by=3)
```
