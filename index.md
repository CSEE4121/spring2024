---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
menu: main
---

CSEE4121 - Computer Systems for Data Science 
{: style="color:black; font-size: 190%; font-weight:700; text-align: center; padding-top: 15px;"}
Spring '24, Columbia University
{: style="color:black; font-size: 130%; text-align: center; padding-bottom: 30px;"}

----

## Course Overview
Data scientists and engineers increasingly have access to a powerful and broad
range of systems they use to conduct big data analysis and machine learning at
scale: from databases, large-scale analytics to distributed machine learning
frameworks. \\
\\
The goal of this class is to provide data scientists and engineers that work
with big data a better understanding of the foundations of how the systems they
will be using are built. It will also give them a better understanding of the
real-world performance, availability and scalability challenges when using and
deploying these systems at scale. In the course we will cover foundational ideas
in designing these systems, while focusing on specific popular systems that
students are likely to encounter at work or when doing research. The class will
include some written homework and programming assignments. One of the
programming assignments will be done in pairs, and the rest will be done
individually. In this course we will answer the following questions:
<ul>
  <li>How are popular big data systems designed and architected?</li>
  <li>How to think about performance, scale and reliability of big data systems?</li>
  <li>How do they remain available and not lose data despite frequent server and
hardware failures?</li>
  <li>How to reason about issues like security, privacy and data quality when
conducting analysis on large data sets?</li>
</ul>
{: .text-justify}

## Instructor
Sambit Sahu - ss3876@columbia.edu

OH: CEPSR (Schapiro Building) 7W51 Thursday 6:00pm-6:50pm

## TAs
[OH Calendar](https://calendar.google.com/calendar/u/0/embed?src=c_cd34b309dbe3126f513b87e9c29d50873242a639550137021c720fcf3909c267@group.calendar.google.com&ctz=America/New_York)

<table>
  <tr>
    <td>Mooizz Abdul - ma4496@columbia.edu</td>
    <td>Nipun Navin Agarwal - nna2132@columbia.edu</td>
  </tr>
  <tr>
    <td>Mohini Mangesh Bhave - mb5157@columbia.edu</td>
    <td>Samhit Chowdary Bhogavalli - sb4845@columbia.edu</td>
  </tr>
  <tr>
    <td>Ajit Sharma Kasturi - ak5055@columbia.edu</td>
  </tr>
</table> 

## Ed
[Link](https://edstem.org/us/courses/54718/discussion/)

## Prerequisites
Students are expected to have solid programming experience in Python or with an
equivalent programming language. This class is intended to be accessible for
data scientists who do not necessarily have a background in databases, operating
systems or distributed systems.

## Schedule (this is a work in progress, and is likely to change)
<table>
<colgroup>
<col width="33%" />
<col width="45%" />
<col width="22%" />
</colgroup>
<thead>
<tr class="header">
<th>Week</th>
<th>Topic</th>
<th>Homework</th>
</tr>
</thead>
<tbody>
<tr>
<td markdown="span">1</td>
<td markdown="span">Introduction (<a href="https://www.dropbox.com/scl/fi/mpj2twbm1l5dnfc6vvbau/Topic-1.pdf?rlkey=5r4m47yd0ivi6h3rzue0ui5o1&dl=0">Slides</a>)</td>
<th></th>
</tr>
<tr>
<td markdown="span">2</td>
<td markdown="span">Relational Data Model (<a href="https://www.dropbox.com/s/z1vvm34hhwq1csj/Topic%202%20-%20relational%20model.pdf?dl=0">Slides</a>)</td>
<th markdown="1">[Programming Homework 1 (to be released) (February 1st, 2024)]</th>
</tr>
<tr>
<td markdown="span">3</td>
<td markdown="span">Relational Data Model</td>
<th></th>
</tr>
<tr>
<td markdown="span">4</td>
<td markdown="span">Transactions and Logging (<a href="https://www.dropbox.com/s/oajai8bm781wiv0/Topic%203%20-%20transactions%20and%20ACID.pdf?dl=0">Slides</a>)</td>
<th></th>
</tr>
<tr>
<td markdown="span">5</td>
<td markdown="span">Storage/memory hierarchy (<a href="https://www.dropbox.com/s/aiy5rlmuz8xcpwd/Topic%204%20-%20single%20DB%20architecture.pdf?dl=0">Slides</a>)</td>
<th markdown="1">Written Homework 1 (to be released) (February 14, 2024) (On Gradescope)</th>
</tr>
<tr>
<td markdown="span">6</td>
<td markdown="span"> Indices and bloom filters</td>
<th markdown="1">Programming Homework 1 due (February 22, 2024 4:59:59PM)</th>
</tr>
<tr>
<td markdown="span">7</td>
<td markdown="span">Distributed file systems (<a href="https://www.dropbox.com/s/q3hloco1elfgek9/Topic%205%20-%20Distributed%20File%20Systems%20and%20Databases.pdf?dl=0">Slides</a>)</td>
<th markdown="1">Written Homework 1 due (March 6, 2022 4:59:59PM)</th>
<th></th>
</tr>
<tr>
<td markdown="span">8</td>
<td markdown="span">Midterm on 3/10 (all material up to Topic 4, not including RocksDB)</td>
<th></th>
</tr>
<tr>
<td markdown="span">9</td>
<td markdown="span">Spring Break</td>
<th></th>
</tr>
<tr>
<td markdown="span">10</td>
<td markdown="span">MapReduce and stragglers (<a href="https://www.dropbox.com/s/o5uwaa3fo8tv9ch/Topic%206%20-%20MapReduce%20and%20Spark.pdf?dl=0">Slides</a>)</td>
<th></th>
</tr>
<tr>
<td markdown="span">11</td>
<td markdown="span">Spark and distributed analytics</td>
<th></th>
</tr>
<tr>
<td markdown="span">12</td>
<td markdown="span">Caching (<a href="https://www.dropbox.com/s/5sggarpl2kx1oxn/Topic%207%20-%20Caching.pdf?dl=0">Slides</a>)</td>
<th markdown="1">[Programming Homework 2 (to be released) (Apr 4, 2024)]</th>
</tr>
<tr>
<td markdown="span">13</td>
<td markdown="span">Machine Learning (<a href="https://www.dropbox.com/s/ub35qceqpbo7c31/Topic%208%20-%20Systems%20for%20Machine%20Learning.pdf?dl=0">Slides</a>)</td>
<th></th>
</tr>
<tr>
<td markdown="span">14</td>
<td markdown="span">Security (<a href="https://www.dropbox.com/s/9rz9n9gvhw2iajq/Topic%209%20-%20Data%20Security%20and%20Compliance.pdf?dl=0">Slides</a>)</td>
<th markdown="1">Written Homework 2 (to be released) (April 18, 2023)</th>
</tr>
<tr>
<td markdown="span">15</td>
<td markdown="span">Data Quality and Review</td>
<th markdown="1">Programming Homework 2 due (April 25, 2024 4:59:59PM)</th>
</tr>
<tr>
<td markdown="span">16</td>
<td markdown="span"></td>
<th markdown="1">Written Homework 2 due (May 4, 2024 4:59:59PM, hard deadline May 7, 2023 4:59:59PM)</th>
</tr>
<tr>
<td markdown="span">17</td>
<td markdown="span">Final Exam (May 11, 2023)</td>
<th></th>
</tr>
</tbody>
</table>

## Grade Breakdown
20% Programming Homework 1 \\
10% Written Homework 1 \\
20% Programming Homework 2 \\
10% Written Homework 2 \\
15% Midterm \\
25% Final

## Late Submission Policy
Each student will have a total of 3 late days for the entire semester. After all
late days are used, there will be a 5% penalty for submission within 24 hrs of
the deadline, 10% penalty for submission within 48hrs of the deadline and 20%
penalty for submission within 72 hrs of the deadline. No submissions will be
accepted after 72 hrs from the deadline.

## Collaboration/Copying Policy
Programming assignment 1 and the written assignments will be done alone.
Programming assignment 2 will be done in pairs. You may not copy answers and
code. We will enforce this policy when checking the assignments (we use a code
similarity system).

## Course Materials
No textbook.

