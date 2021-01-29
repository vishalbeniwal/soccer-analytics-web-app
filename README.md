# Soccer Analytics Web App

Soccer analytics web app was developed by utilising a number of AWS web cloud services including AWS Cognito, AWS Sage maker, AWS S3, AWS DynamoDB, AWS Route 53, AWS QuickSight, AWS services SDK, AWS Elastic Beanstalk and AWS EC2.


The purpose of this project was to develop an analytical web application on European Football league and football match betting with an idea to:

1. To help the application users to know about the upcoming matches in major leagues (England Premier League in present application) with informative analytical data for each match. This analytical data is further supported by an analytical dashboard using which a user can interpret a team’s form, performance and history.
2. This will work as a helping hand for a user to make bets for a particular team more confidently on a third-party website such as bet365.
3. The application is built with a provision where the user’s preferences and prediction for an upcoming match will also be captured. This will give an idea about another user’s perspective.
4. To help a new user to know about European football world and team history.


FUNCTIONALITIES OF THE APP

The Soccer Analytics web is developed to introduce the world of European football in an analytical way to learn about a football team and their history, match fixtures, profit/loss in betting world, and user’s predictions.

The app provides the following as functionality to the user:

1. A user can register themselves using Login/Register functionality of the app.
2. User can view the upcoming football matches from one of the major European leagues i.e. English Premier League.
3. User can view host team’s overall win ratio and head 2 head (against guest team) win ratio. Host team is a team which is playing in their home stadium and hosting another team for the match.
4. User can access the dashboard created on AWS Quick Sight to gain analytical information about a particular team. Functionality is provided to the user for selecting the team they want. The dashboard is analysing last 10 years of data.
5. Based on the applied machine learning model on betting odds data from the one of the biggest betting sites, bet365, User will be able to see number of bets placed for a team and predicted loss or profit associated with that team. This will help them to make better betting decisions on third party sites, like bet365.
6. Provision to vote. User can use this functionality to give vote to a team that they think will have more chances to win in a particular match based on their analysis and own preferences. This vote will be saved in database for any future analysis. The vote count will be saved in the session so that other users can know more about other user's perspective.
7. Using the user profile, a user can change their name/nickname and password.

A complete walkthrough to the project implementation is given in the "soccer-analytics-report.pdf" file 

