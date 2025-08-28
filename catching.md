# My Catcher Evaluation Report

Using R as a tool and Trackman CSVs as my data, I was able to craft a report that analyzes catchers including aspects of throwing, pop time, accuracy, and framing.

## Project Description

When making my catcher evaluation report, I wanted to use R to read Trackman data and make the catching data easily digestible. Trackman gives us data on pitch location, pitch type, throw speed, pop time, exchange time, time to base, and throw location. Using these measurements, we are able to analyze a catcher’s performance. My report formats this data in an understandable way, sorted by throws to each base. For each base, you are able to see the total throwing statistics, throwing statistics for pitches in the zone, throwing statistics for pitches out of the zone, and throwing statistics for whiffs. All of these data tables are sorted by pitch type. Each base also has an accuracy plot that is sorted by pitch type. These accuracy plots are color coded by height, allowing the viewer to better visualize the accuracy of the throw. For each catcher there is also a framing plot which includes a scatter plot of pitch locations relative to the zone, color coded by strike/ball with different shapes corresponding to each pitch type. This helps visualize framing and a catcher’s ability to steal strikes on pitches outside the zone. Their receiving performance is also depicted by a heat map that illustrates strike percentage for pitches caught by the catcher without a swing. The regions of the heat map surrounding the zone extend 6 inches outside of the strike zone. This page also includes framing statistics such as strikes stolen (and percentage), strikes lost (and percentage), framing runs saved, framing runs saved per 9 innings, and SL+ (Strikes Looking Plus). The SL+ is derived from my called strike probability model trained using a XGBoost in R. An SL+ of 100 means a catcher is getting the expected number of called strikes, 105 means they are getting 5% more strikes than expected, and so on. The framing pages include overall framing, framing to left handed hitters, and framing to right handed hitters. For better interpretability, statistics where I felt it would be useful for them to be compared to league averages are automatically color coded (on a blue to red scale where red is good for the catcher) based on the rolling NCAA average and standard deviation for each statistic (SL+ is color coded based on the 100 scale). The following output was made with data from the Iowa 2025 baseball season but my code works with any Trackman csv!

### Catcher Evaluation
In this project, I wrote code in R to output a report analyzing a catcher's performance when given Trackman data.

- [View The Project's Outputted PDF](https://github.com/jjsvenson/jj-svenson-baseball-analytics/blob/658b4c5a1228be516bae70c8ca3a26f37d7cdc54/Iowa%202025%20Catcher%20Evaluations.pdf)
- Technologies used: R and Trackman

[Home Page](index.md)

---

## Contact

I am always looking to improve my reports and to hear the opinions of others. If you have any questions or comments, feel free to connect with me at [svensonjj@gmail.com](mailto:svensonjj@gmail.com) or view my [LinkedIn](https://www.linkedin.com/in/john-jj-svenson/)!
