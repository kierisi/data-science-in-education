# Teaching Data Science {#c16}

## Chapter Overview

This book is focused on the application of data science to education. In other
words, this book focuses on how to apply data science to questions of teaching,
learning, and educational systems. The previous chapters have addressed this
topic through narrative and walkthroughs for common questions (or problems) and
the types of data encountered in education. In this way, much of the book has
focused on *applying data science methods*. However, for a book on data science
in education, we think it is important to not only discuss the application of
data science methods, but also to consider what we know about *how to teach
about data science*. In recognition of these dual meanings of data science in
education, A recent chapter by one of our authors refers to the application of
data science methods as "data science *in* education\*, and the teaching and
learning of data science as "data science \*for" education
[@rosenberg2020mdsc].

Thus, an important consideration for data science is how to teach others about
data science and how to do it: Naturally, we think educators who do data science
are positioned well to try to describe how to do so. In addition, we expect
readers of this book - many who will also be involved in education - will be
interested in teaching others about data science.

This chapter, then, focuses on teaching data science to others. This chapter is
organized around three topics, which progress from concrete and specific (with
reference to pedagogical approach we used to guide how we wrote this book) to
more general ideas and findings from educational research about teaching and
learning.

1.  The pedagogical principles this book is based upon
2.  Strategies for teaching data science
3.  General strategies related to teaching and learning

## 1\. The pedagogical principles this book is based upon

As the authors of a book about data science in education - and readers of books
that taught us about data science - we considered what would make it effective
for our readers when we set out to write it. The result of this process was a
pedagogical framework that consists of two principles: problem-based learning,
differentiation, and working in the open. We consider each of these in turn.

### Problem-based learning

Problem-based learning (PBL) is a method of instruction that presents learners
with a real-world challenge in which they must apply their skills and knowledge
to solve. We applied this principle to the design of this book through including
walkthroughs for common questions with respect to data science and education.
Whereas some topics may benefit less from such an approach (and the inclusion of
walkthroughs), for data science, we believe this is important because we do not
have all of the right answers in this text. Moreover, there is not one right
statistical model or algorithm, a technique to write code or even software and
tools to utilize.

Thus, the text features walkthroughs that reflect the types of challenges that
educational data scientists may encounter in the course of their work: All of
the data (as well as the code) is available, and readers may choose to go about
approaching the analysis of the data used in each walkthrough differently.
Moreover, the walkthroughs are structured in such a way that readers return to
some of the analytic challenges, but with different aims, over the course of the
book: [Walkthrough 1/Chapter 7](#c07), [Walkthrough 7/Chapter 13](#c13), and
[Walkthrough 8/Chapter 14](#c14) all use the same dataset on online science
learning, but Walkthrough 7 expands Walkthrough 1 by its focus on modeling the
effects of courses, and Walkthrough 8 takes a *predictive*, rather than an
explanatory, goal, through the use of machine learning. Other challenges, such
as processing and preparing data, are introduced in the first walkthrough, and -
reflective of the importance and ubiquity of these steps of the data science
pipeline - returned to in each of the subsequent chapters.

### Differentiation

Differentiation is a method for providing multiple pathways for learners to
engage with, understand, and ultimately apply new content and new skills. To
differentiate this text, we first created personas for who we expected to be
common groups of readers of the book (see @wilson2009 for an example of this
approach).

The objective of this approach was for us to write in a way that helped readers
see themselves in the scenarios. The personas were a way to imagine our audience
and guide who we interviewed to prepare for the writing. The interviews equipped
us to go beyond what we imagined the needs of our readers were and include their
voices in the way we presented the content.

We then aimed to differentiate the book by recognizing and providing background
knowledge (either explicitly or through references to other resources) and
recommendations for where to begin based upon prior expertise. We also provided
screenshots--particularly in [Chapter 5/Getting Started with R and
RStudio](#c05) and [Chapter 6/Foundational Skills](#c06)--that are annotated and
reflective of the content in the text to help to show readers how they are able
to use what they are reading about.

Lastly, a part of differentiating this book concerns for whom we are aiming to
differentiate it. We consider inclusivity (in terms of who belongs as a part of
the audience for this text and how this broader view of who participates in data
science implies the types of challenges, topics, and data that we include in the
book) and accessibility (technically, in terms of how a wide audience of readers
is able to access and use the book, as well as in terms of the ways in which the
content is written based on the unique assets that those in education bring)
along with how we differentiate the book.

### Working in the Open

We started writing this book in the open, on GitHub. This allowed us to share
the book as it developed. Writing the book in the open also allowed others from
the wider educational data science and data science community to contribute.
These contributions included writing sections of the book in which contributors
had specific expertise, asking clarifying questions, and, even, creating a logo
for the book which informed our choice of a color palette. We decided to write
this book in the open after witnessing the success of other books on data
science (such as @wickham2019advr *Advanced R* (<https://adv-r.hadley.nz/>)
book.

### Universal Design

In our original proposal for this book (see @dsieurproposal), we noted that
Universal Design [@mctighe2019upgrade, @wiggins2005understanding] was a part
of our pedagogical framework. As we worked toward completing the book, we
recognized that we did not fully meet the aims we had laid out. Here is what we
wrote in the proposal:

> Universal Design is a series of principles which guide the creation of spaces
> that are inclusive and accessible to individuals from all walks of life
> regardless of age, size, ability, or disability. While traditionally applied
> to physical spaces, we have extended these principles to the creation of a
> data science text in such a way that the text and accompanying materials will
> be designed for individuals from all walks of life, regardless of educational
> level, background, ability, or disability. Many of the seven guiding
> principles of Universal Design are readily transferable to the creation of a
> text, such as equitable use, flexibility in use (aided in large part through
> differentiation), simple and intuitive use, perceptible information, and
> tolerance for error.

While we did not adequately address these in the book, they remain important to
us, and we hope to address them in a future edition of the book.

## 2\. Strategies for teaching data science

You may be interested in teaching others' data science. You may be doing this
informally (such as by teaching a colleague with whom you work in your school
district or organization), in a formal environment (such as a class on data
science for educational data scientists or analysts), or in some setting
in-between (such as a workshop you are asked to provide). There is some research
on teaching data science, as well as practical advice from experienced
instructors that can inform these efforts, which we detail in this section.

### Provide a home base for learners to access resources (and to learn more)

As we discuss in the next section, along with other important factors (such as
learners' motivation and having a supportive atmosphere), learning strategies
can make a difference for learners. Especially when it comes to learning to do
data science, there are many tools and resources to keep track of, such as:

  - How to download and install R
  - How to download and install R Studio
  - How to install packages
  - How to access resources related to the workshop or course (or simply other
    resources you wish to share)
  - How to contact the instructor
  - How to get help and learn more

Having a "home base," where you can remind learners to first look to for
resources, can help to lower some of learners' demands in terms of remembering
how these tools and resources can be accessed. One way to do this is through a
personal website. Another is through GitHub pages. For some organizations, a
proprietary learning management system - such as Desire2Learn, Blackboard,
Moodle, or Canvas - can be helpful (especially if your learners are accustomed
to using them).

### When it comes to writing code, think early and often

It is important to get learners to start writing code early and often. It can be
tempting to teach classes or workshops that front-load content about data
science and using R. While this information is doubtlessly important, it can
mean that those you are teaching do not have the chance to do the things that
they want to do, including installing R (and R Studio) and beginning to run
analyses. Because of this, we recommend starting with strategies that lower the
barrier to writing code for learners. Ways to do this in teaching settings
include:

  - Using R Studio Cloud
  - Providing an R Markdown document for learners to work through
  - Providing a data set and ideas for how to begin exploring it

While these strategies are especially helpful for courses or workshops, they can
be translated to teaching and learning R in tutoring (or "one-on-one")
opportunities for learners. In these cases, being able to work through and to
modify an existing analysis (perhaps in R Studio Cloud) can be a way to quickly
begin to run analyses - and to use the analysis as a template for analyses
associated with other projects. Also, having a data set associated with a
project or analysis - and a real need to analyze it using R - can be an
outstanding way for an individual to learn to use R.

### Don't touch that keyboard!

Resist helping learners to the point of hindering their learning. @wilson2009
writes about the way in which those teaching others about R - or to program, in
general - can find it easier to correct errors in learners' work. But, by fixing
errors, learners' may perceive themselves to not be capable of carrying out all
of the steps needed in an analysis on their own.

This strategy relates to a broader issue, as well: issues that have to do with
writing code in a way that runs correctly (e.g., with the correct capitalization
and syntax) can be minor to those with experience programming, but can be major
barriers to using R in an independent way for those new to it. For example,
becoming comfortable with where arguments to functions belong and how to
separate them, how to use brackets belong in functions or loops, and when it is
necessary to use an assignment operator can be *completely new* to beginners:
doing these steps for learners may push their learning later when they do not
have as many resources available to help them than when you are teaching them.
So, consider taking the additional time needed to help learners to navigate
minor issues and errors in their code: it can pay off in increased motivation on
their part in the longer-term.

### Anticipate issues (and sacrifice accuracy for clarity)

Don't worry about being perfectly accurate early on, especially if doing so
would lead to learners who are less interested in the topic you are teaching.
Especially in cases for which additional details may not be helpful to beginning
learners, it can be valuable to not only anticipate these questions, but to have
responses or answers that provide more clarity, rather than confusion.

For example, there are complicated issues at the heart of why data that is
built-in to packages or to R (such as the iris dataset) appear in the
environment after they are first used in an R session (see the section on
"promises" in @wickham2019advr). Similarly, there are complicated issues that
pertain to how functions are evaluated that can explain why it is important to
provide the name of packages installed via `install.packages()` (whereas the
names of arguments to other functions, such as `dplyr::select()` do not need to
be quoted).

### Start lessons or activities with visualizing data

There are examples from data science books @grolemund2018 and past research
(e.g. @lehrer2015) that suggests that starting with visualizing data can be
beneficial in terms of learners' ability to work with data. @grolemund2018 write
that they begin their book, *Data Science Using R*, with a chapter on
visualization, because doing so allows learners to create something that they
can share immediately, whereas tasks such as loading data can be rife with
issues - and does not immediately lead learners to have a product they can
share. @lehrer2007 show how providing students with an opportunity to invent
statistics by displaying the data in new ways. This led to (productive) critique
among fifth- and sixth-grade students and their teacher.

### Consider representation and inclusivity in the data and examples you use

One way to think about data is that it is objective, free of decisions about
what to value or prioritize. Another is to consider data as a process that is
value-laden, from deciding what question to ask (and what data to collect) to
interpreting findings with attention to how others will make sense of them
(e.g., @oneill2016's *Weapons of Math Destruction*, and @lehrer2007's
description of data modeling). From this broader view, choosing representative
data is a choice, like others, that teachers can make. For example, instructors
can choose data that directs attention to issues--equity-related issues in
education, for example--that she or he believes would be valuable for students
to analyze.

We think this consideration is important - particularly when it comes to
data-related issues that we consider to be objective, such as how variables are
assumed and constructed to be dichotomous (such as variables for individual's
gender) or categorical (such as variables for individual's race), when the truth
may be that such variables are based on decisions that analysts or those
collecting data made - decisions that may benefit from questioning. This
consideration is also important when it comes to what data is used for teaching
and learning. If names of individual's in data exclusively from individuals from
majority racial or ethnic group, for example, some learners may implicitly
perceive the content being taught to be designed for others. While we may think
that such issues are better left to those we are teaching to decide later on,
setting the stage in classes, courses, and other contexts in which data science
is taught and learned can set an important precedent for the data our learners
use and how they use it.

### Draw on other resources

In this section of this chapter, we presented some strategies for teaching data
science. There are others that go more into depth on this topic from different
perspectives, such as the following:

  - [GAISE
    Guidelines](https://www.amstat.org/asa/education/Guidelines-for-Assessment-and-Instruction-in-Statistics-Education-Reports.aspx) (https[]()://www.amstat.org/asa/education/Guidelines-for-Assessment-and-Instruction-in-Statistics-Education-Reports.aspx):
    guidelines for teaching statistics
  - [Data Science for
    Undergraduates](https://www.nap.edu/catalog/25104/data-science-for-undergraduates-opportunities-and-options) ((https[]()://www.nap.edu/catalog/25104/data-science-for-undergraduates-opportunities-and-options)):
    a report on undergraduate data science education
  - [R Studio Education](https://education.rstudio.com/) (https[]()://education.rstudio.com/)

There are also a number of data science-related curricula (for the K-12 level)
which may be helpful:

  - [Bootstrap Data Science](https://www.bootstrapworld.org/blog/index.shtml)(https[]()://www.bootstrapworld.org/blog/index.shtml)
  - [Exploring CS, unit 5](http://www.exploringcs.org/curriculum) (http[]()://www.exploringcs.org/curriculum)
  - [Chromebook Data Science](http://jhudatascience.org/chromebookdatascience/) (http[]()://jhudatascience.org/chromebookdatascience/)
  - [Oceans of Data Institute
    Curricula](http://oceansofdata.org/our-work/ocean-tracks-high-school-learning-modules) (http[]()://oceansofdata.org/our-work/ocean-tracks-high-school-learning-modules)

Last, there are also books that emphasize the importance--for teachers--of
understanding their students--every student. These books include
@bookparis2017culturally, @kozol2012savage, and will likely be valuable for
teachers of data science who wish to understand and honor the diversity of their
students. @moore2017guide and @emdin2016 may be helpful for data science
educators who aim to be aware and intentional about teaching students from
backgrounds other than their own.

## 3\. General strategies related to teaching and learning

The National Academy of Science commissioned a report, *How People Learn*
[@nrc2000], that aimed to summarize research from the educational psychology
and the learning sciences on teaching and learning. In 2018, the book was
updated in *How People Learn II* [@nrc2018], which aimed to emphasize the
social and cultural aspects of teaching and learning, which were not as much the
focus of the earlier report. These may be helpful to those teaching data science
for the general strategies they reference related to teaching and learning

In addition to these reports, there are some books that are more
practically-oriented, including @hattie2012visible, @lemov2015teach, and
@bambric. These can help to provide some answers to the question of how to teach
data science--and to mitigate some of the anxiety that those teaching data
science may feel about how to teach others to know about and do data science:
There are existing resources on teaching that are highly-relevant, and it is
important to not feel like you must recreate the wheel!

In this section, then, we highlight general strategies related to teaching and
learning, drawing from the above reports and books, with an emphasis on
strategies applicable to teaching and learning data science. These general strategies
are more conceptual than those described in the last section, and are likely more
useful as starting points for further research or reflection, instead of as specific techniques that can be brought to the next
workshop, class, or peer-to-peer teaching session one is leading.

### Teaching and learning are complex

One principle that *HPL2* begins with is that learning is complex. in short,
learning is not just about what learners know, or think, but is also about
developmental, cultural, contextual, and historical factors - and distinctions
between individuals with respect to each of these factors. This is an asset to
teachers, as the authors of the report state: Learners bring resources that can
serve as a starting point for their learning trajectory when it comes to data
science. These distinctions also mean that educators need to be concerned with -
and to consider within their purview - factors well beyond what learners know,
but also what their prior educational experiences have been and what resources
and other individuals they have access to at work and at home, for example.

### Learners learn many different things (consciously and unconsciously)

We often think of learning in terms of objectives for specific lessons, but
learners learn many different things at different times. The authors of *HPL2*
point out that individuals learn in response to different challenges and
circumstances, including those in formal learning environments, such as
workshops or classes. This principle implies a strategy that involves supporting
learners to do data science, however and whenever they learn it. This means that
it is both okay - and even to be expected - that learners may take away more
from a problem they try to solve on their own, than what they do from a workshop
or class (or even a degree!). This also suggests that learners may learn things
that we do not anticipate, such as how instructors try to solve problems that
arise in class.

### Meta-cognition is important (even though it sounds more sophisticated than it is!)

Educators and educational researchers often talk about meta-cognition, or
thinking (and ideas) about thinking, as if it is something only very
sophisticated learners do, but it is truly something much more commonplace, as
people (and learners) are thinking about what they are learning and doing
regularly. One strategy for instructors to support meta-cognition is to include
moments wherein learners are asked to consider what they learned and what they
would like to learn more about (exit tickets can be a great way to do this, but
brief period in-class can also be used). Another strategy is to help learners to
recognize when it is important to ask for help: Often, when doing data science,
the right question to the right person (or community) can save hours of work.

### Learning strategies matter

While teachers are responsible for designing learning opportunities, learners
also play an important role - in their own learning! Learning strategies,
according to the authors of *HPL2*, matter, including those that help students
to retrieve information and summarize and explain what they have learned (for
themselves and others). There are many specific strategies documented in
[chapter four](https://www.nap.edu/read/24783/chapter/6#72) (https[]()://www.nap.edu/read/24783/chapter/6#72) of *HPL2*. What is
important for teachers of data science to know is less the specific strategies,
and more the commitment to teaching learners how to learn.

In addition to strategies for learners, teaching strategies, such as how content
is spaced and sequenced, can also help learners. @dirksen2015's *Design for How
People Learn* presents these strategies, based largely about instructional
design research, that may be helpful to those teaching data science.

### Educators can help students to learn

Educators know that how motivated learners are matters. According to the authors
of *HPL2*, teachers can make an impact on how motivated learners are. Some
specific things that educators can do to support learners include helping
learners to set (and to work toward) goals, selecting content that is valuable
and interesting to learners, helping learners to have choices and showing them
how they are in-control of their learning value, and supporting learners to feel
good at and supported in what they are doing. In short, motivation matters, and
may be especially important when teaching learners who do not see the value of
data science (initially!).

## Summary

In this section, we described the pedagogical principles for this book and
strategies for teaching data science. We also directed attention to more general
strategies for teaching and learning. Teaching data science is a relatively new
area, but data science educators are not alone, and do not need to reinvent the
wheel. There are many already-existing resources and those that can be adapted
from other disciplines and the wider body of educational research.
