### Setup

- Assumes quarto (1.8.27)
- Assumes uv (0.10.2)
- Assumes R (4.5.2)
    - kableExtra (1.4.0)
    - tidyverse (2.0.0)
    - readxl (1.4.5)
- Download workbook
    - update sheet name "Author index" -> "Author Index"
    - update sheet "Author index" with header columns to match "Attendee List"


```zsh
# preview to observe changes
cd maizebook
quarto preview ../maizebook
```