# DATA ANALYSIS EXPRESSIONS(DAX) ON BANK FULL DISTRIBUTION DATASET

## INTRODUCTION

In this data-driven exploration of the 'Bank Full Distribution' dataset, we will embark on a comprehensive journey to extract meaningful insights and enhance the dataset's analytical capabilities using advanced data analysis techniques. Our focus lies on implementing various data manipulation and calculation techniques to generate valuable metrics and classifications. The primary objectives include establishing a measure for the 'Average Age of Depositors,' introducing a new column denoting 'Age Band' to categorize depositors by age groups, and creating measures to assess the total balance specific to certain demographic criteria, such as occupation and marital status. Furthermore, we aim to quantify the number of depositors with active loans, employing the power of data analysis expressions. Through these tasks, we aim to uncover patterns, trends, and relevant information that can contribute to a more informed understanding of the dataset and support strategic decision-making processes.

## PROBLEM STATEMENT

The task at hand revolves around a comprehensive analysis of the 'Bank Full Distribution' dataset. The specific challenges to address include:

1. Develop a measure to calculate the average age of depositors.
2. Introduce a new column named 'Age Band' with the following categories:
   - 'Young' for ages below 30
   - 'Mid-aged' for ages between 30 and 50
   - 'Old' for ages above 50
3. Create a measure calculating the total balance for depositors with the following criteria:
   - Job: Technician
   - Marital: Single and Married
4. Formulate a measure to determine the number of depositors with active loans.

Successfully addressing these challenges will contribute to a richer understanding of the dataset, unveiling patterns, trends, and relevant information crucial for informed decision-making in strategic and operational contexts.

## SKILLS AND CONCEPTS TO BE DEMONSTRATED

Skills to be Demonstrated in this task include:

- DAX (Data Analysis Expressions) Mastery
- Column Creation with DAX
- Conditional Logic in DAX
- Data Visualization
- Data Interpretation

Demonstrating proficiency in these skills and concepts will not only showcase a comprehensive understanding of Power BI but also ensure the effective extraction of valuable insights from the 'Bank Full Distribution' dataset.

## ANALYSIS, DISCUSSIONS AND RESULTS

### 1. Develop A Measure To Calculate The Average Age Of Depositors:

DAX Measures are calculations that aggregate data and provide insights into the underlying data model. It allows users to perform calculations like sums, averages, counts etc based on specified conditions. Measures are like containers that give rise to a single value which can be distributed accross different categories. having known this, to develop a measure to calculate the average age of depositors, we would first and foremost click on new measure found on the power bi ribbon and create new measure, the moment you do that a measurre pops up directly beneath the power bi ribbon and also on the data pane having a calculator icon beside it signifying its a measure,edit the measure beneath the power bi ribbon by cleaning of and replacing with average age of depositors since that is what we want to calculate. After which, put in the equality sign and apply the average function and in parenthese fill in the age column along side with the table it comes with and click on enter to execute the analysis. its syntax would be:

```powerbi
SYNTAX:
MEASURE = AVERAGE(TABLE_NAME[COLUMN_NAME])

APPLYING SYNTAX:
Average age of depositors = AVERAGE('Bank full'[age])
```

The calculated result will not be found in our table because its neither a calculated column or calculated table. Therefore, to view this result, we would use the card visual in the visualization pane by selecting the card visual to appear on the canvas page, and dragging our result which would be found in the data pane as average age of depositors into the card visuals. This visualization was further worked on using the format page option in the visualization pane to give it a suitable background colour, title name and good call out value


















