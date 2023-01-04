# Programming-Fundamentals-Project

#Introduction: 

Our "horse race betting game" includes a random number of horses based on the programmer's preference and need, as well as the option to wager on a single horse. If the user's chosen horse wins, the betted sum rises by three times, whereas if the horse loses, the user loses the whole amount. It's worth noting that our program isn't hardcoded, nor does it follow a precise pattern that may enable the user to win all of the time; instead, we utilized Python's "random" function to avoid any set order.
If a user chooses a "blue” horse and lays a bet of "x," the user will gain "3*x" if the blue horse wins, but if the user loses, he or she will lose the whole betted sum.
The objective of this report is to give detailed instruction on the functions that have been utilized, as well as a succinct overview of the program.

#Modules used:   

•	Tkinter
•	Random
•	Time

#User-defined Functions:

•	start_game
•	move_horses
•	check_winner  

#Working:
In order to execute the program, user has to open the file named ‘horse racing.py’ which leads to python IDE and from there, code can be executed. Once the program runs, interface shows up which tells the user what the game is about and how the user must interact. The user would first be prompted to select a horse out of three options provided i.e., Red, Blue and Black. Then user is prompted to input the betting amount in the range of 500 to 10000. Once both the inputs are validated, main graphical window pops up which shows the jockey arena along with the ‘Play’ button. Once the button is pressed, game starts and horses race against each other. After a random race, winner is announced and the betted amount is either completely lost if your horse loses, or tripled if your selected horse won the race.    

#Constraints:
•	Only red, blue or black horse should be selected.
•	Betting amount should be in the range of 500-10000. 

