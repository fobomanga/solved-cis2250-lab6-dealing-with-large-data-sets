Download Link: https://assignmentchef.com/product/solved-cis2250-lab6-dealing-with-large-data-sets
<br>
<h2>Overview Skills</h2>

<sup>Learning objectives:</sup>pair programming skills to the projectteamExtracting and examining fields<sub>#H </sub>Dealing with large data sets<sup># Extending our</sup>

coordination + communication (3/6) organization + planning (3/6) teamwork (3/6) programming + tools (5/6) strategy (3/6) visualization (0/6)

(*)[tal Awareness) to 6 (Main Focus).]The skill scale is from 0 (Fundamen-

Image description

A pair of black books. Image sourcepublicdomainvectors.org CC0 1.0

<h3>Team/Pair Organization</h3>

In this lab, we will work in our project teams. Get organized with your team mem-bers, and determine how best to perform the lab work.

<sup>The focus of this lab is answering the question “how does average employment</sup>income change over the last years for people with a computer science degree, whenexamined two and five years after graduation?”

We can answer this question (and more!) based on the data in educationON.csv.

This data is a subset of a larger data set available from Statistics Canada and isavailable online at the website:https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3710015701

This larger data set is entitled “Characteristics and median employment income oflongitudinal cohorts of postsecondary graduates two and five years after gradua-tion, by educational qualification and field of study (STEM and BHASE (non-STEM)groupings), 2010 to 2012 cohorts.” and allows answers to questions regardingeducation and employment.

TheregardingeducationON.csv file is a subset of the larger file, and contains information

<ul>

 <li>•••• earnings reported (in 2017 constant dollars) forCanadian and international studentswho are residents of Ontario,who are university graduates reporting employment incomeand have a degree in computer or information sciences.</li>

</ul>

When you look at the data file you will see that it has columns named:

<ul>

 <li>“REF_DATE”,</li>

 <li>“GEO”,</li>

 <li>“DGUID”,</li>

 <li>“Educational qualification”,</li>

 <li>“Field of study”,</li>

 <li>“Gender”,</li>

 <li>“Age group”,</li>

 <li>“Status of student in Canada”,</li>

 <li>“Characteristics after graduation”,</li>

 <li>“Graduate statistics”,</li>

 <li>“UOM”,</li>

 <li>“UOM_ID”,</li>

 <li>“SCALAR_FACTOR”,</li>

 <li>“SCALAR_ID”,</li>

 <li>“VECTOR”,</li>

 <li>“COORDINATE”,</li>

 <li>“VALUE”,</li>

 <li>“STATUS”,</li>

 <li>“SYMBOL”,</li>

 <li>“TERMINATED”,</li>

 <li>“DECIMALS”</li>

</ul>

What do these columns contain? How many of them can you recognize?

Overview Skills

<sup>Learning objectives:</sup>pair programming skills to the projectteamExtracting and examining fields<sub>#H </sub>Dealing with large data sets<sup># Extending our</sup>

coordination + communication (3/6) organization + planning (3/6) teamwork (3/6) programming + tools (5/6) strategy (3/6) visualization (0/6)

(*)[tal Awareness) to 6 (Main Focus).]The skill scale is from 0 (Fundamen-

Image description

A pair of black books. Image sourcepublicdomainvectors.org CC0 1.0

<h3>Task 1 Description: Select Data To Answer The Question</h3>

Our obejctive is to produce a file that has three columns that describe

<ol>

 <li>the year of the data</li>

 <li>how many years after graduation the graduate is reporting (2 or 5)</li>

 <li>the income (you will find this in a column called “<sup>VALUE</sup>”</li>

</ol>

Your file should describe earnings for all people holding an undergraduate degree.Thethere is information for people with graduate degrees as well).educationON.csv file contains all of this information, and more (for instance, Your task is to determine how to obtain the correct data by writing and running aperl program.

Using any of your past perl programs as a starting point, write a program that willextract the data to answer this question. Put your program in a file calleda single argument: the name of the data file.undergradCSincome.pl. Your program should take Print out the results to the screen in the format shown here below. If everything hasworked correctly, you should see exactly this output:

Year,YearsAfterGraduation,Dollars

2010,”Median employment income two years after graduation”,55600

2010,”Median employment income five years after graduation”,72800 2011,”Median employment income two years after graduation”,58800

2011,”Median employment income five years after graduation”,72800 2012,”Median employment income two years after graduation”,58900

A file containing this data is available on CourseLink for your reference.2012,”Median employment income five years after graduation”,75800

<h3>Task 2 Description: Produce a plot based on your data</h3>

Collect the output of your program into a data file, as we did in the last lab: $ perl undergradCSincome . pl educationON . csv &gt; income . csv

Write a program to plot your data as a line graph, based on thefile we used in Lab 4. Call your new program <sub>createUndergradCSincomePlot.pl</sub>createNameRankPlot.pl.

Running the following command should produce the plot on the next page: $ perl createUndergradCSincomePlot . pl income . csv income . pdf Upload to Courselink

Upload both of your new perl programs to CourseLink:

<ul>

 <li>pl</li>

 <li>pl Project Kickoff</li>

</ul>

<sup>Once you have completed these tasks, be sure everyone in your group has read the</sup>“Project Overview” document in CourseLink, and come up with a strategy to reachthe first milestone described in this document for the next lab.

Overview Skills

<sup>Learning objectives:</sup>pair programming skills to the projectteamExtracting and examining fields<sub>#H </sub>Dealing with large data sets<sup># Extending our</sup>

coordination + communication (3/6) organization + planning (3/6) teamwork (3/6) programming + tools (5/6) strategy (3/6) visualization (0/6)

(*)[tal Awareness) to 6 (Main Focus).]The skill scale is from 0 (Fundamen-

Image description

A pair of black books. Image sourcepublicdomainvectors.org CC0 1.0

Income for CS undergraduates after graduation

<table width="17">

 <tbody>

  <tr>

   <td width="17"><span style="text-decoration: line-through;">●</span></td>

  </tr>

  <tr>

   <td width="17"><span style="text-decoration: line-through;">●</span></td>

  </tr>

 </tbody>

</table>

YearsAfterGraduation

Median employment income five years after graduation

Median employment income two years after graduation