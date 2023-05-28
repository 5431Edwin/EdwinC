Microsoft's Movie Analysis
Edwin Cheruiyot
### Overview
The movie industry is a dynamic and competitive sector encompassing the production, distribution, and exhibition of films. It is driven by creativity, diversity, and the desire to captivate audiences with compelling stories. From concept development to distribution strategies and audience preferences, the industry constantly evolves to meet the changing demands of viewers. With advancements in technology and the rise of digital platforms, movies are now more accessible than ever, shaping the global cinematic landscape. 

Additionally, the movie studios play a vital role in the entertainment industry by producing and distributing films to audiences both locally and  worldwide. Movies are the driving force behind the creation, financing, marketing,distribution of movies and shaping the global cinematic landscape. Understanding the workings and dynamics of movie studios is essential for analyzing the industry, identifying trends, and predicting future developments. 

Movie studio are committed to fostering creativity, nurturing talent, and embracing diversity in all aspects in the entertaining industry and supporting emerging filmmakers, telling diverse stories that reflect the richness of our world, and contributing positively to the art of cinema.

### Problem Statement
Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### Main Objective 
The xplore the types of films that have been performing exceptionaly well in the box office

### Specific Objectives
* The primary objective of this project is to extract valuable insights that can effectively inform the decision-making process for Microsoft's newly established movie studio.
* By analyzing relevant data and conducting thorough research, we aim to equip the management team with the necessary information and recommendations that will guide their decision-making process and help drive the company's success.

### Notebook Structure
* Data Collection
* Read and check the data
* Cleaning the data
* Exploratory Data Analysis
* Conclusions and Recommendations

### Data Understanding
The data we used was collected from various locations, the different files have different formats and Some are compressed CSV (comma-separated values) that can be opened using spreadsheet software or Pandas DataFrame using pd.read_csv, while the data from IMDB is located in a SQLite database.

Analyzing dataset will determine what contributes to the "success" of a movie. In this analysis, I will define analysis in financial terms basing the success of a movie on the amount of money it earns in comparison to the budget.

### Data Wrangling
In thIS phase, the focus was on selecting the relevant features and eliminating unnecessary information from the collected datasets. This involved dropping the irrelevant features and rows from each dataset to streamline the data. Once the unnecessary data was removed, the remaining datasets were merged or joined together to create a consolidated dataset for further analysis and exploration. This step ensured that only the essential data was retained, reducing complexity and facilitating efficient analysis.

### Data Analysis
In our analysis, we define a successful movie based on its worldwide gross, which combines the total domestic and foreign income. Specifically, a movie is considered successful if its worldwide gross is at least twice the budget. This criterion ensures that the movie generates significant revenue compared to its production costs.

From the top 20 most successful genres in terms of average income ratio are Action, Drama, and Romance. These genres consistently generated the highest average income compared to other genres.
<img src =   "Images\output1.png" /> 
Successful movies 
<img src = "Images\output2.png" />
Distribution of successful movie genres
<img src = "Images\output4.png" />
Average income Ratio per month
<img src = "Images\output 5.png" />
Correlation between Budget and income Ratio
<img src = "Images\output6.png" />

### Conclution / Recommendations 
In our analysis, we define a successful movie based on its worldwide gross, which combines the total domestic and foreign income. Specifically, a movie is considered successful if its worldwide gross is at least twice the budget. This criteria ensures that the movie generates significant revenue compared to its production costs.
Based on the findings, I would highly recommend considering the following points:

* Film Genres: Based on the analysis, the most common and successful genres in movies are DRAMA, THRILLER, and COMEDY. Among these, DRAMA stands out as it has a high income ratio and is relatively cheaper to produce. Additionally, genres like ACTION, ADVENTURE, HORROR, and MYSTERY have also performed well and are worth considering. The genre combination of ACTION, DRAMA, and ROMANCE has shown to have the highest income ratio.

* Release Months: The success of a movie is greatly influenced by the release month. I recommend focusing on three months that have proven to be the best in terms of income generation: JULY, JANUARY, and NOVEMBER. Among these, JULY has shown the highest income ratio.

* Budget Allocation: To optimize the budget allocation for a successful movie, it is recommended to allocate within 24 million dollars. This range has been observed to be effective in achieving success in terms of income generated.

By considering these recommendations, you can increase the chances of creating successful movies with higher income ratios.