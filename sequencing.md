# My Pitch Sequencing Report

Using R as a tool and Trackman CSVs as my data, I was able to craft a report that analyzes pitch sequencing.

## Project Description

When making my pitch sequencing report, my goal was to investigate how pitchers’ different pitch types performed following a specific pitch type. I was interested in calculating usage %, strike %, swing %, swing % for pitches in the zone, whiff %, whiff % for pitches in the zone, chase %, swinging strike %, called strike + whiff (CSW) %, ball in play %, out % on balls in play, ground ball %, line drive %, fly ball%, pop up %, and average exit velocity. To do this I used variables in a Trackman CSV and wrote functions in R to calculate these statistics. This included defining the strike zone based on the spatial axes Trackman uses. My code filters the data so that I can analyze, for example, all pitches after a fastball for a certain pitcher. I then put all of these statistics in a table, sorted by pitch type. My report includes one page per pitcher, and one table for each pitch type to show the results of pitches following that pitch type. However, because I was focused on pitch sequencing, I did not count the first pitch of an at bat as following the last pitch of the previous at bat because that does not help analyze pitch sequencing. The data only includes pitches that followed a certain pitch within the same at bat. Statistics where I felt it would be useful for them to be compared to league averages are automatically color coded based on the rolling NCAA average and standard deviation for each statistic. This report includes all of the data from the 2025 Arizona baseball season but the code can be used to analyze any Trackman data.

### Pitch Sequencing Analysis
In this project, I created code in R to create a report analyzing pitch sequencing when given a Trackman CSV.

- [View the Project's Outputted PDF](https://github.com/jjsvenson/jj-svenson-baseball-analytics/blob/6d52ec99b18b91dad9d6e2813f8733d169efa4c3/Arizona%20Wildcats%20Pitch%20Sequencing%20Report.pdf)
- Technologies used: R and Trackman

[Home Page](index.md)

---

## Contact

I am always looking to improve my reports and to hear the opinions of others. If you have any questions or comments, feel free to connect with me at [svensonjj@gmail.com](mailto:svensonjj@gmail.com) or view my [LinkedIn](https://www.linkedin.com/in/john-jj-svenson/)!
