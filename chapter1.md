---
title: 'Chapter Title Here'
description: 'Chapter description goes here.'
free_preview: true
---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

First thing: figure out where you should be typing. Then type `5 + 7`. Don't type the period. Press enter.

`@instructions`
Find the command line. It is a ">" followed by blank nothingness.

`@hint`


`@pre_exercise_code`
```{r}
5 + 7
```

`@sample_code`
```{r}
5 + 7
```

`@solution`
```{r}
12
```

`@sct`
```{r}
# Example SCT
ex() %>% check_correct(
  check_equal(5 + 7)
)
```
