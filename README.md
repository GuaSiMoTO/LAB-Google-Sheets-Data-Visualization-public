# LAB-Excel-Data-Representation

# Excel Data Visualization Lab

## Introduction

Today you have learned various techniques in data visualization using Excel, so you are ready to solve a lot of new problems. This lab will have several exercises that increase in difficulty.
You will use the provided data sets in each iteration and follow the instructions to create and customize charts. Make sure to save your work in an Excel file and export as pdf.

Ready?

## Requirements
1. Have an excel account.
2. Basic understanding of creating and formatting charts in Excel.
3. Clone this repo into your code/labs folder

## RULES
1. Ensure your charts are clear and readable.
2. Customize your charts to make them visually appealing.
3. Save your work regularly.

---

## Iteration 1: Data Preparation

1.1 For the first two columns of the table we are going to create, add validations for the text type fields, so that you cannot enter numbers. 


1.2 Compile the data into an Excel sheet with the following structure:


| Month | Store  | Sales ($) | Employees | Advertising Spend ($) | Customer Satisfaction (%) |
|-------|--------|-----------|-----------|-----------------------|---------------------------|
| Jan   | Store1 | 10000     | 10        | 2000                  | 85                        |
| Jan   | Store2 | 15000     | 12        | 2500                  | 90                        |
| 44    | Store1 | 11000     | 10        | 2100                  | 88                        |
| Feb   | Store2 | 16000     | 12        | 2600                  | 89                        |
| Mar   | Store1 | 12000     | 10        | 2200                  | 86                        |
| Mar   | 28     | 17000     | 12        | 2700                  | 92                        |
| Apr   | Store1 | 13000     | 10        | 2300                  | 87                        |
| Apr   | Store2 | 18000     | 12        | 2800                  | 93                        |
| May   | Store1 | 14000     | 10        | 2400                  | 88                        |
| May   | Store2 | 19000     | 12        | 2900                  | 94                        |
| Jun   | Store1 | 15000     | 10        | 2500                  | 89                        |
| Jun   | Store2 | 20000     | 12        | 3000                  | 95                        |
| Jul   | Store1 | 16000     | 10        | 2600                  | 90                        |
| Jul   | Store2 | 21000     | 12        | 3100                  | 96                        |
| Aug   | Store1 | 17000     | 10        | 2700                  | 91                        |
| Aug   | Store2 | 22000     | 12        | 3200                  | 97                        |
| Sep   | Store1 | 18000     | 10        | 2800                  | 92                        |
| Sep   | 23     | 23000     | 12        | 3300                  | 98                        |
| Oct   | Store1 | 19000     | 10        | 2900                  | 93                        |
| Oct   | Store2 | 24000     | 12        | 3400                  | 99                        |
| Nov   | Store1 | 20000     | 10        | 3000                  | 94                        |
| Nov   | Store2 | 25000     | 12        | 3500                  | 100                       |
| Dec   | 14     | 13000     | 10        | 2200                  | 87                        |
| Dec   | Store2 | 17000     | 12        | 2700                  | 91                        |

1.3 Observe the sequence that the table follows and change the fields that do not comply with the validations

1.4 As we have a very large table, freeze the first 22 rows for better data visualisation. 

## Iteration 2: Bar Chart

Compare the monthly sales of different stores.

1. Select the data range for Month, Store, and Sales ($).
2. Insert a column chart.
3. Customize the chart titles and add different colors for each store.

## Iteration 3: Line Chart

Analyze the trend of sales over the months for each store.

1. Apply advanced filter for the stores using sliders for better data visualisation. 
2. Select the data range for Month and Sales ($).
3. Insert a line chart.
4. Add lines for each store to the chart.
5. Customize with descriptive axis labels
6. Make the legend positioned on the right, add black borders, change the font to bold and also make the font size increase to 12


## Iteration 4: Pie Chart

Show the proportion of total annual sales contributed by each store.

1. Calculate the total annual sales for each store.
2. Select the data range for Store and Total Sales ($).
3. Insert a pie chart.
4. Customize with titles and adjust colors to simulate dark mode.

## Iteration 5: Scatter Plot

You are a data analyst for a retail chain with stores in multiple locations. Your task is to analyze the sales performance of the stores over the past year and highlight key data points using conditional formatting in Excel. This will help the management easily identify trends and anomalies.

### 5.1 Do two conditional formating for the top 10% and the Bottom  10% Sales


### 5.2 find the Above and below 10% average of Satisfaction


### 5.3 Insert a Scatter Plot

Analyze the relationship between advertising spend and sales, with bubble size representing the number of employees.

1. Select the data range for Advertising Spend ($), Sales ($), and Employees.
2. Insert a scatter plot with bubbles.
3. Create the trend line of sales

## Bonus

- Display the linear equation and the value of r
- Considering the value of r, what conclusion can you draw about the validity and significance of the trend line?

## How to Submit

To submit this LAB, we upload the file to our forked repository.

## Additional Resources

- [Excel documentation](https://support.microsoft.com/excel)
- [Conditional Formatting in Excel](https://support.microsoft.com/conditional-formatting-in-excel)
- [Excel Charts](https://support.microsoft.com/en-us/office/create-a-chart-from-start-to-finish-0baf399e-dd61-4e18-8a73-b3fd5d5680c2)

