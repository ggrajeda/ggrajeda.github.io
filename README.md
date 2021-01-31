# Portfolio

Hello, my name is Gabriel Grajeda. I am currently an undergraduate at Princeton University. My projects are listed below with descriptions. Feel free to email me at [ggrajeda@princeton.edu]() with any questions or comments.

# Boston ZIP Earnings Project

## Summary
The Boston ZIP Earnings Project uses several choropleth maps to help visualize the issue of economic segregation in Boston. I created this project to show how Boston city employee earnings have evolved over the past decade and, more importantly, to shed light on income disparities among Boston neighborhoods. I was originally interested in looking at this data because my mother is a teacher in the Boston Public Schools. I found that there exist significant disparities in median city employee salaries between Boston neighborhoods, even after blocking Boston city employees into groups of comparable education and profession. More details can be found on the [repo's README](https://github.com/ggrajeda/boston-zip-earnings) or the [project website](https://ggrajeda.github.io/boston-zip-earnings/).

## Note
This project is currently undergoing review to be hosted on the City of Boston's [Analyze Boston Showcase](https://data.boston.gov/showcase).

## Links
Source code for the project can be accessed at [the project repo](https://github.com/ggrajeda/boston-zip-earnings), and the project itself can be accessed [here](https://ggrajeda.github.io/boston-zip-earnings/).

# Coding Car

## Summary
I created the Coding Car project in the summer of 2016, when I was a rising junior in high school. The point of the project is to introduce kids to coding in a more entertaining way. When the project was up and running, students would visit [this website](https://ggrajeda.github.io/coding-car/) (looks best on Chrome) and learn to program a remote-controlled car at three different levels: **Play**, **Learn**, and **Get Coding!**. More details can be found on the [repo's README](https://github.com/ggrajeda/coding-car).

## Links
Source code for the project can be accessed at [the project repo](https://github.com/ggrajeda/coding-car), and the project itself can be accessed [here](https://ggrajeda.github.io/coding-car/).

# Other Personal Projects

## VIMBoost
I am currently implementing a new random forest algorithm in C++ and R, under the guidance of Assistant Professor Marc Ratkovic. This new algorithm retrieves more meaningful variable importance measures by partialing variables into _predicted_ and _partialed-out_ components, and then creating lookahead trees on what has been partialed out. An initial brute-force implementation of the algorithm by Prof. Ratkovic and a graduate student took 8+ hours on a 16-core computer. My implementation currently takes less than two minutes on a 7-year-old dual-core laptop.

Prof. Ratkovic's paper on the subject is still in the process of publication, and my code is being converted into an R package, so I cannot yet upload my contributions publicly to GitHub. However, you can find the slides for a presentation I gave to incoming Princeton freshmen on the subject [here](https://docs.google.com/presentation/d/1wB6g0gdCDQKx1hLhC0wLswiwwZG4CmK8dMTFZYFPgkY/edit?usp=sharing).

# Smart Plug
I created the Smart Plug in the summer of 2017, when I was a rising senior in high school. The point of the project is to make smart home devices more affordable. Companies often charge high prices for simple smart appliances, like chargers, lights, and AC units. The "smartest" thing about these appliances is that you could turn them on and off remotely. So, instead of making the appliances smart, I realized that we could make the power source smart. The smart plug was a power strip with four smart sockets, which could be scheduled and toggled manually on [this website](https://io.adafruit.com/gabrielgrajeda/dashboards/smartplug) when the project was up and running. The power strip also contained a temperature and humidity sensor, to enable the automatic toggling of AC units.

I haven't uploaded this project yet because it's not as aesthetic or impressive as the projects above, and the code itself isn't very interesting. The Particle Photon simply waits for instructions to toggle four relays and updates the temperature and humidity readings. Building the project took quite some time, however, especially since I was just learning to code. I am working on finding old photos and videos documenting the project. I might upload some of this project documentation, as it might be of interest to others.

## Note
Smart plugs are actually [really common now](https://www.wired.com/gallery/best-smart-plugs/). Back in 2017, however, the concept of a smart plug was relatively new, and not many vendors were selling the product. Google searches for "smart plug" in May 2017 were about 10 percent of what they were in December 2019 (holiday season), and a third of what they were in May 2020. The Google Trends data can be found [here](https://trends.google.com/trends/explore?date=all&geo=US&q=smart%20plug).

# Course Projects
To prevent against plagiarism, my course projects cannot be uploaded to GitHub, but some of them may still be of interest. For each course, I have listed the three most notable projects.

## COS 126: Introduction to Java Programming (Java)
  1. **N-body Simulation**: Simulated the motion of _n_ particles under mutual gravitational forces and animated the results.
  2. **Markov Model**: Generated stylized pseudo-random text after training on large text files.
  3. **Traveling Salesperson Problem**: Implemented the two greedy "nearest neighbor" and "smallest increase" heuristics to find reasonable (but suboptimal) solutions to the traveling salesperson problem.

## COS 217: Introduction to Programming Systems (C)
  1. **Symbol Table**: Implemented a symbol table as a linked list and a hash table.
  2. **Heap Manager**: Wrote five different implementations of a memory heap manager, including a linked list implementation, a doubly-linked list implementation, and a bins implementation.
  3. **Unix Shell**: Implemented my own shell, handling lexical analysis, syntactic analysis, external commands, built-in commands, redirection, and signals.

## COS 226: Algorithms and Data Structures (Java)
  1. **Autocomplete**: "Autocompleted" queries with the closest matching strings in a large text file.
  2. **kd Trees**: Implemented a 2d-tree to optimize range searches and nearest-neighbor searches.
  3. **Seam Carving**: Implemented the content-aware image resizing algorithm known as "seam carving."

## COS 324: Introduction to Machine Learning (Python)
  1. **Clustering**: Implemented clustering algorithm with two different center initialization methods.
  2. **Low Rank Matrix Approximation**: Implemented low-rank matrix approximation algorithm using gradient descent.
  3. **Multiclass Classification of Images**: Implemented and trained a convolutional neural network to classify handwritten digits.

## COS 326: Functional Programming (OCaml)
  1. **Interpreter**: Implemented an environment-based interpreter that prunes function closures efficiently.
  2. **Moogle**: Implemented a web crawler and a PageRank algorithm.
  3. **Web Indexing**: Computed the inverted index of documents efficiently with parallel sequences.