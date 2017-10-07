---
layout: post
title:  "Python : Computation with NumPy"
date:   2017-10-07 20:20:00
categories: Python
---

Totals

{% highlight ruby %}
is_canada_1986 = (world_alcohol[:,2] == "Canada") & (world_alcohol[:,0] == '1986')
canada_1986 = world_alcohol[is_canada_1986,:]
canada_alcohol = canada_1986[:,4]
empty_strings = canada_alcohol == ''
canada_alcohol[empty_strings] = "0"
canada_alcohol = canada_alcohol.astype(float)
total_canadian_drinking = canada_alcohol.sum()

print(total_canadian_drinking)
{% endhighlight %}

{% highlight ruby %}
totals = {}
is_year = world_alcohol[:,0] == "1989"
year = world_alcohol[is_year,:]

print(year)

for country in countries:
    is_country = year[:,2] == country
    country_consumption = year[is_country,:]
    alcohol_column = country_consumption[:,4]
    is_empty = alcohol_column == ''
    alcohol_column[is_empty] = "0"
    alcohol_column = alcohol_column.astype(float)
    totals[country] = alcohol_column.sum()
{% endhighlight %}


Highest_value

{% highlight ruby %}
highest_value = 0
highest_key = None

for country in totals:
    consumption = totals[country]
    if highest_value < consumption:
        highest_value = consumption
        highest_key = country
{% endhighlight %}
