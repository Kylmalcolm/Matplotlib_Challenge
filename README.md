<h1> Tumor Treatment Mouse Study in Python </h2>

In this project I used a variety of techniques in python to examine a mock-up mouse study of various drugs and their effectiveness. Visualizations were created using the matplotlib library.

<h2> Observations: </h2>

By reviewing the mean, median, variance, etc. in the treatment statistics, it's clear that a few of the treatments seem more effective than others. However, I would have some questions about the data. The timepoints adjust but the age of the mice does not - what are the units of the time points? This would be important to document. How did the errors with g989 occur and is it possible there were other errors that could have happened in a similar way?

![image](https://user-images.githubusercontent.com/70925750/112414568-3ee27400-8cf0-11eb-9d66-1dd966b83972.png)

Also, while we documented a never even split in male and female mice, it would be important to review treatment results grouped by gender to see if there is a difference. Granted this is a study on mice, but the significant differences in how men and women process the common sleep aide Ambien and how long it took to figure that out comes to mind.

In this study Capomulin and Ramicane seemed to be the most effective treatments with notable decreases in tumor volume and less variance in volume at the final time stamp. Both treatments seem worth exploring in an expanded mouse study or a trial with larger test subjects.

![image](https://user-images.githubusercontent.com/70925750/112414478-1e1a1e80-8cf0-11eb-9d7b-25101b243704.png)

Useful Resources:

https://datacarpentry.org/python-ecology-lesson/03-index-slice-subset/index.html

https://medium.com/@kvnamipara/a-better-visualisation-of-pie-charts-by-matplotlib-935b7667d77f
