# What Is Pandas In Python?

---
Pandas is an open source Python package that is most widely used for data science/data analysis and machine learning tasks. It is built on top of another package named Numpy, which provides support for multi-dimensional arrays. As one of the most popular data wrangling packages, Pandas works well with many other data science modules inside the Python ecosystem, and is typically included in every Python distribution, from those that come with your operating system to commercial vendor distributions like ActiveState’s ActivePython. 


---

# What Can You Do With DataFrames Using Pandas?


Pandas makes it simple to do many of the time consuming, repetitive tasks associated with working with data, including:

Data cleansing
Data fill
Data normalization
Merges and joins
Data visualization
Statistical analysis
Data inspection
Loading and saving data
And much more
In fact, with Pandas, you can do everything that makes world-leading data scientists vote Pandas as the best data analysis and manipulation tool available.

---

## How to create a DataFrame in Pandas :

Creating an Empty DataFrame


* Importing Pandas to create DataFrame
import pandas as pd
  
* Creating Empty DataFrame and Storing it in variable df
```{df = pd.DataFrame()}```
  
* Printing Empty DataFrame
```{print(df)}```

---

## How to slice a DataFrame in Pandas :

Sometimes generating a simple Series doesn’t accomplish our goals. For more complex operations, Pandas provides DataFrame Slicing using “loc” and “iloc” functions. For example, let’s say Benjamin’s parents wanted to learn more about their son’s performance at the school. They want to see their son’s lectures, grades for these lectures, # of credits earned, and finally if their son will need to take a retake exam. We can simply slice the DataFrame created with the grades.csv file, and extract the necessary information we need. For example:
```
{
Grades = 

Report_Card.loc[(Report_Card["Name"] == "Benjamin Duran"),  
  ["Lectures","Grades","Credits","Retake"]]
Sofia_Grades = Report_Card.iloc[6:12,2:]

or else:

Sofia_Grades = Report_Card.iloc[[6,7,8,9,10,11],[2,3,4,5]]  }
```

---

## How to group data in Python Pandas:
```
{Report_Card.groupby(["Lectures","Name"]).first()
}
```

## How to access a row in DataFrame:
```{
enjamin_Math  = Report_Card.iloc[0]
How to access a row in DataFrame

The above function simply returns the information in row 0. This is useful, but since the data is labeled, we can also use the loc function:

Benjamin_Math =  

Report_Card.loc[(Report_Card["Name"]     =="Benjamin Duran") &

                (Report_Card["Lectures"] == "Mathematics")]
}
```
---

## How to apply functions in Pandas:

The Pandas apply() function lets you to manipulate columns and rows in a DataFrame. Let’s see how. First we read our DataFrame from a CSV file and display it.
```{

Report_Card = pd.read_csv("Grades.csv")
Report_Card["Retake"] = 

Report_Card["Grades"].apply(lambda val: "Yes" if val < 45 else "No")
}
```