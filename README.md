### TODO

- [ ] Pre-preview checks
    - [ ] Confirm there are no instances of `eval=FALSE` in the qmds
    - [ ] Confirm there are no instances of `FIXME` or `TODO` in the qmds or ipynb
- [ ] Fix author index
- [ ] Check custom pages
    - [ ] index.qmd
        - [ ] 
    - [x] program_authors_attendees.qmd
        - [x] Updated table rendering 
    - [ ] program_awards.qmd
        - [ ] Don't have award information
    - [ ] program_general_information.qmd
        - [ ] Need pdf with schedule -> `schedule.csv`
        - [ ] Need pdf with general info. This is from 2025
    - [b] program_poster_list.qmd
        - [ ] Assumes `generated/schedule_links.csv`
        - [ ] Assumes `generated/schedule.csv`
        - [ ] test `subset_M()`
    - [b] program_schedule.qmd
        - [ ] Need pdf with schedule
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
    - [x] program_keynote_speakers.qmd
        - Updated 
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
- Assumes R (4.5.2)
    - kableExtra (1.4.0)
    - tidyverse (2.0.0)
    - readxl (1.4.5)
- Download workbook
    - update sheet name "Author index" -> "Author Index"
    - update sheet "Author index" with header columns to match "Attendee List"


```zsh
# preview to observe changes
cd maize-meeting
quarto preview ../maize-meeting
```