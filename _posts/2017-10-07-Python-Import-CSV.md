---
layout: post
title:  "Python : Import CSV"
date:   2017-10-07 19:20:00
categories: Python
---

Introduction To The Dataset

{% highlight ruby %}
csv_list = open("US_births_1994-2003_CDC_NCHS.csv").read().split("\n")
csv_list[0:10]
{% endhighlight %}

Converting Data Into A List Of Lists

{% highlight ruby %}
def read_csv(filename):
    string_data = open(filename).read()
    string_list = string_data.split("\n")[1:]
    final_list = []
    
    for row in string_list:
        string_fields = row.split(",")
        int_fields = []
        for value in string_fields:
            int_fields.append(int(value))
        final_list.append(int_fields)
    return final_list
        
cdc_list = read_csv("US_births_1994-2003_CDC_NCHS.csv")
{% endhighlight %}

[Exploring Gun Deaths In The US]

{% highlight ruby %}
import csv

with open("guns.csv", "r") as f:
    reader = csv.reader(f)
    data = list(reader)
{% endhighlight %}

Removing Headers From A List Of Lists

{% highlight ruby %}
header = data[:1]
data = data[1:]
print(header)
print(data[:5])
{% endhighlight %}

Counting

{% highlight ruby %}
years = [row[1] for row in data]

year_counts = {}
for year in years:
    if year not in year_counts:
        year_counts[year] = 0
    year_counts[year] += 1

year_counts
{% endhighlight %}

Read CSV with Pandas 

{% highlight ruby %}
import pandas as pd

food_info = pd.read_csv("food_info.csv")
col_names = food_info.columns.tolist()

print(col_names)
print(food_info.head(3))
{% endhighlight %}

[Exploring Gun Deaths In The US]: https://github.com/HighLvRiver/PythonLearning/blob/master/Basics.ipynb
