+++
title = "Exploring Open Datasets"
date = "2025-01-06"

[taxonomies]
tags=["data science", "projects"]

[extra]
repo_view = true
comment = false
+++

# Exploring Open Datasets for Predictive Models

I've started to find and collect openly available datasets that can be used for 
predictive moldeing, classification or regression.

It is at first surprising how hard it is to find publicly available datasets
that are somewhat realistic. Most of the common test sets are very clean
and thus very unlike any real data. Now there is a place for that in
testing and demonstrating new ideas (although we all need to stop using Iris),
but has little to do with what actually occupies most of a data scientists's time.

Now, on second thought this does make sense. Real data is complex because
each problem is unique and has a different mix of problems. Expecting to be 
able to just grab a dataset that is not too simple but does also not have
problems except for the one you are trying to explore is illusory.

This was dispiriting, but when I started poking around some sights
for sharing data to reproduce academic publications, the thought I'd
been missing came to me: Exploring real datasets can fill our
repository of ideas and toolbox of methods for tackling new problems. 
Even if we just scratch the surface and think about what the key qualities
of a dataset are, we can set ourselves up to go "Ah, I thought about
that before" in a few weeks or decades; and we will be more ready to 
tackle the new problems, because just seeing them is the biggest step.

So, not all that much here yet as of writing this, but I've collected
three datasets so far [in this notebook](https://github.com/jrings/model_citizen/blob/main/notebooks/datasets_overview.ipynb)
and done some basic exploration in neighboring notebooks. I've been
harvesting them from [Harvard Dataverse](https://dataverse.harvard.edu)
and [DataOne](https://www.dataone.org). More thoughts on this to follow.