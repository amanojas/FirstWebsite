---
title: Example Page 1
linktitle: Tips 1-2
date: 
output: 
 html_document:
  css: style.css 
  toc: true
  toc_float: true
  number_sections: yes
draft: false
menu:
  example:
    parent: Example Topic
    weight: 1

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 1
---
```{r include = FALSE}
install.packages("learnr")
library(learnr)
```
This chapter includes basic introduction of economics.

# Tip 1

```{r letter-a, echo=FALSE}
question("What number is the letter A in the English alphabet?",
  answer("8"),
  answer("14"),
  answer("1", correct = TRUE),
  answer("23")
)
```

# Tip 2

