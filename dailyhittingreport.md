# My Daily Hitting Report
Using R as a tool and Trackman CSVs as my data, I aimed to make a report that could be used daily to evaluate a team's hitters.

## Project Description
Working as a Baseball Analytics Intern for the Yarmouth-Dennis Red Sox of the Cape Cod Baseball League, I aimed to create a coded report in R that could be used on a day to day basis to evaluate a team's hitters. The report uses Trackman data to present statistics relating to a hitter's performance in terms of contact quality, contact rates based on pitch type/location as well as ball/strike count, general approach and swing decisions, and on-base metrics. It is also color coded based on league averages for better interpretability. I find the day to day use of this report useful because it not only shows you season-long performance, but also recent performance in terms of both a hitter's last 18 plate appearances and their most recent game. This is useful for indentifying long term season trends as well as how hitters have been performing recently. Formal definitions of the statistics are listed below:

#### Performance:
- **Bullet/Swing (tables sorted by descending Bullet/Swing)**
  - Bullets / Qualified Swings
  - Bullet = EV 90+ and Launch Angle 0-40º
  - Qualified Swings are all swings other than swings in 2 strike counts that resulted in foul balls
- **Squared-up EV**
  - Average EV on squared-up balls
  - Squared-up balls: balls in play that are of EV 85 mph or greater and between -5º and 40º of Launch Angle
- **Mis-Hit%**
  - (# Mis-Hits) / (# BIP)
  - Mis-Hit: BIP with launch angle < -10º or > 40º

#### Approach:
- **FB-Middle Sw%**
  - Swing% on FB's in the zone before 2 strikes
- **Chase%**
  - Chase zone is defined as at least 1.5 baseballs outside the zone in any direction

#### Contact:
- **IZ Miss%**
  - Whiff% on pitches in the zone
- **FB Miss%**
  - Whiff% on FBs
- **2K Fight%**
  - (# 2 strike fights) / (# 2 strike swings)
  - 2 strike fight: foul or ball in play with 2 strikes

#### On-Base:
- **BB%**
- **K%**


### Daily Hitting Report
In this project, I used R to code a report that could be used daily to evaluate a team's hitters using Trackman data.

Here is an example of the report using the Harwich Mariners of the Cape Cod Baseball League.
- [View The Project's Outputted PDF](https://github.com/jjsvenson/jj-svenson-baseball-analytics/blob/1e829623f8da770fb1312b8bd42f7236d5ab900d/Harwich%20Daily%20Hitting%20Report.pdf)
- Technologies used: R and Trackman

[Home Page](index.md)

---

## Contact
I am always looking to improve my reports and to hear the opinions of others. If you have any questions or comments, feel free to connect with me at [svensonjj@gmail.com](mailto:svensonjj@gmail.com) or view my [LinkedIn](https://www.linkedin.com/in/john-jj-svenson/)!
