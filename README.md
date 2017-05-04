# CelebrityMatch
Demo for Personality Insights (PI) Watson API

The application does the following:

Accepts two Twitter usernames as variables
Retrieves the last 200 Tweets from each Twitter username
Sends the text of the 200 Tweets to the Personality Insights (PI) API (covered in more detail later in this course) to gain insights on the two users
Compares the users to one another
Displays the results of the comparison

The final results displayed will be the top 5 traits shared between the two Twitter users (for example: you and a celebrity of your choice).

The results are displayed in the following format:

Matched Personality Trait -> Probability of your profile exhibiting given trait -> Probability of Celebrity's profile exhibiting given trait.

Note: To successfully run this demo, a Twitter account and Twitter API credentials are required.

Enter a Twitter username on line 71. Be sure to include the @ symbol and ensure the name is encapsulated by " ".

Note: The Twitter username must correspond to a public Twitter account.

On lines 15 through 17, add your Twitter API credentials to the correct variables.
