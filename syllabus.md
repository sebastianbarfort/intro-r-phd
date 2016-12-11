
\noindent  \textbf{PhD Course: Introduction to \texttt{R}}

\noindent January 16 - January 18, 2017

\noindent Department of Political Science, University of Copenhagen

\noindent Sebastian Barfort ([s.barfort@lse.ac.uk](mailto:s.barfort@lse.ac.uk)). \newline

\noindent \textbf{Objective:}
The aim of this course is to introduce and prepare participants to do quantitative academic work within the social sciences. As increasing emphasis in academics is being placed on the skills needed to effectively gather, handle, model, and analyze data as well as present results to a range of audiences, this course will provide participants with important tools for doing independent research. Furthermore, the skills taught in this course are also in high demand outside academia. Participants will be introduced to an effective workflow for doing effective quantitative research using the R programming language. `R` is a free (based on open source principles) statistical software package, which is supported by a very large international research community. The program can be used to do all types of statistical analyses. \newline

\noindent \textbf{Content:}
A tentative outline of the course, subject to change, is below:

- *Day 1:* Introduction to `R`, basics (reading/writing data, data cleaning, merging, types of data), functions, getting help when things don’t work.
- *Day 2:* Linear and binary choice models, panel data, interactions, standard errors, data visualization.
- *Day 3:* Some combination of: working and visualizing spatial data, analyzing text data, web scraping, statistical learning.

\noindent My plan is to tailor the third day to the specific needs of the course participants. Therefore, if you're enrolled and have a preference for some subset of topics for the third day (or other topics not listed), please send me an email. \newline

\noindent \textbf{Format and Evaluation:}
The course will be very hands-on and will be a combination of lectures and practical instruction using `R`. Focus will be on giving participants hands-on experience doing actual analysis, and finish the course with a series of small scripts that can be used in the future. Practical exercises using real-world research examples from economics and political science will be assigned for each session. \newline

\noindent \textbf{Preparation}: Please make sure you install `R` and `RStudio` before the first day of class. [`R`](http://www.r-project.org/) is a free software environment for statistical computing and graphics. It works on all platforms. If you want to watch a step-by-step tutorial on how to install R for Mac or Windows, you can watch these videos

- [Install R for Windows](https://www.youtube.com/watch?v=Ohnk9hcxf9M&feature=youtu.be)
- [Installing R on the Mac](https://www.youtube.com/watch?v=uxuuWXU-7UQ&feature=youtu.be)

\noindent I recommend you use an [IDE](http://en.wikipedia.org/wiki/Integrated_development_environment) to interact with `R`. IDEs integrate text editing and syntax highlighting, and highly recommend you download and use [`RStudio`](http://www.rstudio.com/). It's free and modern, and if you're new to R this will make it much easier to get started. There's a nice video of how to install `RStudio` here

- [Installing `RStudio`](https://www.youtube.com/watch?v=bM7Sfz-LADM&feature=youtu.be)

\noindent Once installed, try to open up `RStudio` and type the following in the console (lines that start with `##` are the console's output) - don't worry if the commands make no sense to you right now.

\begin{verbatim}
x = 5
y = 2
x + y
## [1] 7
\end{verbatim}

\begin{verbatim}
print("R is running on my computer")
## [1] "R is running on my computer"
\end{verbatim}

\clearpage

\noindent \textbf{Readings/References}: Below are readings or references for each day of the course. I don't expect you to read all these in detail, but it will be easier for you to follow along if you've browsed at least some of them before we meet. You can also use them as references if you want to dig deeper into some of the details after the course.

\begin{center} \textbf{Day 1} \end{center}

\noindent \textit{Core texts} - I recommend at least browsing these before class.

- Leeper, Thomas. 2016. "[Really Introductory Introduction to R](https://github.com/leeper/Rcourse/raw/gh-pages/Intro2R/Intro2R.pdf)". Page *1-17*.
- Grolemund, Garrett and Hadley Wickham. 2016. "[R for Data Science](http://r4ds.had.co.nz/)". The book is to be published by O’Reilly in late 2016/early 2017, but it's free online. *Chapters 3-5, 11-15, 19, 21*.

\noindent \textit{Additional texts} - These are only provided in case you want to go further and learn more about the topics than what we're able to cover in the course.

- Bla bla bla.

\begin{center} \textbf{Day 2} \end{center}

\noindent \textit{Core texts}.

- Grolemund, Garrett and Hadley Wickham. 2016. "[R for Data Science](http://r4ds.had.co.nz/)". *Chapters 23-25, 28*.
- Schwabish, Jonathan A. 2014. "[An Economist's Guide to Visualizing Data](https://www.aeaweb.org/articles.php?doi=10.1257/jep.28.1.209)". *Journal of Economic Perspectives*, 28(1): 209-34.
- Healy, Kieran and James Moody. 2014. "[Data Visualization in Sociology](http://kieranhealy.org/files/papers/data-visualization.pdf)". *Annual Review of Sociology*, 40:105–128.
- Croissant, Yves, and Giovanni Millo. 2008. "[Panel data econometrics in `R`: The `plm` package](http://th.archive.ubuntu.com/cran/web/packages/plm/vignettes/plm.pdf)." *Journal of Statistical Software* 27.2: 1-43.
- Esarey, Justin, and Andrew Menger. 2015. "[Practical and Effective Approaches to Dealing with Clustered Data](http://jee3.web.rice.edu/cluster-paper.pdf)." Department of Political Science, Rice University.

\noindent \textit{Additional texts}.

- Cox, Amanda. "[Data Visualizations at the New York Times](https://www.youtube.com/watch?v=IBfjEEkK3lk)".

- [Fivethirtyeight: How We Charted Trump’s Fall From Grace In Hip-Hop](https://fivethirtyeight.com/features/how-we-charted-trumps-fall-from-grace-in-hip-hop/)

- Wickham, Hadley. 2016. "[Making Data Analysis Easier](https://www.youtube.com/watch?v=hRNUgwAFZtQ)". Workshop presentation organised by the Monash Business Analytics Team.

- Wickham, Hadley. 2010. "[A Layered Grammar of Graphics](http://byrneslab.net/classes/biol607/readings/wickham_layered-grammar.pdf)". *Journal of Computational and Graphical Statistics*, Volume 19, Number 1, Pages 3–28.

- Wickham, Hadley. 2011. “[The Split-Apply-Combine Strategy for Data Analysis](http://www.jstatsoft.org/article/view/v040i01)”. Journal of Statistical Software 40(1).

- Lovelace, Robin and James Cheshire. 2013. "[Introduction to Spatial Data and ggplot2](http://spatial.ly/2013/12/introduction-spatial-data-ggplot2/)".


\begin{center} \textbf{Day 3} \end{center}

- Wickham, Hadley. 2014. "[rvest: easy web scraping with R](http://blog.rstudio.org/2014/11/24/rvest-easy-web-scraping-with-r/)". RStudio Blog.

- Shiab, Nael. 2015. "[On the Ethics of Web Scraping and Data Journalism](http://gijn.org/2015/08/12/on-the-ethics-of-web-scraping-and-data-journalism/)". Global Investigative Journalism Network.

- The Economist. 2016. "[What APIs are](http://www.economist.com/blogs/economist-explains/2016/05/economist-explains-20?fsrc=scn/tw/te/bl/ed/)."

Some examples of academic papers using scraped data

- Stephens-Davidowitz, Seth. 2014. "[The cost of racial animus on a black candidate: Evidence using Google search data](http://www.sciencedirect.com/science/article/pii/S0047272714000929)." *Journal of Public Economics*, 118: 26-40.

- Stephens-Davidowitz, Seth, Hal Varian, and Michael D. Smith. 2016. "[Super Returns to Super Bowl Ads?](http://people.ischool.berkeley.edu/~hal/Papers/2015/super.pdf)". R & R, *Journal of Political Economy*.

- Stephens-Davidowitz, Seth, and Hal Varian. 2015 "[A Hands-on Guide to Google Data](https://www.aeaweb.org/aea/2016conference/program/retrieve.php?pdfid=772)." Google working paper.

- Barberá, Pablo. 2015. "[Birds of the same feather tweet together: Bayesian ideal point estimation using Twitter data](http://pan.oxfordjournals.org/content/23/1/76.short)." *Political Analysis*, 23.1: 76-91.

- Cavallo, Alberto. "[Scraped data and sticky prices](http://www.aeaweb.org/aea/2011conference/program/retrieve.php?pdfid=403)". No. w21490. National Bureau of Economic Research, 2015.

- Bond, Robert M., et al. 2012. "[A 61-million-person experiment in social influence and political mobilization](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3834737/)." *Nature*, 489.7415: 295-298.
