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
  
  ![imgonline-com-ua-resize-pvKMn3VQ1cPAKl (1)](https://user-images.githubusercontent.com/54388663/114297007-e53dc000-9acb-11eb-8ffe-c2293d034c06.jpg)

  Bowler Clustering:
  
  ![imgonline-com-ua-resize-fhXeeGKKtR6JyOb](https://user-images.githubusercontent.com/54388663/114296799-dacef680-9aca-11eb-9d9b-7efe9f2bd2af.jpg)
  
  Wicket keeper clustering:
  
  ![wicket_keeper_clustering](https://user-images.githubusercontent.com/54388663/114295752-e5868d00-9ac4-11eb-899a-8923169b3696.png)
  
  All rounder clustering:

  ![imgonline-com-ua-resize-qItpFkmoEH](https://user-images.githubusercontent.com/54388663/114296958-a3147e80-9acb-11eb-9743-259d1e0c37b6.jpg)
  
  2. Classification: Random Forest classifier was used
  
  Batsman and Wicketkeeper Classification report and Confusion matrix:
  
  ![classification_report_batsman_wicket_keeper](https://user-images.githubusercontent.com/54388663/114297147-9ba1a500-9acc-11eb-90d6-dc026ef439be.png) ![confusion_matrix_batsman_wicket_keeper](https://user-images.githubusercontent.com/54388663/114297150-9cd2d200-9acc-11eb-979b-4929152435c4.png)
  
  Bowler Classification report and Confusion matrix:
  
  ![imgonline-com-ua-resize-fzP6SPp1kuMO](https://user-images.githubusercontent.com/54388663/114297743-13bd9a00-9ad0-11eb-8e03-39f998ea6d8c.jpg)    ![imgonline-com-ua-resize-LYigfKlfd675W](https://user-images.githubusercontent.com/54388663/114298951-71ed7b80-9ad6-11eb-81a0-9ee2b0e03d53.jpg)
  
  Allrounder Classification report and Confusion matrix:
  
  ![classification_report_all_rounder](https://user-images.githubusercontent.com/54388663/114297149-9c3a3b80-9acc-11eb-9825-ffa40d362791.png) ![confusion_matrix_all_rounder](https://user-images.githubusercontent.com/54388663/114297148-9ba1a500-9acc-11eb-9e70-e85a8db49dd8.png) 
  
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
