Assignment Documentation:

2 places of manipulation:

     Variables and number of clusters

My process was to jump between these two sections until I didn't see any outlier images in a cluster. 

While I manipulated the variables I referenced the elbow plot to evaluate the impact of different variables. 
I found that using things like artist or title were effective in making the elbow plot sharper, but the clusters
seemed to make less sense. I focused on using 
attributes like, area, point, and line. 

When it came to the sillhouette plots I picked each initial plot that didn't fall under the average and tested the 
values around those. I repeated this pattern until I would reach a sillhouette plot that had shapes of similar length.  

After picking the number of clusters I would scroll through the images quickly to see if there were any obvious outlying
images. I would do a second, slower pass, to see if each cluster made sense. 

I recognized a pattern with a number of images that seemed out of place. I made guesses as to why they were placed where
they were, and adjusted the variables accordingly. 

The biggest impact was removing lines(li) from the variables. I found that lines were evaluated as anything from
the shape of a persons body, and optical illusion, or a string in an installation. Removing this made each cluster
significantly more cohesive and the images that kept seeming out of place didn't stick out as much. 