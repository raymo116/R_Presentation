# R

## Matt Raymond, Charlie Raymond, Andrew Bauer

There are a couple of reasons that we thought it would be a good idea to work with R. First of all, we’ve worked with R before, and its something that we’re all familiar with. We thought that it’d be better to study a language that we already knew than to start off with a brand new one. Additionally, R is extremely important for Data Science, which is a topic that some of us are really interested in at the moment. Furthermore, R seems to have a relatively unique programming method, acting more like a computational environment than code intended to be compiled into a standalone executable. Finally, it seemed interesting because it’s one of the few languages that we know of that’s meant to be used in a specialized, language-specific IDE. Many other languages can be written in a notepad, but R is specifically meant to work with R studio. This is due, in part to its unique history.

R has a convoluted and interesting background. Like many programming languages, R was an iterative improvement of another, less-popular language: S. Developed by Bell Labs for statistical computing, it was intended to improve and expand upon many of S’s limitations. However, the largest improvement was the addition of lexical scoping. This means that even though variables inside functions will hide ones outside, uniquely-named variables in a global namespace can still be reached. This allows you to execute your code completely out of order (one of the features of R), and still maintain computational continuity.

Originally written in C and FORTRAN, R was conceived by Robert Gentleman and Ross Ihaka, who worked at the University of Auckland, New Zealand. Due to its small development team, who were mainly concentrated on their own research, R spent an extended period of time in development. Although programming began in 1992, an alpha version wasn’t released to the public until 1995. A couple of years later, in 1997, R joined the GNU project in order to improve the free library of software they project, and a stable beta was released in 2000. As demand increased, the language became an open-source project operated by the R foundation. In addition to adding more core features to the language, the R foundation facilitates the dissemination and regulation of standard “packages”, which are effectively R libraries. Largely written by members of the public, they extend R’s functionality with pre-compiled code written in C, FORTRAN, and R.

Due to its focus on statistical computing, R is highly optimized for complex computations over large datasets, such as matrix arithmetic and machine learning models. Additionally, because many R packages are written in low-level languages like C and FORTRAN, some allow for extremely fast data processing. Furthermore, R has an extensive amount of built-in graphics processing, and as a result, it’s optimal for data analysis, statistical modeling, simulation, and chart rendering. As an added bonus, the way that R is written can be abstract enough that the same code can be reused again and again for different datasets with only slight modifications to the code. In fact, there are even built-in functions to help you automatically clean up messy datasets. However, there are some disadvantages to R. Because it’s based on a relatively old language, there is little support for 3d and interactive graphics. Additionally, because R was simply meant to be a statistics tool, there are basically no security features built into the language. R is also commonly cited as handling loops extremely poorly outside of default, built-in functions, and R can sometimes be slow due to the lack of optimization between packages. In general, it appears that R is best for non-computer scientists who want to be able to perform standard statistical computing without too many frills or packages running at once.

R is currently the 7th most popular programming language in the world and is still growing in use. Due to its popularity, many modern-day companies have adopted the language to their own platforms to stay competitive. In 2012, Oracle adopted R under its belt as Oracle R Enterprise to become a part of the Oracle Advanced Analytics. Due to its ease of data handling, their new Oracle R Enterprise allows users to apply their existing R scripts and models to the data mining platform.

Since it’s more of a statistical tool than an actual programming language, R has a couple of really interesting features. One feature is that there are no scalar types, only vectors with a length of 1. This means that if you want to add two numbers together, you’re not adding x + y, you’re adding the matrix [x] + the matrix [y]. We’re not exactly sure why this is, but we assume that because R is meant to be used on tables and datasets almost exclusively, there wasn’t much of a point of adding scalar variables. Furthermore, in R, we have what is called “First Class Functions”, which are functions can be treated as objects (they can be saved into variables, passed to functions, etc.). Finally, due to the fact that it’s open-source, there are some people who’ve decided that they want to try to squeeze every ounce of performance out of the language. One example of this is pqR, which even will split up functions onto multiple cores to allow them to run faster.

R is a unique programming language that’s helped give rise to a whole new programming style and has even led to old languages being adapted to fit this new paradigm (such as ipython notebooks). Although it’s only useful for a very niche market, as data science becomes more important than ever, R will continue to have lasting effects on computer science and programming as a whole.


## Code Examples



## Sources
https://en.wikipedia.org/wiki/R_(programming_language)

https://www.r-project.org/about.html

https://data-flair.training/blogs/pros-and-cons-of-r-programming-language/

https://www.geeksforgeeks.org/first-class-functions-python/

http://www.pqr-project.org/

http://adv-r.had.co.nz/Functions.html

http://pypl.github.io/PYPL.html


## Presentation
https://docs.google.com/presentation/d/1LmseXbSVqE7cn9U7h80DoYnZ72MeQzt2_ifLj3s6CZs/edit?usp=sharing

## Notation for Presentation

Real World Use
- 7th Most Popular Language
    - So R is currently the 7th most popular language worldwide
    - That means that it has to be doing something right
    - Not only that but that means it’s incredibly utilized in the computer science industry, meaning you guys might want to pick up the language in your free time
- Oracle
    - One of the big tech giants to officially adopt R was Oracle
    - In 2012 they integrated R within their Oracle R Enterprise
    - This is Oracle’s big data mining platform and they integrated R because of R’s both widespread and ease of use
- Google
    - Another big tech giant to admit to using R is Google
    - With their Google Flu Trends project, a project to visualize current flu projections, they use R to estimate current flu activity based off Google Search results
    - Within this project they take large sets of data, which in this instance a bunch of users’ search queries, and utilize R to create models with optimized weights to estimate flu activity around the world
- Facebook
    - The last big tech giant, although there are many, that uses R is Facebook
    - With the thousands of data points that they pull from a single user, they can predict the emotions of a user
    - As seen on the graph on the screen, Facebook was able to show that people in a relationship are generally happier than those who are single
    - They created this correlation through the number of posts that a user posts when single vs when in a relationship based on when the user changes their relationship status
    - All of this data was then organized and visualized through R as seen on the screen


Advantages
- Great With Data
    - The language itself was originally created to deal with data
    - It’s fantastic for observing statistics and analyzing said data which brings me to R’s next advantage
- Visualization
    - R is extremely flexible and easy to use when trying to create visualizations for data
    - The language itself has a bunch of built in functions that create a smart display of data such as the str() function which will display each individual input and output of any function
    - Another built in function that’s extremely useful when dealing with data is the summary function that will display descriptive statistics for every function within the dataset such as the minimum, maximum, and median
    - The plot function is a built in function that will automatically display all data points on a computer generated graph
    - All these functions are just a couple of built in functions that aide to creating processes such as simulations, graphs, and charts
- Open-Source
    - R is open-source meaning anyone can examine the source code to see exactly what’s happening in the background
    - This also helps improve the language as users are able to fix bugs and implement features without waiting for a vendor
    - Also, since R is the 7th most popular language, there’s a massive user support for the language including tons of tutorials, forums, and people working to improve the language constantly
- Easy Cross Language Integration
    - There are tons of community generated packages to implement R within other languages due to R’s large community
    - This makes it extremely simple to find a package to implement R
- Object Oriented
    - Lastly, it’s object oriented, meaning you can create any object of your imagination
    - Which also basically means its not as annoying as C is
