### TODO

- [ ] Pre-preview checks
    - [ ] Confirm there are no instances of `eval=FALSE` in the qmds
    - [ ] Confirm there are no instances of `FIXME` or `TODO` in the qmds or ipynb
- [ ] Fix author index
- [ ] Check custom pages
    - [ ] index.qmd
    - [ ] program_authors_attendees.qmd
    - [ ] program_awards.qmd
    - [ ] program_general_information.qmd
    - [ ] program_poster_list.qmd
    - [ ] program_schedule.qmd
    - [x] program_keynote_speakers.qmd
        - Updated.
    - [x] program_sponsors.qmd
    - [ ] _quarto.yml
- [ ] Request updated info for custom pages
    - [ ] index.qmd
        - [ ] pdf schedule
        - [ ] pdf program
    - [ ] program_authors_attendees.qmd
    - [ ] program_awards.qmd
    - [ ] program_general_information.qmd
    - [ ] program_poster_list.qmd
    - [ ] program_schedule.qmd
    - [ ] program_keynote_speakers.qmd
    - [x] program_sponsors.qmd
        - [x] Are the sponsor the same?
            - No. Updated. 
    - [ ] _quarto.yml
        - [ ] I commented out feedback link. Is there a new link for 2026?

- [ ] Check generated pages
    - [ ] generated_keynote_list.qmd
    - [ ] generated_lightning_list.qmd
    - [ ] generated_poster_list.qmd
    - [ ] generated_talks.qmd

### Setup

- Assumes quarto (1.8.27)
- Assumes uv (0.10.2)
- Assumes R
    - kableExtra
    - tidyverse
    - readxl    

```zsh
# preview to observe changes
cd maize-meeting
quarto preview ../maize-meeting
```