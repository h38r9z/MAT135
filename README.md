java c
MAT135 – Differential Calculus - Fall 2024
Written Assignment
Clariﬁed MAT135 Assignment 9 (Written Component)
Due 1 December 2024, at 9pm
More details
0. What’s this new version? Students expressed some confusion with Q1(a) and Q1(b), and in retrospect Q1(a) is worded   in a way that really does not seem to need a theorem. This version clariﬁes those things. All changes are in red. 
1. Deadline: The deadline to submit this   assignment   is   strict, to the second.   Assignments   that   are   even   a   few   seconds   late will normally receive a grade of 0.   Technical   issues   are   not   a valid   reason to   be   late, so you   are taking   a   risk   if you   leave uploading your solutions to the last minute. Please give yourself lots of time to upload your assignment! 
2. Purpose and feedback: The   purpose   of the   written   assignments   is   to   give   you   some   practice   in   thinking   about   and   writing solutions to mathematical problems, without anytime pressure. You will receive feedback on your writing and   on your solutions.   You are encouraged to take this   opportunity to   carefully   write your   solutions   and   think   about   how   to best present your reasoning   behind them.
3. Writing solutions: Explain all your work,   show your   steps   as well   as   your   reasoning.   You   should   write in words what   you   are   doing   and   why.      The   person   reading your   solution   should   easily   be   able to   understand   what you   have   done, because you explained it, in words.   Submissions with   little or   no written explanations will   not   receive full marks.
4. Uploading: A   handwritten   assignment can   be   photographed or   scanned.    It   is   important that   the   images   (the   scans   or   photos)   are   clear   and   easy to   read   (not too   dark, too   bright, too   blurry,   etc.).   Your   submitted ﬁles   are   what   will   be   marked, so if the grader(s) can’t read them or can’t   make sense   of   what you’ve written, you will   not   get full   marks.
You may also write your solutions on a tablet, or type your solutions (LaTeX only please) as long as your solutions   are   clear, easy to read and follow, and are   all your   own work.
Make sure you upload solutions to each problem to the correct place. If   you upload solutions   to   the wrong problems,   or uploadallyour   solutions   to   the   same problem, it may result in   getting0on   all problemsuploaded   to   the   wrong places.
5. Grading: The assignment is out   of   10   marks, with the   marks for   each   question   indicated   beside   it.
Marks for each solution will depend on your answer, as well as the quality of your explanation of those answers.
6. Academic Integrity: The solutions that you submit to this   assignment   must   be   all your   own   work.   By   submitting this   assignment you declare that:
(a)    Your solutions are all your own work,   explained   in your own   words.
(b)    You have not copied any part of the assignment   solutions   from   anyone or   anywhere.
(c)    You have not let anyone   else copy   any   part of your solutions to the assignment.
(d)    You have not used   Generative AI   (e.g.,   ChatGPT) for   any   part   of the   assignment.


Background
Several   months   have   passed   since the   aliens   arrived.   The world’s   leading   scientists   are jealous that the   aliens   continue to   seek the help of   MAT135 students at UTM, even after   10%   of the   class tried to   kill   Estra on Written Assignment   6.As incredible as their time here with us has been, the aliens have begun making preparations to leave Earth and head   back to   their home planet.   Despite all   their incredible   technological advancements,   they still have some basic problems   that ﬁrst-year   calculus students (and only ﬁrst-year calculus students) can help them solve.
Problems
1.    (3 points) Estra, who you’ve come to   learn is the alien   ship’s   navigator,   is   planning their   route and   is concerned   about their   fuel levels for their   journey home. The alien ship uses   a   mysterious fuel   called orsh,   a   substance   unfamiliar to   humanity.Estra estimates that the   regular functions of their ship while it   sits   at   UTM   (lights,   communications,   hydroponic fruit   gar-   dens,   and   so   on)   consume   orsh   at   a   rate   between   4000 and   5000 litres   per   day.    The   ship’s   fuel   gauge   says   there   are   currently 300000 litres of orsh on board,   but   Estra tells you that the fuel   gauge’s   reading   can   be   off   by   as   much   as   3000   litres (they’ve been meaning to get it ﬁxed,   but   it’s   so   hard to ﬁnd   a   good   mechanic...).
You may assume that the amount of orsh in the ship’s tank is a differentiable function of time.
(a)    (2   points) Assuming   Estra’s estimates are   correct,   and   accounting for   the   potential   error   from   the   orsh   gauge,   what
is the range of possible amounts of orsh that might be   left   in the ship’s tank after two weeks of   normal operation?         State your ﬁnal answer as an interval (like   [a,b]).   Explain your answer, and   justify the   use of   any theorems you   use.Clariﬁcation: Due to the wording of the   information about orsh   usage   given   above   (it’s   given   as   range   of   litres   used   per day, rather than a direct statement about a derivative) it is possible to   interpret this question   in a   way that can   be   solved without any calculus theorems.   Our original intention with this question was to   mirror examples from   LEC   27   (it’代 写MAT135 – Differential Calculus - Fall 2024 Assignment 9SQL
代做程序编程语言s virtually the same as those examples in all but its   numbers.) We will accept answers of either form. 
(b)    (1point)Estra believes   thejourney   to   theirhomeplanetwill require no lessthan200000   litres   oforsh. Again, assuming   their estimate for the ship’s orsh consumption is correct (and   still   accounting for the   gauge’s   error),   how   many   more
full days can the ship remain at UTM before   it   no   longer   has enough orsh to   make the   journey   home?            State your ﬁnal answer as an integer.   Explain your answer, and   justify the use of any theorems you   use.Clariﬁcation: Everything   mentioned for   part   (a) also applies   here.   In addition, we’d   like to   clarify that this   question   is   asking for how many full days the aliens can stay at UTM starting from now (when the gauge   reads   300000).   Many   students mistakenly thought we were asking for how many days after the two weeks mentioned in   part   (a).


2.    (3 points) The aliens want to stay longer than   your estimate from   Q1(b)   allows,   so their chief   scientist   Genly   has   come   up   with a way of converting water into orsh.   He says that by applying a   great   deal   of   pressure to water, the aliens   can   obtain   many litres of orsh from a single litre of water, with the exact   amount varying as   a   function   of the   pressure.
Genly’s ﬁrst version of   this process produces orsh according to the following function, where G(P)   is the number of litres   of orsh produced by applying a pressure P   > 0 (measured   in   kilopascals,   kP) to   a   litre   of water:
G(P) = 10+(P−10)2/5P2
The aliens can apply very large amounts of pressure to the water, but   need your   help to determine what to do.
(a) (Warm-up! Do not submit this part to Crowdmark.) Check   that   G(10)   =   50.   What   are   the   units   for   this   quantity?   Compute the value of G   for some other values of P. What do you think is   happening for   large values of P?
(b)      (1 point) Show with a limit that increasing the pressure P   to very, very large levels doesn’t produce   more orsh   per   litre   of water.
(c)    (2   points)   Find   the   ideal   pressure   Pi    at   which   this   process   is   most   efﬁcient   (i.e,.    at   which   it   produces   the   largest   quantity of orsh per litre of water).   How much orsh   is   produced   (per   litre   of water)   at the   pressure   Pi?
Clearly   state your two   answers   at the   beginning   of your   solution,   and   show your   work   below.    Don’t forget   to justify   why your answer is where this maximum occurs.
3.    (2 points) Genly’s ﬁrst version of the   process was   good,   but   he   is   conﬁdent   he   can   do   better.
He   spendsanother day reﬁning his ideas, and   comes up   with   a new, adjustable   version   of his process   that produces Gb(P)   litres of orsh per   litre   of water,   where
Gb(P) = 10+(P−b)2/5P2,
where b is a   positive constant that Genly can   manipulate with   his   laboratory   equipment.   We’ve   used the   name   Gb   above   so it’s clear that different values of b make for different functions.
(a)      (1   point)   For   a   (general) value of   b, ﬁnd the   ideal   pressure Pb   at   which   this   process   is   most   efﬁcient   (i.e.,   at   which   it   produces the most litres of orsh   per   litre of water).
Clearly state your answer at   the beginning of   your solution, and show your work below.   Don’t forget   to   justify why your   answer is actually where this maximum occurs.
Hints: Think about whether your answer should depend on b.   You’ve   already found   P10!
(b)      (1 point)   For a (general) value of b,   let   O(b) be the   maximum output   value   of   Gb.   Find   a   formula   for   O(b),   and   show   that   as   b increases,   O(b) also   increases.    In   other   words,   the   maximum   efﬁciency   of   this   process   increases   as   b   increases.
Clearly state your formula at the beginning of your solution, and show your work below.4.    (2   points) A   rival alien scientist   named   Faxe   has   come   up   with   their   own   conversion   process   for   turning   water   into   orsh.
Their process is described   by the function
F(P) =   1+(P−2)2/P3+10.
(a)    (1 point) We already   know   that Genly’s   processes   have   a   high   peakefﬁciency   at   a   low   pressure.
If the aliens are able to apply very high pressures (much   higher than the values of Pb   you were thinking about   in   Q2   and Q3), which process would be produce   more orsh   per   litre   of water?
State   your   answer   (“Genly”   or   “Faxe”)   at   the   top   of   your   answer   and,   in   at   most   two   sentences   and   some   short   computations,   justify your choice below.
(b)      (1   point)   Another   alien   named   Tibe   works   in   Faxe’s   laboratory   and   has   experimented   with   Faxe’s   process   at   high   pressures.Tibe says   that   for   very high pressures,   the increase in orsh production per litre of   water   from Faxe’s process is directly   proportional to the increase in pressure (i.e., Tibe believes that F is a line for large values of P).   Faxe hears this and   thinks   this is at best a good approximation for   what happens at high pressures. The   two of   them come   to   the MAT135   students, who have   just learned about different types of asymptotes in class, for some clariﬁcation.
In   at   most   a few   sentences   and   some   computations,   explain which   one   of   Faxe   or Tibe   is   more   correct   about   F,   and why.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
