# CC6104 Statistical Thinking

The purpose of this course is to introduce students to statistical thinking, a systematic way of thinking to describe "real world" phenomena taking into account their inherent uncertainty and using data for decision making.

The course introduces the fundamentals of statistical thinking, which are descriptive data analysis, statistical programming in R, and probability theory. It then teaches the two most important schools of statistical inference: frequentist inference and Bayesian inference. Finally, advanced topics such as model evaluation using information theory, directed graphical models for modeling conditional dependencies between variables, and multilevel models are discussed.


* Lecturer: [Felipe Bravo-Marquez](https://felipebravom.com/)
* TAs: Ignacio Meza, Sebastián Bustos, Mauricio Araneda, Matías Rojas, Arie Wortsman

* Lectures: Tuesday 14:30 - 16:00, Thursday 14:30 - 16:00  

* [Course Program](https://docs.google.com/document/d/1v-AlWXmS_v1MXgwO-0BOLU05CGbFarMx8EIsG-uDTok/edit?usp=sharing) (in Spanish)

* [Course Calendar](calendar.md)

* [Youtube Playlist with lectures](https://youtube.com/playlist?list=PLppKo85eGXiXpvRVYM5ZJEHWWofjzuiXw)


## Slides

### PART I: Foundations 
1. [Introduction to Statistical Thinking](slides/1_1_ST-intro.pdf) | ([tex source file](slides/1_1_ST-intro.tex)), [video 1](https://youtu.be/X4SqJu6lExM), [video 2](https://youtu.be/YbiQU5TTBX4)
1. [Introduction to R](slides/1_2_ST-R.pdf) | ([tex source file](slides/1_2_ST-R.tex)), [video 1](https://youtu.be/MbeLD3hWWVo), [video 2](https://youtu.be/9W_eWCy86F4),  [video 3](https://youtu.be/QvFXSw2-1r4), [video 4](https://youtu.be/y4JY7klrbfQ)
1. [Descriptive Statistics](slides/1_3_ST-explore.pdf) | ([tex source file](slides/1_3_ST-explore.tex)), [video 1](https://youtu.be/kWNskZ8_98o), [video 2](https://youtu.be/_FJ8x9M4b1w),  [video 3](https://youtu.be/m7VBNZ2mYWI), [video 4](https://youtu.be/ylGMJ_aSQk0)
1. [Probability](slides/1_4_ST-prob.pdf) | ([tex source file](slides/1_4_ST-prob.tex)), [video 1](https://youtu.be/R9AVYV73m1M), [video 2](https://youtu.be/zubh1jbRiKE),  [video 3](https://youtu.be/uiwToagp0z4), [video 4](https://youtu.be/RlhN3t_VIyw), [video 5](https://youtu.be/4kV1dBaeWVc), [video 6]( https://youtu.be/MGyXc70JdSk)

### PART II: Frequentist Inference

1. [Introduction to Statistical Inference](slides/2_1_ST-inference.pdf) | ([tex source file](slides/2_1_ST-inference.tex)), [video 1](https://youtu.be/A0BAhO9_RSI), [video 2](https://youtu.be/6Io555e2stM),  [video 3](https://youtu.be/2-Q2f6zmTns), [video 4](https://youtu.be/Hp2A5EJoXbk), [video 5](https://youtu.be/M0Ag4bww7Q0), [video 6](https://youtu.be/K7khgecup3I), [video 7](https://youtu.be/uZ126Lh3L-k), [video 8]( https://youtu.be/kHSPx99nJ7g)
1. [Design of Experiments & Hypothesis Testing](slides/2_2_ST-hypothesis.pdf) | ([tex source file](slides/2_2_ST-hypothesis.tex)),  [video 1](https://youtu.be/3MueyHnNNig), [video 2](https://youtu.be/JuyIrya23E0),  [video 3](https://youtu.be/OXTyG6DIvK4), [video 4](https://youtu.be/95QeSwrNoLI), [video 5](https://youtu.be/ZCr3WCdc-54), [video 6](https://youtu.be/T6ZR0KoKhBQ)
1. [Linear Regression](slides/2_3_ST-regression.pdf) | ([tex source file](slides/2_3_ST-regression.tex))

### Part III: Bayesian Inference 
1. [Introduction to Bayesian Inference](slides/3_1_ST-bayesian.pdf) | ([tex source file](slides/3_1_ST-bayesian.tex))
1. [Summarizing the Posterior](slides/3_2_ST-posterior.pdf) | ([tex source file](slides/3_2_ST-posterior.tex))  
1. [Bayesian Linear Regression](slides/3_3_ST-bayes_lin.pdf) | ([tex source file](slides/3_3_ST-bayes_lin.tex))
1. [Markov Chain Monte Carlo](slides/3_4_ST-MCMC.pdf) | ([tex source file](slides/3_4_ST-MCMC.tex)) 

### Part IV: Other Topics
1. [Model Evaluation and Information Theory](slides/4_1_ST-eval.pdf) | ([tex source file](slides/4_1_ST-eval.tex)) (Chapter 7 of Statistical Rethinking)
1. [Directed Graphical Models](slides/4_2_ST-dag.pdf) | ([tex source file](slides/4_2_ST-dag.tex)) (Chapter 17 of All of Statistics and Chapter 6 of Statistical Rethinking)
1. [Multilevel Models](slides/4_3_ST-multi.pdf) | ([tex source file](slides/4_3_ST-multi.tex))  (Chapter 13 of Statistical Rethinking)


## Software

* [Rethinking R package](https://github.com/rmcelreath/rethinking)
* [STAN: a state-of-the-art platform for statistical modeling and high-performance statistical computation](https://mc-stan.org/)
* [Rstan: the R interface to Stan ](http://mc-stan.org/rstan/), [installation instructions](https://github.com/stan-dev/rstan/wiki/RStan-Getting-Started)
* [Pyro:  a universal probabilistic programming language (PPL) written in Python and supported by PyTorch on the backend](https://pyro.ai/)
* [DAGitty — draw and analyze causal diagrams](http://dagitty.net/)



## Books

* [Statistical Thinking for the 21st Century](https://statsthinking21.org/)
* [All of Statistics -  A Concise Course in Statistical Inference by Larry Wasserman](http://www.stat.cmu.edu/~larry/all-of-statistics/)
* [Statistical Rethinking by Richard McElreath](https://xcelab.net/rm/statistical-rethinking/)
* [Doing Bayesian Data Analysis: A Tutorial with R, JAGS, and Stan by John K. Kruschke](https://sites.google.com/site/doingbayesiandataanalysis/)
* [Bayesian Data Analysis](http://www.stat.columbia.edu/~gelman/book/)
* [Answering questions with data](https://crumplab.github.io/statistics/)
* [Introduction to Modern Statistics by Mine Çetinkaya-Rundel and Johanna Hardin](https://openintro-ims.netlify.app)
* [Let's Explore Statistics by Colin Quirk](https://bookdown.org/cquirk/LetsExploreStatistics/)
* [Probabilistic Machine Learning: An Introduction by Kevin Patrick Murphy](https://probml.github.io/pml-book/book1.html)
* [Trustworthy Online Controlled Experiments: A Practical Guide to A/B Testing by Ron Kohavi, Diane Tang, and Ya Xu](https://www.cambridge.org/core/books/trustworthy-online-controlled-experiments/D97B26382EB0EB2DC2019A7A7B518F59)
* [Applied Biostats by Yaniv Brandvain](https://bookdown.org/ybrandvain/Applied-Biostats/)
* [Probability and Statistics: a simulation-based introduction by Bob Carpenter](https://github.com/bob-carpenter/prob-stats)
* [Beyond Multiple Linear Regression: Applied Generalized Linear Models and Multilevel Models in R by Paul Roback and Julie Legler](https://bookdown.org/roback/bookdown-BeyondMLR/)

## Courses

* [Richard McElreath - Statistical Rethinking Winter 2020](https://github.com/rmcelreath/stat_rethinking_2020)
* [Jonathan Marchini - Introduction to Probability Theory and Statistics](https://jmarchini.org/teaching/#introduction-to-probability-and-statistics)
* [Jonathan Marchini - Foundations of Statistical Inference](https://jmarchini.org/teaching/#part-b-foundations-of-statistical-inference-bs2a)

## Videos

* [Richard McElreath - Statistical Rethinking Winter 2019 Videolectures](https://www.youtube.com/playlist?list=PLDcUM9US4XdNM4Edgs7weiyIguLSToZRI)
* [Detecting Network Effects: Randomizing Over Randomized Experiments](https://youtu.be/1v5_CzdRVAc)



## Links
* [Statistical Rethinking with brms, ggplot2, and the tidyverse](https://bookdown.org/ajkurz/Statistical_Rethinking_recoded/)
* [Statistical Rethinking with Python and PyMC3](https://github.com/pymc-devs/resources/tree/master/Rethinking)
* [Statistical Rethinking with PyTorch and Pyro](https://fehiepsi.github.io/rethinking-pyro/)
* [Demystifying hypothesis testing with simple Python examples](https://towardsdatascience.com/demystifying-hypothesis-testing-with-simple-python-examples-4997ad3c5294)
* [On Bayesian and frequentist, latent variables and parameters By Dustin Tran](http://dustintran.com/blog/on-bayesian-and-frequentist-latent-variables-and-parameters)
* [What is statistics by Michael Jordan](https://www.youtube.com/watch?v=EYIKy_FM9x0&t=4742s)
* [Foundations of Statistics – Frequentist and Bayesian by Mary Parker](https://www.austincc.edu/mparker/stat/nov04/talk_nov04.pdf)
* [The Permutation Test by Jared Wilber](https://www.jwilber.me/permutationtest/)
* [Spurious Correlations](https://tylervigen.com/old-version.html)
* [Research Methods and Statistics Bristol University](http://www.bristol.ac.uk/medical-school/media/rms/red/index.html)
* [Seeing Theory - Frequentist Inference](https://seeing-theory.brown.edu/frequentist-inference/)
* [Stats with R by Manny Gimond](https://mgimond.github.io/Stats-in-R/index.html)
* [FiveMinuteStats by Matthew Stephens](https://stephens999.github.io/fiveMinuteStats/index.html)
* [Experimentation - Yale Universtity](http://www.stat.yale.edu/Courses/1997-98/101/expdes.htm) 
* [Probabilistic graphical models notes by Stefano Ermon](https://ermongroup.github.io/cs228-notes/)
* [D-separation without tears by Judea Pearl](http://bayes.cs.ucla.edu/BOOK-2K/d-sep.html)
* [ML beyond Curve Fitting: An Intro to Causal Inference and do-Calculus by Ferenc Huszár](https://www.inference.vc/untitled/)
