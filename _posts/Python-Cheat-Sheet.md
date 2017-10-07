---
layout: post
title:  "Python Cheat Sheet"
categories: Cheat_Sheet
---
참고 : [Basics.ipynb]

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

Counting Gun Deaths By Year

{% highlight ruby %}
years = [row[1] for row in data]

year_counts = {}
for year in years:
    if year not in year_counts:
        year_counts[year] = 0
    year_counts[year] += 1

year_counts
{% endhighlight %}

[Basics.ipynb]: https://github.com/HighLvRiver/PythonLearning/blob/master/Basics.ipynb
