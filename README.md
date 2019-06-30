# Hollywood-Black-List-Analysis
The Hollywood Black List is a list of movie scripts that is compiled annually and voted on by elite movie producers and directors. 

Hollywood Black List Analysis
In 2005 Franklin Leonard surveyed almost 100 film industry development executives about their favorite scripts from that year that had not been made as feature films. Since then the voter pool has grown to 500 film executives, 60% of whom typically respond.

Over 300 Black List screenplays have been made as feature films. Those films have earned over $26 billion in worldwide box office, have been nominated for 264 Academy Awards, and have won 48, including Best Pictures SLUMDOG MILLIONAIRE, THE KING'S SPEECH, ARGO and SPOTLIGHT, and ten of the last twenty screenwriting Oscars.

Scope of Work
Objectives:

1. Create year comparisons based on information about financing, gender, and genre.

2. Run for loops that search descriptions for specific words in order to group all movie titles by category.

3. Analyze percentage of movies by category from data set with genres included.
Methods:

1. Scrape data from the annual Black List websites. Transpose data in sheets and create a Sqlite database of all years of data.

2. Complete exploration of data in SQL, Python, and Tableau.

3.Create for loop functions to search movie descriptions to identify percentages of movie titles associated with specific genres.

4. Use Scikit_learn topic modeling functions to cluster popular words in Python. Compare how many of the cluster words it would take to account for a higher percentage of movie titles than the words we initially used to categorize movie
titles. 
Summary of Analysis
81% of screenwriters whose scripts made the black list are men.

Since 2015 the amount of female screenwriters have doubled to 33% of the total scripts in the Black List. If this trend continues for the next 5 years we can expect equal gender representation of scripts in the black list.

When searched the word 'man' appears in 13.73% of script descriptions. 'Woman' appears in only 7.49% of script descriptions.

The percentage of scripts with financing that made the black list has been declining since 2014. This may signify that the black list is returning to it's original purpose of bringing light to great scripts that might otherwise go unnoticed.

We intially searched 42 words in the script descriptions in an attempt to account for all of the movie titles in the list. We were only able to account for 68% of script titles with those words.

-human words- (love, relationship, friendship, friend, romance, romantic, true, biopic, biographical, kidnapped, murder, murdered, death, spy, spies, killer, serial killer, assassin, prison, imprisonment, cop, cops, police, torture, revenge, vengeance, war, civilian, soldier, comedy, romcom, funny, bank, rob, heist, mob, robot, future, space, alien.)

We used a cluster modeling function to identify popular topics among the movie descriptions. Through clustering Python was able to identify 11 words that when searched in our original search function were able to account for a higher percentage of script titles than our 42 words. The short list of cluster words accounted for 70% of script titles.
-Python words- (life, old, young, year, man, story, true, based, world, war, family)
