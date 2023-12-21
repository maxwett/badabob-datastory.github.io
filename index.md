---
layout: page
title: "Hollywood Unveiled"
cover-img: images/women-collage.png
---
### Rewriting Women’s Stories on the Silver Screen 

The perception and role of women in the US society has greatly evolved during the past century with women being granted a myriad of new rights. Simultaneously, their perception has also evolved, shifting away from mere housewives. Movies are often seen as a reflection of society, moving along with its ebbs and flows. But has this specific social movement bled into the entertainment industry? Has the depiction of women progressed alongside important milestones in the Feminist movement? Or on the contrary, do stereotypes around women still prevail in Hollywood?

This data story will explore the CMU Movie Summary Corpus (add hyperlink) to explore how women are portrayed in Hollywood. Not only by mere representation but whether women are now being put at the forefront of storylines. It will also dive deeper into the characteristics of stereotypical movies.
As a first step into this it is logical to wonder about the representation of women through time. The proportion of actresses over time gives us a first insight into how well the industry is representing society.  According to Martha Lauzen from the San Diego State’s Center for the Study of Women in Television and Film, “Despite the major disruptions in the film business over the last couple of years, onscreen gender ratios have remained relatively stable.”(add ref) But what about going back 100 years, has society progressed at all ?

<object>
  <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="700" height="550" src="html_plots/proportion_men_women.html"></iframe>
</object>

As we can see the ratios have remained fairly constant over time,  hitting a proportion of women between 30% and 40%, close to a 2 to 1 ratio. However we can see a small but interesting trend starting in the 70s, with the proportion of women slowly but steadily increasing. If the industry keeps evolving at this rate, by fitting a regression through this time period, we could naively say that parity would be reached in 2064. This of course only reflects a thought experiment that helps us understand the overall trend. But can this trend be explained by any significant event in history ? In fact two major events for women's rights in the US occurred in the 60s: the Equal Pay Act and the Civil Rights Act. The Equal Pay Act prohibits a difference of salary based on sex while the Civil Rights Act prohibits (amongst others) employment discrimination based on sex. These two events were a huge step towards gender equality and they might have prompted a change in mentality, resulting in the proportion of women in movies increasing.

Nevertheless, this result doesn't mean that each movie has approximately 30-40% of women in their actors cast. This result might be biased by movies that have an extremely low/high proportion of women versus movies that have a balanced actors cast.

<object>
  <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="700" height="550" src="html_plots/movie_proportions.html"></iframe>
</object>

This is in fact what we see with the plot above. Indeed over 85% of movies have less than 50% of actresses  in their cast. So while we may think from the plot before that women represent 40% of characters in movies, this plot demystifies this idea. Nonetheless, from 2000 onwards there is a growing number of movies with a majority of women actors in their cast. Breaking this down further by genre we can look more precisely at the individual trends. 

<object>
  <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="700" height="550" src="html_plots/movie_proportions_percentages_actress_by_genre.html"></iframe>
</object>

Interestingly, three genres stick out as much worse than the average: Action, Western and Drama. In those genres, over 50% of movies that have less than 25% of women in them. On the contrary, three genres seem to do slightly better than the average namely Musical, Adventure and Horror. This shows that all genres aren’t equal when it comes to women representation. 
TIME magazine in 2015 reported that “male actors see their careers peak at the age of 46, female actors reach their professional pinnacles at age 30” (add ref). According to this, there is therefore not only a gap in representation but also in the age of actors versus actresses. This can in fact be seen very well in this plot: 

<object>
  <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="700" height="550" src="html_plots/Average_age_actor.html"></iframe>
</object>

On average, female actors are **significantly** younger than men at any point throughout the last century. This clearly emphasises the age gap in the industry. Moreover, the average age of actors increases over time regardless of gender, potentially reflecting the long career span of actors. As a matter of fact, an actor starting in the 60s might be playing well into the 80s. But throughout this maturing of the industry, the age gap does not get smaller. This next animation we clearly see the exact breakdown of actors and actresses throughout the decades. TO ADD: more analysis here (Distributions are skewed towards the left and heavy tailed)

<object>
  <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="700" height="550" src="html_plots/age_distribution_plot.html"></iframe>
</object>


Now all of this does not tell us in any way **how** women are portrayed in these movies. We've seen that women's representation is increasing but what kind of representation ? Having a women lead is much more meaningful than adding only female secondary characters. It is therefore crucial to be able to differentiate the two. 

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="700" height="550" src="html_plots/main_char_ratio.html"></iframe>

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width="700" height="550" src="html_plots/proportion_main_characters_per_genre.html"></iframe>


### Clustering to classify stereotypical vs non-stereotypical movies.
### Ratio of stereotypical vs non-stereotypical movies through time.
### Which genres display a strong difference in prevalence in stereotypical vs non-stereotypical movies.
### Vocabulary associated with female characters through time.

### [TEMPORARY]Testing dropdown menus

<iframe src="test_plot.html" width="100%" height="400px"></iframe>

