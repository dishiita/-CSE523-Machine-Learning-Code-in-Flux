# CSE523-Machine-Learning-Code-in-Flux
Cricket is a very popular game it includes following types of players:
  1. Batsman
  2. Bowler 
  3. All Rounder
  4. Wicket keeper

Performance of a team depends highly upon performance of individual players and a player’s performance in each match depends on several parameters like location, past records, current form, average rate, strike rate (batsman), economy rate (bowler), number of innings, opposition team etc. So we are developing a model which could predict the best 11 players for that particular match.In this project we attempt to predict individual player’s performance in IPL, by analyzing their previous records through supervised learning and we rate every player’s performance through clustering.

Here are some screenshots of the output obtained:

  1. Clustering: K-means clustering 5 classes - 8, 8.5, 9, 9.5,10 ratings to the players
  
  Batsman Clustering:
  ![](Results/batsman_clustering.jpg)
  
  Bowler Clustering:
  ![](Results/bowler_clustering.jpg)
  
  Wicket keeper clustering:
  ![](Results/wicket_keeper_clustering.jpg)
  
  All rounder clustering:
  ![](Results/all_rounder_clustering.jpg)
  
  2. Classification: Random Forest classifier was used
  3. Regression: We basically worked on improving accuracy using Regression. For improving the accuracy, we have used Hyper Parameter Tunimg. Here is a comparison chart for the same:
  4. Linear Programming: To finally get an optimised team from the playing 2 teams, we have used Linear Programming: Here's the output for Linear Programming:

References:
1. Nilesh M. Patil, Bevan H. Sequeira, Neil N. Gonsalves and Abhishek A. Singh, “Cricket Team Prediction Using Machine Learning Techniques”, 
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3572740

2. Sonu Kumar and Sneha Roy, “Score Prediction and Player Classification Model in the Game of Cricket using Machine Learning”, International Journal of Scientific & Engineering Research, Volume 9, Issue 8, August-2018, ISSN 2229-5518,
https://www.ijser.org/researchpaper/Score-Prediction-and-Player-Classification-Model-in-the-Game-of-Cricket-Using-Machine-Learning.pdf

3. Nihal Patel and Mrudang Pandya, “IPL Player’s Performance Prediction”, International Journal of Computer Sciences and Engineering, Volume 7, Issue 5, May-2019, E-ISSN 2347-2693
https://www.ijcseonline.org/pdf_paper_view.php?paper_id=4268&

4. Kalpdrum Passi and Niravkumar Pandey, “Predicting Players’ Performance in One Day Internation Cricket Matches Using Machine Learning”, 
https://airccj.org/CSCP/vol8/csit88310.pdf

5. Madhav Goswami and Abhishek Anand, “Dream11 Team Predictor with Python and Machine Learning”,
https://medium.com/analytics-vidhya/dream11-team-predictor-with-python-and-machine-learning-f0dfce1489eb

6. L. Ajay, “Creating a Fantasy Cricket Team - Application of Linear Programming,” Medium, 10-Feb-2021 https://towardsdatascience.com/creating-a-fantasy-cricket-team-application-of-linear-programming-4b60c261702d. 

7. Dream11 Fantasy Points distribution system.
https://www.dream11.com/games/point-system
