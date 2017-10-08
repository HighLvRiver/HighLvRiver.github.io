---
layout: post
title:  "Python : Index with .loc & .iloc in Pandas"
date:   2017-10-09 00:50:00
categories: Python
---

With `.loc[]`, we specify the column label strings as we have in the earlier exercises in this missions. With `.iloc[]`, we simply use the integer number of the column, starting from the left-most column which is 0.

{% highlight ruby %}

first_row_first_column = new_titanic_survival.iloc[0,0]
all_rows_first_three_columns = new_titanic_survival.iloc[:,0:3]
row_index_83_age = new_titanic_survival.loc[83,"age"]
row_index_766_pclass = new_titanic_survival.loc[766,"pclass"]


row_index_1100_age = new_titanic_survival.loc[1100, "age"]
row_index_25_survived = new_titanic_survival.loc[25, "survived"]
five_rows_three_cols = new_titanic_survival.iloc[0:5,0:3]

{% endhighlight %}

After we sorted new_titanic_survival by age, the row indexes were no longer sequential. Each row retained its original index from titanic_survival.

Sometimes it's useful to reindex, starting from 0. We can use the DataFrame.reset_index() method to do this. By default, the method retains the old index by adding an extra column to the dataframe with the old index values

{% highlight ruby %}

titanic_reindexed = new_titanic_survival.reset_index(drop=True)
print(titanic_reindexed.iloc[0:5,0:3])

{% endhighlight %}