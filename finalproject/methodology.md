## Data Source

- I downloaded my data from Corgis CSV data sets https://corgis-edu.github.io/corgis/csv/
- Used the coffee data set

## Data Preparation

- I tried to turn the CSV into a list and I quickly realized that it would be better to just leave it as it was.
- Flavor, aroma, acidity, and total score are the data points I used and I wanted to find a good high number that has about the same amount of rows for all of those data sets.
- Created a smaller version of my data to only things I need such as flavor, aroma, acidity, and total score. I as well removed rows that had missing values.
- Created a subset of my data that shows coffee with a total score of 85 or higher. There was 81 rows left after this.
- Compared average scores then did a correlation to compare aroma, flavor, and acidity with total score. Close score to 1 means a strong relation ship, close to 0 means weak or no relationship, and -1 means a negative relationship.
- Then made 4 visulizations, Flavor vs Total Score, Aroma vs Total Score, Acidity vs Total Score, then top 10 countries by their average coffee score

## Assumptions

- I believe most assumptions I made were probably consistent with the logic that the people who collected the data had.
- The higher the flavor, aroma, and acidity scores the higher the total score would be
- I am also assuming that each row is a different kind of coffee sample

## Limitations

- Doesn't represent every coffee in the world
- The correlation between flavor, aroma, acidity, and total score doesn't mean or prove that it directly causes the other
- Some countries have more coffee samples than others