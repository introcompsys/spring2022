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

# Prepare for the next class

```{warning}
these are listed byt the date they were *posted* (eg the content here under Feb 1, was posted Feb 1, and shoudl be done before the Feb 3 class)

*below* refers to followingin the notes
```

```{code-cell} ipython3
:tags: ["hide-input"]
import os
from IPython.display import Markdown, display

prep_file_list = sorted(os.listdir('../_prepare/'))


```

```{code-cell} ipython3
:tags: ["hide-input"]

for prep_file in prep_file_list:
    date_str = prep_file[:-3]
    date_link = '[' + date_str + '](../notes/' + date_str + ')'
    display(Markdown(date_link))
    display(Markdown('../_prepare/' + prep_file))
```
