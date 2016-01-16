---
title: "p-hacking"
author: "sf210"
---
```{r, echo=FALSE}
summary(cars)
```

```{r echo=FALSE}
anls <- list(food='lemonade', char='crash')
```

## Summary
This study provides a statistical analysis to evaluate the correlation between `r anls$food` and `r anls$char`.  Data from the study is gathered using a food frequency survey, and examines a logistical regression to evaluate how variation in `r anls$char` can be explained by variation in `r anls$food`.

```{r,echo=FALSE}
print(anls$food)
```
## Data

