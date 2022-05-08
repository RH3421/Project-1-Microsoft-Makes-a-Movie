# Project 1: Microsoft Makes a Movie
![alt text](https://github.com/Noptov/DS-Project-1/blob/main/images/Microsoft%20logo.png)
#### Authors: [Richard Hinds](https://github.com/RH3421) | [Will Norton](https://github.com/Noptov)

## Overview:
In this analysis we explored how [Microsoft](https://www.microsoft.com/en-us/) can best produce their first movie in their newly created movie studio following their acquisition of [Activision Blizzard](https://www.activisionblizzard.com/content/atvi/activisionblizzard/ab-touchui/ab/web/en/home.html). Microsoft should use our recommendations to optimize movie production.

## Business Understanding
![alt text](https://github.com/Noptov/DS-Project-1/blob/main/images/ATVI.jpeg)
Microsoft is a multinational technology company that recently annouced a massive [$69 billion acquisition](https://www.cnbc.com/2022/01/18/microsoft-to-buy-activision.html) of Activision Blizzard. This acquisition brings a massive library of highly engaging intellectual property (IP) that is prime for movie production.

## Data Understanding, Preparation, and Analysis
To perform this analysis we sourced data from the [IMDB](https://www.imdb.com/) and the [Numbers](https://www.the-numbers.com/movie/budgets) databases. We included films over a 10-year period from 2012 to 2021. 

## Methods
Descriptive analyses were performed, optimizing for net earnings (worldwide gross - production budget) in examination of movie genre, production budget, and movie talent.

## Results
The adventure genre is most correlated with net earnings.
![alt text](https://github.com/Noptov/DS-Project-1/blob/main/images/gen_netearn_vert.png)
Movie productions with a budget over $150 million correlated most closely with net earnings.
Top 5 talent, on average, brings in more than $1 billion in net earnings per film.

## Conclusions
1) Microsoft should leverage Activision Blizzard IP to make an adventure movie.
2) The budget should be over $150 million as big budgets mean big earnings.
3) Microsoft should cast Ty Simpkins given his ability to drive net earnings as top talent.

## Next Steps
Incorporate movie rating and merchandise sales into earnings analysis.

## For More Information
View the full analysis via the [Jupyter Notebook](https://github.com/Noptov/DS-Project-1/blob/main/MainDF.ipynb).

## Repository Structure <br>
. <br>
├── data <br>
├── images <br>
├── .gitignore <br>
├── MainDF.ipynb <br>
├── Presentation.pdf <br>
└── README.md <br>
