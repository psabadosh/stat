---
title       : представление данных
description : описательная статистика
--- type:NormalExercise lang:r xp:100 skills:1 key:3f38ea43bc
## Упражнение 1


*** =instructions
Вычислите среднее
*** =hint
используйте функцию mean 
*** =pre_exercise_code
```{r}
a <- rbinom(1, 1, 0.5)

```

*** =sample_code
```{r}
a

```

*** =solution
```{r}
a

```

*** =sct
```{r}
test_error()
test_object("a",
undefined_msg = "Make sure to define 'a'!",
incorrect_msg = "Have you correctly assigned value?")
success_msg("Hourrah! Bingo! Qu")

```
