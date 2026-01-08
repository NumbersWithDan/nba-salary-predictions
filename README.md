[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/yXdXIqnw)

## Project Description
Data Set Name: NBA Player Salaries (2022-23 Season)
Data Source url: https://www.kaggle.com/datasets/jamiewelsh2/nba-player-salaries-2022-23-season



The dataset contains NBA player salaries combined with their individual season’s performance statistics for 2022-23.  This data allows analysis into how different performance metrics correlate with earnings. The metrics include per-game statistics like points, assists, rebounds, and shooting efficiency as well as advanced statistics like win shares (WS) and value over replacement player (VORP). The goal is to understand what drives salaries and whether the compensation a player receives can be predicted by their production. By exploring these statistics we can identify driving features that indicate increased earnings and assess the value of different skills.
The analysis will focus on modeling salary as a function of performance, using regression to quantify which statistics have the strongest impact on earnings. The analysis will explore salary and performance distributions, compare the performance statistics of players with high salary predictions, and identify players who are underpaid/overpaid relative to their predicted salary. 



Here is the overview of the repository structure:

```
$ pwd
/path/to/local/repos/ml-python-class

$ tree
.
├── data
│   ├── data-file-1.csv
│   ├── data-file-2.csv
│   ├── ...
│   └── data-file-X.csv
├── figures
│   ├── figure-01.png
│   ├── figure-02.png
│   ├── ...
│   └── figure-XX.png
├── scripts
├── src
│   ├── ml_python_class
│   │   ├── custom_funcs.py
│   │   ├── __init__.py
│   └── setup.py
├── LICENSE
├── README.md
└── .devcontainer
```




**README.md, LICENSE**

Top level markdown files holding general project information.  
README.md markdown files may also be given in subdirectories for
further information about aspects of the project.


