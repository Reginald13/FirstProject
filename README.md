![Movie Industry](https://cloudblogs.microsoft.com/industry-blog/wp-content/uploads/2017/07/17300_MSFT_CDSACustomerStoryMiBBlog_embedded1_r1_v3.jpg)

# Microsoft Movie Industry Analysis

## Business problem:

Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They have decided to create a new movie studio, and they have seeked help from SeaNa data consulting to help them better understand the movie industry. Our team was charged with doing data analysis and creating a presentation that explores what type of films are currently doing the best at the box office and translating findings into actionable insights that the CEO can use when deciding what type of films they should be creating.

#### Questions of interest:

1. What are the most successful genres by revenue?
2. What are the most successful genres by ROI?
3. What are the most popular movie genres?
4. Do higher IMDB ratings lead to higher movie revenues?
5. Have high grossing movies automatically a higher ROI?
6. Who are the best directors to partner with in winning genres?
7. What are the common runtimes by genre?
8. Which studio should Microsoft partner with?

## Data

This analysis leveraged movie data merged from 4 different SQL databases:
* Box Office Mojo
* IMDB
* Rotten Tomatoes
* TheMovieDB.org


## Findings & Recommendations

Please refer to the [Presentation Jupyter Notebook](./Presentation notebook.ipynb) in this repository for a walkthrough and more explanation of these findings.

 1. The most successfull movie genres by revenue, ROI and ratings contain a "Horror" element, so Microsoft should target that segement for first their first movie
 2. Higher IMDB ratings seem to not necessarily lead to higher movie revenues
 3. High grossing movies seem to have a higher ROI, Microsoft should not neccesarly get fixated on creating high ratings movie but should rather focus on creating a high grossing movie
 4. We recomend Microsoft partner with Directors with high ROI. We were able to identify only one director ([Tod Williams](https://www.imdb.com/name/nm0931095/)) with a high ROI and also a high IMDB ratings.
 5. Average runtime of successful movies have been between 80 mins and 130 mins. Target runtime for new movie should be within this range
 

## Limitations & Next Steps

- Data was limited to 2010 - 2012
- Analysis mostly examined 2012 movie performance
- Other relevant colaborators (actos and writers) to be identified in next phase of work


### Contact

For any additional questions, please reach out to Reginald and Adebodun  ![Data Science Program](https://miro.medium.com/max/4080/1*U3WRRwLx3zeDkHmIVGLJdw.gif)


![Movie Industry](https://cloudblogs.microsoft.com/industry-blog/wp-content/uploads/2017/07/17300_MSFT_CDSACustomerStoryMiBBlog_embedded1_r1_v3.jpg)
