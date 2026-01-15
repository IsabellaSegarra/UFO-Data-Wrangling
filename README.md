# Interpreting `{ggplot2}` code with UFO Data Visualizations 

This repository contains the `HW1.qmd` file where I interpret code from  Dan Oehm’s UFO Sightings visualization. This assignment was completed as part of [EDS-240 Data Visualization and Communication](https://eds-240-data-viz.github.io/) class as part of the Masters of Environmental Data Science program. 

## Contributor
**Isabella Segarra** Masters student at the Bren School of Environmental Science and Management MEDS program.

## Repository Structure 
This repository contains the following structure: 
```
.
├── eds240-hw1-ufo.Rproj
├── fonts
│   ├── Font Awesome 6 Brands-Regular-400.otf
│   ├── Font Awesome 6 Free-Regular-400.otf
│   └── Font Awesome 6 Free-Solid-900.otf
├── HW #1.pdf
├── HW1_files
│   └── libs
├── HW1.html
├── HW1.qmd
├── images
│   └── ufo.png
├── outputs
│   └── ufo_sightings_infographic.png
└── README.md
```
## Data Access
Data was sourced externally with the following code:
```
ufo_sightings <- read_csv('https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2023/2023-06-20/ufo_sightings.csv')
places <- read_csv('https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2023/2023-06-20/places.csv')

```

## Acknowledgments 
I would like to acknowledge the EDS-240 Data Visualization and Communications course's instructor and co-instructor Sam Shanny-Csik and Annie Adams. I would also like to acknowledge the work of Dan Oehm. 
