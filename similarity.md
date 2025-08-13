# My Pitch Similarity Report

Using R as a tool and Trackman CSVs as my data, I was able to craft a report that analyzes the results of all NCAA pitches with similar shape/metrics to a target pitcher's pitches.

## Project Description

This report was created with the goal of evaluating a pitcher and how his stuff performs across NCAA baseball. The report includes a table for each pitch type a pitcher throws, split by batter handedness, detailing the results of all pitches within +/- 1.5 inches of induced vertical break (IVB) and horizontal break (HB), +/- 1 mph of velocity, and +/- 3 inches of release height and release side (release point metrics). The tables include counts (# of pitches), 

pitch metrics including velocity, spin, extension, break, tilt, VAA (adjusted to be in different parts of the zone depending on the pitch type), release point, and an arm angle approximation based on the pitcher's height and their release point), and results. It also includes a pitch movement plot (with arm angles), a release point plot, and general location plots and whiff specific plots split by pitch type. The attached report includes all of the data from the 2025 Iowa baseball season but the code can be used to analyze any Trackman data.

### Pitcher Evaluation Analysis
In this project, I wrote code in R to create a report analyzing a pitcher and their stuff when given a Trackman CSV.

- [View the Project's Outputted PDF](https://github.com/jjsvenson/jj-svenson-baseball-analytics/blob/42d9660e7880d8b250d6dc44f970c38a32696731/Iowa%202025%20Pitcher%20Evaluations.pdf)
- Technologies used: R and Trackman

[Home Page](index.md)

---

## Contact

I am always looking to improve my reports and to hear the opinions of others. If you have any questions or comments, feel free to connect with me at [svensonjj@gmail.com](mailto:svensonjj@gmail.com) or view my [LinkedIn](https://www.linkedin.com/in/john-jj-svenson/)!
