Download Link: https://assignmentchef.com/product/solved-data621-project-i
<br>



<h1>Abstract</h1>

To see how regression will help us evaluate baseball team performance, we will explore, analyze and model a historical baseball data set containing approximately 2200 records, to determine a team’s performance based on statistics of their performance. Each record represents a professional baseball team from the years 1871 to 2006 inclusive, and the data include the performance of the team for the given year, with all of the statistics adjusted to match the performance of a 162 game season.

While correlation does not equal causation it is suggested that a focus on some of the variables such as a focus on either single hits or triple or more hits to the exclusion of doubles might be worth pursuing. Also the data suggests that a focus on home runs allowed may not be worth giving up a number of more normal hits.

…..To add more here….

<h1>Introduction</h1>

Because baseball is so numbers-heavy, there are many different statistics to consider when searching for the best predictors of team success. There are offensive statistics (offense meaning when a team is batting) and defensive statistics (defense meaning when a team is in the field). These categories can be broken up into many more subcategories. However, for the purpose of the this project we will use the available data to build a multiple linear regression model on the training data to predict the number of wins for the team.

<h1>Data Used</h1>

<table width="617">

 <tbody>

  <tr>

   <td width="458">VARIABLE NAME                          DEFINITION</td>

   <td width="159">THEORETICAL EFFECT</td>

  </tr>

  <tr>

   <td width="458">INDEX                                               Identification Variable (do not use)</td>

   <td width="159">None</td>

  </tr>

  <tr>

   <td width="458">TARGET_WINS                           Number of wins</td>

   <td width="159">Outcome Variable</td>

  </tr>

  <tr>

   <td width="458">TEAM_BATTING_H                       Base Hits by batters (1B,2B,3B,HR)</td>

   <td width="159">Positive Impact on Wins</td>

  </tr>

  <tr>

   <td width="458">TEAM_BATTING_2B Doubles by batters (2B)</td>

   <td width="159">Positive Impact on Wins</td>

  </tr>

  <tr>

   <td width="458">TEAM_BATTING_3B Triples by batters (3B)</td>

   <td width="159">Positive Impact on Wins</td>

  </tr>

  <tr>

   <td width="458">TEAM_BATTING_HR Homeruns by batters (4B)</td>

   <td width="159">Positive Impact on Wins</td>

  </tr>

  <tr>

   <td width="458">TEAM_BATTING_BB Walks by batters</td>

   <td width="159">Positive Impact on Wins</td>

  </tr>

  <tr>

   <td width="458">TEAM_BATTING_HBPBatters hit by pitch (get a free base)</td>

   <td width="159">Positive Impact on Wins</td>

  </tr>

  <tr>

   <td width="458">TEAM_BATTING_SO Strikeouts by batters</td>

   <td width="159">Negative Impact on Wins</td>

  </tr>

  <tr>

   <td width="458">TEAM_BASERUN_SB Stolen bases</td>

   <td width="159">Positive Impact on Wins</td>

  </tr>

 </tbody>

</table>

the data was provided in csv file. The files contain approximately 2200 records. Each record represents a professional baseball team from the years 1871 to 2006 inclusive. Each record has the performance of the team for the given year, with all of the statistics adjusted to match the performance of a 162 game season.

1

<table width="640">

 <tbody>

  <tr>

   <td width="458">VARIABLE NAME                          DEFINITION</td>

   <td width="182">THEORETICAL EFFECT</td>

  </tr>

  <tr>

   <td width="458">TEAM_BASERUN_CS Caught stealing</td>

   <td width="182">Negative Impact on Wins</td>

  </tr>

  <tr>

   <td width="458">TEAM_FIELDING_E                   Errors</td>

   <td width="182">Negative Impact on Wins</td>

  </tr>

  <tr>

   <td width="458">TEAM_FIELDING_DP Double Plays</td>

   <td width="182">Positive Impact on Wins</td>

  </tr>

  <tr>

   <td width="458">TEAM_PITCHING_BBWalks allowed</td>

   <td width="182">Negative Impact on Wins</td>

  </tr>

  <tr>

   <td width="458">TEAM_PITCHING_H Hits allowed</td>

   <td width="182">Negative Impact on Wins</td>

  </tr>

  <tr>

   <td width="458">TEAM_PITCHING_HRHomeruns allowed</td>

   <td width="182">Negative Impact on Wins</td>

  </tr>

  <tr>

   <td width="458">TEAM_PITCHING_SO Strikeouts by pitchers</td>

   <td width="182">Positive Impact on Wins</td>

  </tr>

 </tbody>

</table>

<h1>Data exploration</h1>

<strong>Variable Selection</strong>

<strong>Outliers</strong>

<strong>Correlations among predictors</strong>

<strong>Data Preparation</strong>

<strong>Build Models</strong>

<strong>Select Model</strong>

<strong>Appendix</strong>


