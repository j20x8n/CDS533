java c
CDS533 Assignment 3 
(Statistics for Data Science) 
The assignment may consist of   either two parts—a problem set and an R component—   or   just one part. Please follow the guidelines provided below for each.
Problem Set: 
1.          Manually solve   each question   and   clearly   demonstrate   all   necessary   steps.
2.          You   can   either type   out your   answers   in   MS   Word   or   provide   scanned   images   of   your written answers.
3.          Ensure   that your handwriting   is   clear   and   legible,   and   that   the   quality   of scanned   files is sufficient. Unclear submissions will not be accepted.
R Component: 
1.          Provide screenshots of   R   console   outputs   or   insert   R   plots   as   required   by   the   questions.
2.          For questions involving analysis based on R outputs, please   provide    detailed   explanations to showcase your understanding.
On final submission 
Personal Information:
Ensure that your full name and student ID (SID) are   written   at   the   very beginning   of   the document.
Final Submission Format: 
●          Round your final   answer in 3 decimals. 
●          Your final submission, including the answers from the problem set and R   component, should be merged into a single Microsoft Word document (.docx). 
Submission Deadline: 
Please upload your work in Moodle by 1:30pm 18th Nov, 2024. 
NOTE: USE P-VALUE METHOD FOR HYPOTHESIS TESING PROBLEMS.
1.          A study of   MBA graduates for The American Graduate   Survey   1999 revealed that   MBA   graduates   have   several   expectations   of   prospective   employers   beyond   their base   pay.   In   particular,   according   to the   study   46%   expect   a   performance-related   bonus, 46% expect   stock options. 42% expect   a   signing bonus,   28%   expect   profit   sharing, 27%    expect   extra    vacation/personal    days, 25%    expect       tuition   reimbursement,   24%   expect   health   benefits,   and   19%   expect   guaranteed   annual   bonuses.   Suppose   a   study   is   conducted   in   an   ensuing   year   to   see   whether   these   expectations have changed. If 125 MBA graduates are randomly selected and if   66   expect   stock   options,   does   this   result   provide   enough   evidence   to   declare   that   a   significantly higher proportion of   MBAs expect stock options? Let   α = 0.05. If   the   proportion   really   is   0.50,   what   is   the   probability   of committing   a   Type   II   error?   And   what   is   the   power   of   this   test?
2. Using R to complete this question. An American karate studio plans   to   advertise   but   is   unsure   as   to   which   of three   ads   to   use.   The   ads   are   tested   on   randomly   selected   consumers   and the reactions measured   on   an   ordinal   scale   that produces   the following   data:Red 80,80,78,81,72,85,96,84,71,75,98  White 75,55,98,92,86,78,87,79,88,87,85,94,99 Blue 72,76,70,77,68,82,85,81,65,69 Test   the   claim that reactions   are   the   same   for the   three   different   ads.   Perform. the   Kruskal    Wallis    Test.    If   appropriate,    follow    with    Wilcoxon    tests    to    make    the   decision which ads should be given the contract, and interpret your results.
3.          An   experiment   was   conducted   to   compare   the   wearing   qualities   of   three   types   of paint. Ten point specimens were tested for each paint type and the number of   hours   until   visible   abrasion   was   apparent   was   recorded. Assume   that   the   variances   are   not significantly different, that the distributions are approximately normal, that the   measures are numerical. Is there evidence to indicate a difference in the three plant   types?   Construct   the   ANOVA   table,   show   your   calculation.   Each   group   has    10   readings with the following statistics:

a)          Compute an ANOVA table   for these data   (using a   hand   calculator),   including   all relevant sums of   squares, mean squares, and degrees   of   freedom.
b)          State   the statistical   model   underlying   the   procedures   in   the analysis of   variance   as applied to these data. Define symbols used and make clear all distributional   assumptions.
c)          State    in   words   and    symbols   the   null   hypothesis   and   alternative   hypothesis   appropriate   to   this   problem. Compute   the   relevant   F-test   and   find   the   p-value for the test.
4.          Suppose   we   have   a   data   set   with   five   predictors,    X1= 代 写CDS533 Assignment 3 (Statistics for Data Science)SQL
代做程序编程语言  GPA,    X2=   IQ,    X3=   Level   (1 for College and 0 for High School),    X4          = Interaction between GPA   and IQ, and   X5         =   Interaction   between   GPA   and   Level.   The   response   is   starting   salary   after   graduation   (in   thousands   of   dollars). Suppose   we   use   least   squarestofit   the   model,
and get    β(̂)0       =   50,   β(̂)1      =   20,β(̂)2      =   0.07,β(̂)3      =   35,   β(̂)4      =   0.01,   β(̂)5      = −10 .
a)          Write out   the   regression   equation.
b)          Which answer is correct,   and why?
i.   For   a   fixed   value   of   IQ   and   GPA,   high   school   graduates   earn   more,   on   average, than college graduates.
ii. For a fixed value of   IQ and   GPA,   college   graduates   earn   more,   on   average,   than high school graduates.
iii.   For   a   fixed   value   of IQ   and   GPA,   high   school   graduates   earn   more,   on   average, than college graduates provided that the   GPA is high enough.
iv. For a fixed value of   IQ and GPA,   college   graduates   earn   more,   on   average,   than high school graduates provided that the GPA is high enough.
c)          Predict the salary of   a college   graduate   with   IQ   of   110   and   a   GPA of   4.0.
d)          True   or   false:   Since   the   coefficient   for   the   GPA/IQ   interaction   term   is   very   small, there is very little evidence of   an interaction effect. Justify your answer.
5. Using R to complete this question. This question involves   the   use of   simple linear   regression on the “Auto” data   set.
a)          Use   the lm() function to perform   a   simple   linear regression   with   mpg   as   the   response   and   horsepower   as   the   predictor.   Use   the summary() function   to   print the results. Comment on the   output.
For example:
i.                   Is there a relationship between the predictor and the   response?
ii.                   How strong is the relationship between the predictor and   the   response?
iii.                   Is    the   relationship   between   the   predictor   and   the   response   positive   or   negative?
iv.                   What is the predicted mpg associated with a horsepower   of 98? v.                   What is the associated   95%   confidence   intervals   of   β1   ?
b)          Plot   the   response   and   the   predictor.   Use   the abline() function   to   display   the   least squares regression line.
c)          Use    the plot() function    to    produce    diagnostic    plots    of   the      least      squares   regression fit. Comment on any problems you see with   the   fit.
6.          A   substance   used   in   biological   and   medical   research   is   shipped   by   airfreight   to   users in   cartons   of 1,000   ampules. The   data below,   involving   10   shipments, were   collected   on   the   number   of times   the   carton   was   transferred   from   one   aircraft   to   another over   the shipment route (X) and the number of   ampules found to   be broken upon arrival (Y). Assume the first-order regression model      Y       =    β0          +    β1x   +   ε is   appropriate. 
i 
1 
2 
3 
4 
5 
6 
7 
8 
9 
10 
xi 
1 
0 
2 
0 
3 
1 
0 
1 
2 
0 
Y 
16 
9 
17 
12 
22 
13 
8 
15 
19 
11 
a)          Obtain the estimated regression   function.
b)          Obtain   the   point   estimate   of   the   expected   number   of   broken   ampules   when x      =      1    transfer   is   made.
c)          Estimate   the   increase   in   the   expected   number   of   ampules   broken   when   there are 2 transfers as compared to   1   transfer.
d)          Estimate    β1       with a 95% confidence interval. Interpret your interval estimate.
e)          Conduct a    t      test to decide whether or not there is a linear associaton between   number   of   times   a   carton   is   transferred   (x) and   the   number   of   broken   ampules (Y). Use   a   level   of significance1   of 5%.   State   the   alternatives,   decision rule, and   conclusion. What   is   the   p-value   of   the   test?
f)          A   consultant has suggested, on the basis of   previous experience, that the mean   number of   broken ampules should not exceed 9.0 when no transfers are made.   Conduct   an   appropriate test, using   α   =   0.025.   State the   alternatives,   decision   rule, and   conclusion. What   is   the   P-value   of   the   test?

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
