### TODO

- [ ] Pre-preview checks
    - [ ] Confirm there are no instances of `eval=FALSE` in the qmds
    - [ ] Confirm there are no instances of `FIXME` or `TODO` in the qmds or ipynb
- [ ] Request updated info on custom pages


### Setup

- Assumes quarto (1.8.27)
- Assumes uv (0.10.2)
- Assumes R
    - kableExtra
    - tidyverse    

```zsh
# preview to observe changes
cd maize-meeting
quarto preview ../maize-meeting
```