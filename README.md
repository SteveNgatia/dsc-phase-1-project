<span style="color: black; font-size: 24px;">**The movie production industry has spooked Microsoft's curiosity**</span>  

Well..., let's give them some insights of the industry..  



<span style="color: black; font-size:20px;">**Business Case**</span>  

Microsoft is interested in venturing in the movie production business but they do not have business analysis to help them make informed decisions as to which movies to produce.  


<span style="color: black; font-size:20px;">**Data Source**</span> 

We have data from imdb and is contained in three files:  
  imdb.title.basics - contains data about the movies names and genres  
  imdb.title.ratings - contains data about the movie ratings  
  bom.movie_gross - contains data about the gross revenues associated with the movies.  
  
<span style="color: black; font-size:20px;">**Analytical Questions**</span> 

1. Which is the most produced genre in the industry?
2. Which is the genre with the highest and least gross revenue?
3. Which is the genre with the least gross revenue?
4. How is the revenue performance for the top produced genres?
5. How is the revenue performance trend for the top revenue generaters over the years?
6. How is the relationship between rating and gross revenue?  

<span style="color: black; font-size:20px;">**Methodology**</span> 

We use descriptive statistics, trends and use visualizations to analyse our data and draw conclusions.  


<span style="color: black; font-size:20px;">**Results**</span> 

<span style="color: black; font-size:16px;">**Which is the most produced genre in the industry?**</span> 

![image-2.png](attachment:image-2.png)  

<span style="color: black; font-size:16px;">**Most produced genre**</span> 

The top 3 produced genres are:-
* Drama  
* Documentary  
* Comedy,Drama,Romance  

It is important to look at how these genres rank in relation to gross revenue.  

* Drama - 4th   
* Documentary - 6th   
* Comedy,Drama,Romance - 11th   

Rank in relation to average rating  

* Drama - 17th   
* Documentary - 16th   
* Comedy,Drama,Romance - 14th  

Given the foregoing ranking, it is not clear why these genres are the most produced.  

<span style="color: black; font-size:16px;">**Which is the genre with the highest and least gross revenue?**</span>  

![image.png](attachment:image.png)  

<span style="color: black; font-size:16px;">**Top Revenue Generaters**</span> 

The top 3 revenue generating genres are:-
* Action,Adventure,Sci-Fi  
* Adventure,Animation,Comedy  
* Action,Adventure,Fantasy  

How do they rank in relation to average rating?  

* Action,Adventure,Sci-Fi  - 5th 
* Adventure,Animation,Comedy  - 2nd
* Action,Adventure,Fantasy  - 4th  

How about rank in relation to production frequency?  

* Action,Adventure,Sci-Fi  - 10th 
* Adventure,Animation,Comedy  - 7th
* Action,Adventure,Fantasy  - 25th  

The top revenue generating movies are highly rated by viewers and are in the top 5 ranking by viewrs. 

<span style="color: black; font-size:16px;">**Bottom 3 Revenue Generating Genres**</span>
* Drama,War,Western  
* Documentary,History,Thriller  
* Action,Horror  

<span style="color: black; font-size:16px;">**How is the revenue performance for the top produced genres?**</span>  

![image-2.png](attachment:image-2.png)  

* Drama - Ranked 4th in the revenue generating table   
* Documentary - Ranked 6th in the revenue generating table   
* Comedy,Drama,Romance - Ranked 11th in the revenue generating table 

Although they're not in the top three ranking, they still rank in the top ten except Comedy,Drama,Romance. 

<span style="color: black; font-size:16px;">**How is the revenue performance trend for the top revenue generaters over the years?**</span>  

![image-4.png](attachment:image-4.png)  

We see a sawtooth pattern year on year for all the top 5 genres. Between 2010 and 2016, Action,Adventure,Sci-Fi and Adventure,Animation,Comedy have dominated the rest of the top 5 year on year. 
From 2016 moving to 2018 the counters closed on a downward trend except Drama which had a slight upward trend. Notably,Action,Adventure had a huge upward surge to close the highest among the top 5.  

<span style="color: black; font-size:16px;">**How is the relationship between rating and gross revenue?**</span> 

![image-3.png](attachment:image-3.png)  

There seems to be a dense population above the mean of 6.458543. Interestingly, the revenues around this dense polulation is not big as we would expect. However, it is also certain that the top revenue generaters are also distributed around the mean.  


<span style="color: black; font-size:20px;">**Conclusions**</span>  

The top 3 produced genres have no relationship with the rating.  
Although the're not the top ranked in revenue generation, they still rank in the top 11.  

The top 3 ranked genres in revenue generation have high ratings but not highly rated in terms of production frequency. 

<span style="color: black; font-size:20px;">**Recomendations**</span> 

Produce movies ranked highly in gross revenue ranking.  
Do not produce the most prduced genre in the industry as it does not correlate with gross revenue.
When deciding to produce movies based on rating, make sure to choose highly rated movies which are highly ranked in the gross revenue ranking.  

<span style="color: black; font-size:20px;">**Further Reviews**</span> 

Additional data is required inorder to analyse the profit generated by these movies.

During data clean-up after the merging process, we lost a lot of data due to null values occassioned by missing data. I would be important to get data with minimal missing data so as to have a larger sample to carry out our analysis.  

Perform further analysis on how the number of voters correlate with the average rating.


```python

```
