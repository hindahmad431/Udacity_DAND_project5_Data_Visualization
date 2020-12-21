# Exploration project on Student Assessment Data (PISA 2012)

## by Hind Baageel

<img src='assessments-by-design.jpg' />

## Dataset

> In this project, we used a dataset called PISA-2012. PISA is a survey of students' skills and knowledge along with other features. It is not a
conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school. Original dataset contains 510,000 students with 635 features. The dataset was modified to include only 50 features to simplfiy the exploration task in this project. 
ion.


## Summary of Findings

> The Following Results were found after data exploration: 

- Student count comes from grade 10 is the highest followed by grade 9 then grade 11

- Female students in this dataset is slightly higher than the male students.

- More than the half of the particpants mothers completed ISCED level 3A. On the other hand, only 3.4% of particpants mothers didn't complete ISCED level 1.

- Most students final score falls around 10 to 14

- The student that have never came late has scored better on average. However, the students who came late one or two times have higher third quartile range than the others.

- At first glance, we can say that there is a negative relationship between hours of study at home with parents and the final student weight, but there is an exception at 30 hours per week where student weight have increased sharply

- Students that have stay at home mothers or with part time job score better on average than student that have mothers working full time job or other reasons

- Surprisingly, we can see that students with higher math anxity scores better at final student weight than those who don't even with they attend math clubs. Students who never or often join math club and don't have math anxity performed the worst among others.

- Higher number of classes per week has resulted in better math results even though the average final student scores falls at the same level as other students with lower classes per week

- In case teachers encouraged thinking and reasoning while student owns the required text books, the student achieved better scores on average.


## Visulization Improvment Steps
> To polish the presentation, I have removed the initial figures with design mistakes. For example, the initial figure of the categories of Student's mother highest education was full 
of unneccessary colors and it is was shown in unordered way. By sticking only to one color and adding labels to each bars and ordering them, finally we had a better figure to represent different categories. 

> Secondly, in most figures we tried to minimize x axis range or y axis range to remove extreme outliers that can shift the figures and make them unreadable. 

## Key Insights for Presentation
> The first key insight of this presentation that mother state can affect student results. The second key insight that having more classes per week can increase student performance in math tests.
The Third key insight is that students who comes late score lower on average which suggest that arriving at class time might increase student performance. 

## Submitted Files: 

At the end of this project, 5 files were submitted: 

exploration_template.ipynb : This is the main exploration notebook file that we used to explore the dataset to discover useful insights. 

slide_deck_template1.ipynb : This is a juptyer notebook file that we used to communicate our finding in clear and organized manner. 

slide_deck_template1.slides.html: This is the output file to communicate our finding. It is and html file and runs as a slide show. 

output_toggle.tpl: This template file can be used with nbconvert to export slide deck. This adds extra functionality to the slide deck by hiding the code to start, only making it visible if the reader clicks on the output (which should mostly be visualizations in the case of this project). It was taken from this page [this page](https://github.com/damianavila/blog/blob/master/posts/hide-the-input-cells-from-your-ipython-slides.ipynb)

pisa2012_modified.csv: The modified PISA-2012 dataset with only 52 features. 
