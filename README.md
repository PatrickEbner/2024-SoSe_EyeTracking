# **Course project:** Attentional spatial bias in two image tasks
**Authors:** Maximilian Bernhardt, Patrick Ebner, Simon Enkel, Claudius Hilser & Enno Schwenk

**Course:** *Acquisition and analysis of eye-tracking data*

**Semester:** *Summer semester 2024*

## Project Description
This experiment aims to build on previous findings by exploring the impact of spatial configurations, specifically diagonal arrangements, on the left bias in image fixation. The research question guiding this study is: "Does diagonal positioning of stimuli eliminate the left bias in viewing images?" By analyzing how different diagonal placements—combining left-right and top-bottom arrangements—affect which image is fixated on first, the experiment seeks to determine whether these configurations reinforce, negate, or counterbalance the left bias. The results will be compared to existing scientific knowledge to assess consistency and uncover potential new insights.

## Instruction for a new student
To reproduce the experiment and generate the plots, simply run the DiagonalBias.ipynb notebook. All required dependencies and imports will be installed automatically during execution. If you need to add new participants, save the corresponding TSV file in the ../data/raw directory. The rest of the process is fully automated, and the script will run smoothly as long as Python is properly configured.

## Overview of Folder Structure 

```
│projectdir          <- Project's main folder. It is initialized as a Git
│                       repository with a reasonable .gitignore file.
│
├── report           <- Report PDF
|
├── presentation     <- Final presentation slides (PDFs; optionally also .pptx etc)
|
├── _research        <- WIP scripts, code, notes, comments,
│                       to-dos and anything in a preliminary state.
│
├── plots            <- All exported plots go here.
|                   
├── scripts          <- Various scripts, e.g. analysis and plotting.
│                       The scripts use the `src` folder for their base code.
│
├── src              <- Source code for use in this project. Contains functions,
│                       structures and modules that are used throughout
│                       the project and in multiple scripts.
│
├── experiment       <- OpenSesame file to run the experiment; where applicable also stimuli, randomization
|
├── data             
|   ├── raw          <- Raw eye-tracking data
|   ├── preprocessed <- Data resulting from preprocessing
|
├── README.md        <- Top-level README
|
├── .gitignore       <- List of files that Git won't automatically add
|                       (default Python .gitignore was used)
│
└── (requirements.txt)<- List of modules and packages that are used for your project
                     
```

