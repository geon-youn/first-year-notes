---
alias: five-number summary, percentile, boxplot, lower fence, upper fence
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 12:20:08 
---
# 5-number summary and boxplots
**Five-number summary**: reports a distribution's [[centre|median]], quartiles, and extremes (max and min). 

It provides a good overall summary of the distribution of the data. 

**Percentiles**: shows where a given percentage of the data lies.
- Min = 0-percentile.
- Q1 = 25-percentile.
- Median = 50-percentile.
- Q3 = 75-percentile.
- Max = 100-percentile. 

Suppose there are 12 data values and we want the 80th percentile. 80% of 12 is 9.6, which is not an integer, so we *round it up* and the 80th percentile is the 10th data value. If we want the 50th percentile, 50% of 12 is 6, which is an integer so we take the average of the 6th and 7th data values. 

Once we have a five-number summary of a [[data value|variable]], we can display that information in a **boxplot**. To make a boxplot:
1. Draw a single vertical axis spanning the extent of the data.
2. Draw short horizontal lines at the lower and upper quartiles and at the median, then connect them with vertical lines to form a box. 
![[Pasted image 20220313122918.png]]
3. Draw "fences" around the main part of the data, placing the upper fence `1.5 IQR`s above the upper quartile and the lower fence `1.5 IQR`s below the lower quartile.

**Lower fence**: `Q1-1.5*IQR`
**Upper fence**: `Q3+1.5*IQR`

![[Pasted image 20220313122905.png]]

4. Draw lines (whiskers) from each end of the box up and down the two the most extreme data values found *within* the fences.
![[Pasted image 20220313122855.png]]

5. Add any outliers by displaying data values that lie beyond the fences with special symbols. Erase the fences. 

![[Pasted image 20220313122845.png]]

The **centre** of a boxplot shows the middle half of the data between the quartiles. 

The height of the box equals the IQR. 

If the median is rougly centred between the quartiles, then the middle half of the data is rougly symmetric. If it is not centred, then the distribution is skewed. 

The whiskers show skewness as well if they're not rougly the same length.

The outliers are displayed individually to keep them out of the way in judging skewness and to display them for special attention. 
