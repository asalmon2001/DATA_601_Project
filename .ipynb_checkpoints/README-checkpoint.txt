DATE: 2023-09-27
PROJECT NAME: DATA 601 Project
AUTHOR: Alister Salmon

DESCRIPTION: 
See project proposal for entire project outline.

This repository is my section of the project. I will be answering the following question:
"How has the ratio between building permit types changed through the decades?"

The dataset I will be using is: Building Permits from Calgary Open Data
https://data.calgary.ca/Business-and-Economic-Activity/Building-Permits/c2es-76ed/


23/10/05
My initial plan: filter all permits by permit class. However, I encounted a problem where some permit classes include both new buildings and improvements.
New plan: first, I will grab all the demolision permits and throw those in a .csv. Next, I will grab all the improvements and throw those in a .csv. This will all be done with the WorkClassGroup column. With the remaining "New" WorkClassGroup, we will filter for "residential" and "non-residential". Then we will see what we are working with.
I am also going to pre-emptively filter by half-decades