---
layout: post
title:  "Python : Pandas Dataframe "
date:   2017-10-18 22:00:00
categories: Python
---

Pandas Internals: Dataframes

{% highlight ruby %}

fandango_films = fandango.set_index('FILM', drop=False)

movies = ["The Lazarus Effect (2015)", "Gett: The Trial of Viviane Amsalem (2015)", "Mr. Holmes (2015)"]
best_movies_ever = fandango_films.loc[movies]

{% endhighlight %}

{% highlight ruby %}

import numpy as np

# returns the data types as a Series
types = fandango_films.dtypes
# filter data types to just floats, index attributes returns just column names
float_columns = types[types.values == 'float64'].index
# use bracket notation to filter columns to just float columns
float_df = fandango_films[float_columns]

# `x` is a Series object representing a column
deviations = float_df.apply(lambda x: np.std(x))

print(deviations)

{% endhighlight %}

{% highlight ruby %}

double_df = float_df.apply(lambda x: x*2)
print(double_df.head(1))
halved_df = float_df.apply(lambda x: x/2)
print(halved_df.head(1))

{% endhighlight %}

{% highlight ruby %}

rt_mt_user = float_df[['RT_user_norm', 'Metacritic_user_nom']]
rt_mt_deviations = rt_mt_user.apply(lambda x: np.std(x), axis=1)
print(rt_mt_deviations[0:5])
rt_mt_user = float_df[['RT_user_norm', 'Metacritic_user_nom']]
rt_mt_means = rt_mt_user.apply(lambda x: np.mean(x), axis=1)
print(rt_mt_means[0:5])

{% endhighlight %}
