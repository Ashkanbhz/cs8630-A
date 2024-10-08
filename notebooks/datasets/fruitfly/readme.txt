
NAME:  Sexual activity and the lifespan of male fruitflies
TYPE:  Designed (almost factorial) experiment
SIZE:  125 observations, 5 variables

DESCRIPTIVE ABSTRACT:
A cost of increased reproduction in terms of reduced longevity has been
shown for female fruitflies, but not for males.  The flies used were an
outbred stock.  Sexual activity was manipulated by supplying individual
males with one or eight receptive virgin females per day.  The
longevity of these males was compared with that of two control types.
The first control consisted of two sets of individual males kept with
one or eight newly inseminated females.  Newly inseminated females will
not usually remate for at least two days, and thus served as a control
for any effect of competition with the male for food or space.  The
second control was a set of individual males kept with no females.
There were 25 males in each of the five groups, which were treated
identically in number of anaesthetizations (using CO2) and provision of
fresh food medium.

SOURCE:
Figure 2 in the article "Sexual Activity and the Lifespan of Male
Fruitflies" by Linda Partridge and Marion Farquhar.  _Nature_, 294,
580-581, 1981.

VARIABLE DESCRIPTIONS:
Columns  Variable    Description
-------  --------    -----------
 1- 2    ID          Serial No. (1-25) within each group of 25
                     (the order in which data points were abstracted)

 4       PARTNERS    Number of companions (0, 1 or 8)

 6       TYPE        Type of companion
                       0: newly pregnant female
                       1: virgin female
                       9: not applicable (when PARTNERS=0)

 8- 9    LONGEVITY   Lifespan, in days

11-14    THORAX      Length of thorax, in mm (x.xx)

16-17    SLEEP       Percentage of each day spent sleeping


SPECIAL NOTES:
`Compliance' of the males in the two experimental groups was documented
as follows:  On two days per week throughout the life of each
experimental male, the females that had been supplied as virgins to
that male were kept and examined for fertile eggs.  The insemination
rate declined from approximately 7 females/day at age one week to just
under 2/day at age eight weeks in the males supplied with eight virgin
females per day, and from just under 1/day at age one week to
approximately 0.6/day at age eight weeks in the males supplied with one
virgin female per day.  These `compliance' data were not supplied for
individual males, but the authors say that "There were no significant
differences between the individual males within each experimental
group."

STORY BEHIND THE DATA:
James Hanley found this dataset in _Nature_ and was attracted by the
way the raw data were presented in classical analysis of covariance
style in Figure 2.  He read the data points from the graphs and brought
them to the attention of a colleague with whom he was teaching the
applied statistics course.  Dr. Liddell thought that with only three
explanatory variables (THORAX, plus PARTNERS and TYPE to describe the
five groups), it would not be challenging enough as a data-analysis
project.  He suggested adding another variable.  James Hanley added
SLEEP, a variable not mentioned in the published article.  Teachers can
contact us about the construction of this variable.  (We prefer to
divulge the details at the end of the data-analysis project.)

Further discussion of the background and pedagogical use of this
dataset can be found in Hanley (1983) and in Hanley and Shapiro
(1994).  

PEDAGOGICAL NOTES:
This has been the most successful and the most memorable dataset we
have used in an "applications of statistics" course, which we have
taught for ten years.  The most common analysis techniques have been
analysis of variance, classical analysis of covariance, and multiple
regression.  Because the variable THORAX is so strong (it explains
about 1/3 of the variance in LONGEVITY), it is important to consider it
to increase the precision of between-group contrasts.  When students
first check and find that the distributions of thorax length, and in
particular, the mean thorax length, are very similar in the different
groups, many of them are willing to say (in epidemiological
terminology) that THORAX is not a confounding variable, and that it can
be omitted from the analysis.

There is usually lively discussion about the primary contrast.  The
five groups and their special structure allow opportunities for
students to understand and verbalize what we mean by the term
"statistical interaction."

There is also much debate as to whether one should take the SLEEP
variable into account.  Some students say that it is an `intermediate'
variable.  Some students formally test the mean level of SLEEP across
groups, find one pair where there is a statistically significant
difference, and want to treat it as a confounding variable.  A few
students muse about how it was measured.

There is heteroscedasticity in the LONGEVITY variable.

One very observant student (now a professor) argued that THORAX cannot
be used as a predictor or explanatory variable for the LONGEVITY
outcome since fruitflies who die young may not be fully grown, i.e., it
is also an intermediate variable.  One Ph.D. student who had studied
entomology assured us that fruitflies do not grow longer after birth;
therefore, the THORAX length is not time-dependent!

Curiously, the dataset has seldom been analyzed using techniques from
survival analysis.  The fact that there are no censored observations is
not really an excuse, and one could easily devise a way to introduce
censoring of LONGEVITY.

REFERENCES:
Hanley, J. A. (1983), "Appropriate Uses of Multivariate Analysis,"
_Annual Review of Public Health_, 4, 155-180.

Hanley, J. A., and Shapiro, S. H. (1994), "Sexual Activity and the
Lifespan of Male Fruitflies:  A Dataset That Gets Attention," _Journal
of Statistics Education_, Volume 2, Number 1.

SUBMITTED BY:
James A. Hanley and Stanley H. Shapiro
Department of Epidemiology and Biostatistics
McGill University
1020 Pine Avenue West
Montreal, Quebec, H3A 1A2
Canada
tel: +1 (514) 398-6270 (JH) 
     +1 (514) 398-6272 (SS)
fax: +1 (514) 398-4503
INJH@musicb.mcgill.ca, StanS@epid.lan.mcgill.ca
