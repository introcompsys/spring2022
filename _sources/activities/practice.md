---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.10.3
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# More Practice

```{note}
these are listed byt the date they were *posted*
```

```{code-cell} ipython3
:tags: ["hide-input"]
import os
from IPython.display import Markdown, display

prep_file_list = sorted(os.listdir('../_practice/'))


```

```{code-cell} ipython3
:tags: ["hide-input"]

for prep_file in prep_file_list:
    date_str = prep_file[:-3]
    date_link = '[' + date_str + '](../notes/' + date_str + ')'
    display(Markdown(date_link))
    display(Markdown('../_practice/' + prep_file))
```
