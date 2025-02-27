# AI-BASED-RECOMMENDATION-SYSTEM

*Company* : CODETECH IT SOLUTIONS

*Name* : Dasari Madhuri

*Intern ID* : CT12NZP

*Domain* : JAVA Programming

*Duration* : 8 Weeks

*Mentor* : Neela Santosh

##Description about the code: This Recommendation System reads user-item ratings from a CSV file and suggests items based on user preferences using a simple collaborative filtering approach.

##*Tools & Technologies Used*: 

*Java*: Used for implementing data processing and recommendation logic.

*VS Code*: Used to write and save the Java program.

*Command Prompt (CMD)*: Used to compile and execute the program.

*File Handling (java.io package)*: Used to read user preferences from a CSV file.

*Data Structures (HashMap, ArrayList)*: Used to store and process user ratings.

##*Commands Used*:

*1.Compile the Java file*: javac RecommendationSystem.java

*2.Run the program*: java RecommendationSystem

##Data Format  in data.csv

1,Book A,5

1,Book B,4

2,Book A,5

2,Book C,4

3,Book B,3

3,Book D,5

4,Book A,5

4,Book C,4

4,Book E,5

Each line represents: UserID, Item, Rating

The system uses collaborative filtering to suggest items a user has not rated based on other users' preferences.


##*Working of the Program*:

1.Reads the data from data.csv and stores user-item ratings in a HashMap.

2.Takes a user ID as input and finds items highly rated by similar users but not yet rated by the given user.

3.Displays the recommended items based on the highest ratings.


##*Applications*:

1.Product recommendations in e-commerce.

2.Movie or music recommendations.

3.Personalized content suggestion systems.

##*Output* : 
