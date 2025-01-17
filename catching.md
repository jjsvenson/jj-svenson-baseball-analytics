# My Catcher Evaluation Report

Using R as a tool and Trackman CSVs as my data, I was able to craft a report that analyzes catchers including aspects of throwing, pop time, accuracy, and framing.

## Project Description

When making my catcher evaluation report, I wanted to use R to read a Trackman CSV and make the catching data easily digestible. Trackman gives us data on pitch location, pitch call, throw speed, pop time, exchange time, time to base, and throw location. Using these measurements, we are able to analyze a catcher’s performance. My report formats this data in an understandable way, sorted by throws to each base. For each base, you are able to see the total throwing statistics, throwing statistics for pitches in the zone, throwing statistics for pitches out of the zone, and throwing statistics for whiffs. All of these data tables are sorted by pitch type. Each base also has an accuracy plot that is sorted by pitch type. These accuracy plots are color coded by height, allowing the viewer to better visualize the accuracy of the throw. For each catcher there is also a framing plot which includes a scatter plot of pitch locations relative to the zone, color coded by strike/ball with different shapes corresponding to each pitch type. This helps visualize framing and a catcher’s ability to steal strikes on pitches outside the zone. Their receiving performance is also depicted by a heat map that illustrates strike percentage for pitches caught by the catcher without a swing. The regions of the heat map surrounding the zone extend 6 inches outside of the strike zone. This page also includes framing statistics such as strikes stolen, strikes lost, and framing runs saved.

### Catcher Evaluation
In this project, I created code in R to create a report analyzing pitch sequencing when given a Trackman CSV.

- [View The Project's Outputted PDF](https://github.com/jjsvenson/jj-svenson-baseball-analytics/blob/bdc781d213ea8bec210f8c67d3ed8baa0ad1dd73/Arizona%20Wildcats%20Catcher%20Evaluations.pdf)
- Technologies used: R and Trackman

[Home Page](index.md)

---

## Contact

I am always looking to improve my reports and to hear the opinions of others. If you have any questions or comments, feel free to connect with me at [svensonjj@gmail.com](mailto:svensonjj@gmail.com) or view my [LinkedIn](https://www.linkedin.com/in/john-jj-svenson/)!
