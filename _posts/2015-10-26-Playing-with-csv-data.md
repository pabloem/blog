---
layout: post
title: Playing with csv data
tags:
  - csv
  - data analysis
---

Recently I've been working on a paper to classify relationships between pairs of nodes in a graph. To do the classification, I designed a few features -about 20- for each pair of nodes. I wrote a script that calculates the features for each pair of nodes, and outputs it into a csv file. If you are curious about the project, you may [check it out on Github](http://github.com/pabloem/hanja-graph).

My graph has about 6,000 nodes, so there's approximately 18,000,000 pairs of nodes for which I generate features, so the dataset is pretty large (3.8 G for the file that contains the main features).

Originally, I was doing the main analysis in Python and `scikit-learn`, but after some issues with the classification I had to dive into the features, and before I got any code down, I wanted to do some exploration. I started with the basic console utilities in Linux: `grep`, `awk`, `sed`, etc.; but those only took me so far. I needed something that had CSV built into its philosophy. That's when I found [csvkit](http://github.com/onyxfish/csvkit), a set of Python utilities to work with csv files in the console. It provides basic functionality like `csvcut` to slice, mince and mix the csv files as you wish; or `csvgrep` to run good old string matching on particular columns of the file. It also includes more advanced functionality, like `csvstat`, which will run some basic statistics functions on your csv file or stream.

Because they are coded in Python, they have the disadvantage that they might be slower than the good old Unix alternatives. As an example, I found that normal `grep` was faster than `csvgrep`, with the disadvantage that you don't have an easy way of finely matching columns. The pack also has a bunch of other scripts that I haven't tried, but that might work for your application. You can take a look at [the documentation](http://csvkit.readthedocs.org/en/0.9.1/cli.html), where they go over the different kinds of use cases, and utilities provided in csvkit.

It's all a matter of finding the right tool for what you need. I am very pleased with csvkit, and I recommend you try it too. It might even save you the need to write any code for your exploratory data analysis!
