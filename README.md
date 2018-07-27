# rmarkdown-quiz
Random notes related to generating lightweight quiz questions using Rmarkdown

These are some random thoughts related to the generation of assessments / quizzes using r-markdown.  In particular I am looking for solutions which can be hosted as a static site (i.e. solutions that **don't** require shiny etc).

Prompted to open this after seeing https://twitter.com/MattCrump_/status/1022457536740577287. 

rmarkdown can be used to produce [slidy presentations](https://bookdown.org/yihui/rmarkdown/slidy-presentation.html) which can be used to generate quizzes as shown in [this example](http://slidify.github.io/iquiz/)

Adding the capability to include questions for a [xaringan](https://bookdown.org/yihui/rmarkdown/xaringan.html) presentation might also be a possibility. These are built on top of https://remarkjs.com and it seems [adding custom interactivity to the slides is not too difficult](https://github.com/gnab/remark/issues/173)

I'm also aware of http://www.r-exams.org/ but have not used it yet

