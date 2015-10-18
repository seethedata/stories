+++
date = "2015-10-16T21:29:31-04:00"
draft = false
title = "Health System"
+++

For a hospital, readmission of a patient for the same issue is one of the worst things that can happen. That's because insurance payments will be refused and the hospital will be penalized financially.

We had a hospital system out West that was highly focused on reducing their readmission rates and had been trying to find the underlying cause (if any). They did extensive analysis of each of their departments like gastroenterology, cardiology, oncology, etc. After struggling with this issue for a while, we were brought in to tackle the problem.

Looking at the data collected, as well as the analyses previously done by the hospital, there didn't seem to be any common thread. And, indeed, when our data sciences began running their own analysis, they did not find any specific correlations to an increase in readmissions. As the data scientists continued to iterate their models, they eventually found the element that was causing the readmissions. The key was looking at patients who visited no less than two different departments during their stay. 

When presented with this insight, the hospital began to investigate its internal processes that involved transfer of patients between departments. It turns out that these were not particularly structured or repeatable processes and there were few checks in place to assure correctness. 

Once a more formalized system for patient transfer was implemented, the readmission rates dropped significantly.

-----------------