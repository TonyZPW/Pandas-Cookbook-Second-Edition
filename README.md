## $5 Tech Unlocked 2021!
[Buy and download this Book for only $5 on PacktPub.com](https://www.packtpub.com/product/pandas-1-x-cookbook-second-edition/9781839213106)
-----
*If you have read this book, please leave a review on [Amazon.com](https://www.amazon.com/gp/product/1839213108).     Potential readers can then use your unbiased opinion to help them make purchase decisions. Thank you. The $5 campaign         runs from __December 15th 2020__ to __January 13th 2021.__*

# Pandas 1.x Cookbook - 2nd Edition
This is the code repository for [Pandas 1.x Cookbook - 2nd Edition](https://www.packtpub.com/programming/pandas-1-x-cookbook-second-edition), published by [Packt](https://www.packtpub.com/). It contains all the supporting project files necessary to work through the book from start to finish.

## About the Book
A new edition of the bestselling Pandas cookbook updated to pandas 1.x with new chapters on creating and testing, and exploratory data analysis. Recipes are written with modern pandas constructs. This book also covers EDA, tidying data, pivoting data, time-series calculations, visualizations, and more.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

The code will look like the following:
```
def tweak_kag(df):
    na_mask = df.Q9.isna()
    hide_mask = df.Q9.str.startswith('I do not').fillna(False)
    df = df[~na_mask & ~hide_mask]

```


## Related Products
* [Artificial Intelligence with Python – Second Edition](https://www.packtpub.com/in/data/artificial-intelligence-with-python-second-edition)

* [Mastering Machine Learning Algorithms - Second Edition](https://www.packtpub.com/in/data/mastering-machine-learning-algorithms-second-edition)