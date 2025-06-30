# ShadowFox
Task Level (Beginner): Do 5 out of 9
1. Variables
1. Create a variable named pi and store the value 22/7 in it.
Now check the data type of this variable.
2. Create a variable called for and assign it a value 4. See what
happens and find out the reason behind the behavior that you
see.
3. Store the principal amount, rate of interest, and time in
different variables and then calculate the Simple Interest for 3
years. Formula: Simple Interest = P x R x T / 100
2. Numbers
1. Write a function that takes two arguments, 145 and 'o', and
uses the `format` function to return a formatted string. Print the
result. Try to identify the representation used.
2. In a village, there is a circular pond with a radius of 84 meters.
Calculate the area of the pond using the formula: Circle Area = π
r^2. (Use the value 3.14 for π) Bonus Question: If there is exactly
1.4 liters of water in a square meter, what is the total amount of
water in the pond? Print the answer without any decimal point in
it. Hint: Circle Area = π r^2 Water in the pond = Pond Area
Water per Square Meter
3. If you cross a 490meterlong street in 7 minutes, calculate your
speed in meters per second. Print the answer without any decimal
point in it. Hint: Speed = Distance / Time

3. List
1. You have a list of superheroes representing the Justice
League. justice_league = ["Superman", "Batman", "Wonder
Woman", "Flash", "Aquaman", "Green Lantern"]
Perform the following tasks:
1. Calculate the number of members in the Justice League.
2. Batman recruited Batgirl and Nightwing as new members.
Add them to your list.
3. Wonder Woman is now the leader of the Justice League.
Move her to the beginning of the list.
4. Aquaman and Flash are having conflicts, and you need to
separate them. Choose either "Green Lantern" or "Superman"
and move them in between Aquaman and Flash.
5. The Justice League faced a crisis, and Superman decided to
assemble a new team. Replace the existing list with the following
new members: "Cyborg", "Shazam", "Hawkgirl", "Martian
Manhunter", "Green Arrow".
6. Sort the Justice League alphabetically. The hero at the 0th
index will become the new leader.
(BONUS: Can you predict who the new leader will be?)
Your task is to write Python code to perform these operations on
the "justice_league" list. Display the list at each step to observe
the changes.

4. If Condition
1. Write a program to determine the BMI Category based on user input.
Ask the user to:
Enter height in meters
Enter weight in kilograms
Calculate BMI using the formula: BMI = weight / (height)2
Use the following categories:
If BMI is 30 or greater, print "Obesity"
If BMI is between 25 and 29, print "Overweight"
If BMI is between 18.5 and 25, print "Normal"
If BMI is less than 18.5, print "Underweight"
Example:
Enter height in meters: 1.75
Enter weight in kilograms: 70
Output: "Normal"
2. Write a program to determine which country a city belongs to. Given
list of cities per country:
Australia = ["Sydney", "Melbourne", "Brisbane", "Perth"]
UAE = ["Dubai", "Abu Dhabi", "Sharjah", "Ajman"]
India = ["Mumbai", "Bangalore", "Chennai", "Delhi"]
Ask the user to enter a city name and print the corresponding country.
Example:
Enter a city name: "Abu Dhabi"
Output: "Abu Dhabi is in UAE"

4. If Condition (Continued...)
3. Write a program to check if two cities belong to the same country.
Ask the user to enter two cities and print whether they belong to the
same country or not.
Example:
Enter the first city: "Mumbai"
Enter the second city: "Chennai"
Output: "Both cities are in India"
Example:
Enter the first city: "Sydney"
Enter the second city: "Dubai"
Output: "They don't belong to the same country"

5. For Loop:
1. Using a for loop, simulate rolling a sixsided die multiple times (at least 20
times).
Count and print the following statistics:
How many times you rolled a 6
How many times you rolled a 1
How many times you rolled two 6s in a row
2. Imagine you are doing a workout routine, and you have to complete 100
jumping jacks.
Write a program that:
Asks you to perform 10 jumping jacks at a time.
After each set, it asks, "Are you tired?"
If you reply "yes" or "y," it should ask if you want to skip the remaining sets.
If you reply "yes" or "y," it should break and print, "You completed a total of
jumping jacks."
For example, if you did only 30 jumping jacks and answered "yes," the program
will break and print, "You completed a total of 30 jumping jacks."
If you reply "no" or "n," it should continue and display how many jumping jacks
are remaining. After that, ask you again, "Are you tired?"
For example, if you answered "no," it should display that 70 jumping jacks are
remaining and ask you again, "Are you tired?"
If you reply "no" or "n," it should continue and display how many jumping jacks
are remaining. After that, ask you again, "Are you tired?"
For example, if you answered "no," it should display that 70 jumping jacks are
remaining and ask you again, "Are you tired?"
If you complete all 100 jumping jacks, it should print, "Congratulations! You
completed the workout," and stop the program

Task 2(Intermediate Level): Do both the tasks
1. Web Scraper: Extract data from websites using libraries like
Beautiful Soup or Scrapy.
2. Hangman: Implement the wordguessing game with visual
progress and hints.

Task 3(Advanced level): Do any 1 out of 3
1. Cricket Fielding Analysis Data Collection Objective:
As a budding sports analyst with an interest in cricket, your task is to
conduct a detailed fielding performance analysis for three players of
your choice from any innings of a T20 match. This analysis will help to
gauge individual fielding contributions and their impact on the team's
defensive play. A detailed sample data and sample performance matrix
is attached along the mail of task list.
Dataset Features:
- Match No.: Identifier for the match.
- Innings: Which innings the data is being recorded for.
- Team: The team in the field.
- Player Name: The fielder involved in the action.
- Ballcount: Sequence number of the ball in the over.
- Position: Fielding position of the player at the time of the ball.
- Short Description: Brief description of the fielding event.
- Pick: Categorize the pick-up as clean pick, good throw, fumble, bad
throw, catch, or drop catch.
- Throw: Classify the throw as run out, missed stumping, missed run
out, or stumping.
- Runs: Enter the number of runs saved (+) or conceded (-) through the
fielding effort.
- Overcount: The over number in which the event occurred.
- Venue: Location of the match.

  Performance Metrics Formula:
To assess the fielding performance, use the following formula:
PS=(CP×WCP)+(GT×WGT)+(C×WC)+(DC×WDC)+(ST×WST)+
(RO×WRO )+(MRO×WMRO)+(DH×WDH)+RS
Where:
PS: Performance Score
CP: Clean Picks
GT: Good Throws
C: Catches
DC: Dropped Catches
ST: Stumpings
RO: Run Outs
MRO: Missed Run Outs
DH: Direct Hits
RS: Runs Saved (positive for runs saved, negative for runs conceded)
Task Instructions:
1. Data Collection: For each ball bowled in the match, record the fielding
effort according to the dataset features outlined above. Pay close attention
to the effectiveness of fielding actions and their outcomes.
2. Analysis Preparation: Your collected data will be used for advanced
fielding analysis, identifying key areas of improvement and fielding strengths
within the team.
Deliverable: A well-organized spreadsheet or database containing the
complete fielding data for the match.
This task requires meticulous attention to detail and an understanding of
cricket fielding dynamics. Your analysis will contribute

