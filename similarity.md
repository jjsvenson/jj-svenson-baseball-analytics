# My Pitch Similarity Report

Using R as a tool and Trackman CSVs as my data, I was able to craft a report that analyzes the results of all NCAA pitches with similar shape/metrics to a target pitcher's pitches.

## Project Description

This report was created with the goal of evaluating a pitcher and how his stuff performs across NCAA baseball. The report includes a table for each pitch type a pitcher throws, split by batter handedness, detailing the results of all pitches within +/- 1.5 inches of induced vertical break (IVB) and horizontal break (HB), +/- 1 mph of velocity, and +/- 3 inches of release height and release side (release point metrics). The tables include counts (# of pitches), swing %, swing % for pitches in the zone, whiff %, whiff % for pitches in the zone, chase %, swinging strike %, called strike + whiff (CSW) %, ball in play %, out % for balls in play, ground ball %, line drive %, fly ball %, pop up %, bullet % for balls in play (where a bullet is defined as any ball in play between 0º and 35º of launch angle with an exit velocity of 90 mph or more), average exit velocity, and average launch angle. For better interpretability, statistics where I felt it would be useful for them to be compared to league averages are automatically color coded (on a red to green scale where green is good for the pitcher) based on the rolling NCAA average and standard deviation for each statistic. The color scales are different for each pitch type because, for example, league average whiff% for a fastball is lower than league average whiff% for a slider. Therefore, each pitch type is color coded based on its custom scale. The attached report includes all of the data from the 2025 Iowa baseball season but the code can be used to analyze any Trackman data.

### Pitch Similarity Analysis
In this project, I created code in R to create a report analyzing the results of all NCAA pitches of similar shape/metrics to a target pitcher’s pitches when given a Trackman CSV.

- [View the Project's Outputted PDF](https://github.com/jjsvenson/jj-svenson-baseball-analytics/blob/be5b353986f1dc01993b822c14501c5455507e6e/Iowa%202025%20Similarity%20Report.pdf)
- Technologies used: R and Trackman

[Home Page](index.md)

---

## Contact

I am always looking to improve my reports and to hear the opinions of others. If you have any questions or comments, feel free to connect with me at [svensonjj@gmail.com](mailto:svensonjj@gmail.com) or view my [LinkedIn](https://www.linkedin.com/in/john-jj-svenson/)!
