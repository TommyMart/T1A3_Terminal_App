# QUIZ NIGHT TERMINAL APP GAME

#### Term 1 Assignment 3 Coder Academy 2024
#### Thomas Martin

---

### Git Repository 

Link to [Git Respository](https://github.com/TommyMart/T1A3_Terminal_App).

---

### Project Managment Trello Board

Link to [Trello Board](https://trello.com/b/wfUXTR4Q/quiz-night-terminal-app).

---

## Application running requirements

- The app requires python version 3.8 or higher to be in installed, if you want to check which version of Python you have installed please open your terminal and run the following command ```python3 --version```. 

- If you do not have Python 3 installed, that's fine, but please download it from the [Official Python Website](https://www.python.org/downloads/) before proceeding. Please follow the same procedure if you have any other version of Python installed - such as version 2. 

---

## System / Hardware Requirements

There are no system or hardware requirements for the application, besides the device needs to have a terminal to run the app. The application does not need much processing power so should be runnable on all modern devices. 

The application has been designed to run on the following operating systems:

- macOS
- Windows
- Linux

Please also make sure that Python 3.8 or is installed.

--- 

## Getting Started 

#### Options 1 - Clone the Repository

##### Unix-based Systems (macOS, Linux)

You can clone the source respository from the [T1A3 Terminal App Repository](https://github.com/TommyMart/T1A3_Terminal_App), or just follow the following steps.

##### Feel free to copy and paste the following code steps! 

- Next launch the terminal on your device and enter: ```git clone https://github.com/TommyMart/T1A3_Terminal_App.git```

- Navigate into the T1A3 Terminal App directory: ```cd T1A3_Terminal_App```

- Then please convert the run.sh file into an executable bash script by running: ```chmod +x scripts/run.sh```

- Then run the bash script which will start a virtual terminal environment and install the required packages: ```scripts/run.sh```

- Done!! How easy was that? 

You should now see ```Are you a new user? (Y/N): ```

If you're getting ```zsh: command not found: chmod +x scripts/run.sh``` when trying to run the previous ```chmod +x scripts/run.sh``` command, it might be the odd case of because the command was copy and pasted. Try writing the command yourself instead of copying and pasting in this instance and it should hopefully work. I'm not sure why this is the case but some of my fellow students ran into this error and following the instructions above fixed the issue. Good luck!

#### Option 2 - Download Zip File

- If you opted to download the zip file, please download it from here - [T1A3 Terminal App Repository](https://github.com/TommyMart/T1A3_Terminal_App).

- Then please navigate to where ever the file is located on your device and unzip the file. 

- Then launch the terminal from your device and navigate to the unzipped T1A3_Terminal_App project directory. 

- Then please convert the run.sh file into an executable bash script by running: ```chmod +x scripts/run.sh```

- Then run the bash script which will start a virtual terminal environment and install the required packages: ```scripts/run.sh```

- Done!! How easy was that?

You should now see ```Are you a new user? (Y/N): ```

##### Windows

- Install [Windows Subsystem for Linux](https://learn.microsoft.com/en-us/windows/wsl/install)

- Then clone the source respository from [T1A3 Terminal App Repository](https://github.com/TommyMart/T1A3_Terminal_App).

- Navigate into the T1A3 Terminal App directory: ```cd T1A3_Terminal_App```

- Then please convert the run.sh file into an executable bash script by running: ```chmod +x scripts/run.sh```

- Then run the bash script which will start a virtual terminal environment and install the required packages: ```scripts/run.sh```

Incase you thought you had Python 3.8 or higher installed but you don't, the terminal will let you know before it installs the packages, you may have to scroll up if your terminal window is small, after you run the above commands.

In the highly unlikely situation where the above steps don't work, please install Python 3.12.1 or higher and try again. Alternatively, download the zipped folder and via your terminal navigate to the root directory of the app by using change directory ```cd T1A3_Terminal_App``` command. 

For more information please see [About Remote Respositories](https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories).

###### Need Help?

If you're unsure where abouts you are within the file tree of your device, you can execute the print working directory command ```pwd```, which will print the directory in which you currently are. Another great command is ```ls```, this stands for list and will list all the files and directories within the current directory. If you want to move into a directory within that list use the change directory command ```cd``` followed by the directory name like so ```cd T1A3_Terminal_App```. 

 ---

## Packages

The application runs both external and built in Python system packages, these include:

##### Stanard Library Imports

- csv

Is used in the app to write comma seperated value files. More info [here](https://docs.python.org/3/library/csv.html).

- time

Used in the app to take time stamps based on seconds passed since epoch. More info [here](https://docs.python.org/3/library/time.html).

- random

Is used in the app to randomly shuffle tuples and generate random integers. More info [here](https://docs.python.org/3/library/random.html).

- getpass

Is used in the app to make the user password input invisible. More info [here](https://docs.python.org/3/library/getpass.html).

- os.path

Is used in the app to check if a csv has been created or not. More info [here](https://docs.python.org/3/library/os.path.html).

- operator

Is used in the app to access a piece of data from a sorted list, lambda was initially used but it is not recognised as part of the Pep 8 styling. More info [here](https://docs.python.org/3/library/operator.html).

##### Related third party imports

- Rich

Is used in the app for text colours and styling, emojis and tables. More info [here](https://rich.readthedocs.io/en/stable/introduction.html).

Don't worry - These are downloaded automatically in a virtual environment when running the run.sh file above. Sit back and relax, we've taken care of everything for you. 



---

## Code Style Guide

The chosen code style guide for the applicaton is [Pep 8](https://peps.python.org/pep-0008/).

Initially, the code was manually styled as per the Pep 8 guidelines above so that the style guide was successfully learnt. Then autopep8 v2.1.0 was installed and ran on the three .py python files for a more aggressive take on the styling rules. The link to the external package can be found [here](https://pypi.org/project/autopep8/). The autopep8 script file is still available in the scripts folder should you wish to see how it was ran. 

---


#### Congratulations! You've made it past the difficult part - now let's create a username and password. 

## Signing Up

Firstly, as a new user you will have to create an account by entering a username and password. Please ensure you remember the password if you want to try and build on your high scores later down the track.

- Please select Y if you are a new user: <br>
```Are you a new user? (Y/N): Y``` 

- Please enter a username that is at least five characters long. <br>
```Please enter a username: ```

- Please enter a password that is at least five characters long - please be sure to remember it! <br>
```Please enter a password: ```

## Siging In

Assuming you've already signed up following the previous instructions and created an account by entering a username and password... 

- Please select N beacause you are not a new user: <br>
```Are you a new user? (Y/N): N``` 

- Please enter your username. <br>
```Please enter your username: ```

- Please enter your passwor. <br>
```Please enter your password: ```

If for any reason you cannot remember your username or password, then it's probably best to cut your losses and enter S to create a new account... Please be sure to remember your details this time!

---

##### For the best user experience, please make sure your terminal window is at a medium size. We also prefer a black background over white, but hey, that's just our opinion! 

#### Now let's have some Quiz Night fun!

## Main Menu

![Main Menu](images/Screenshot2024-04-30at3.16.53pm.png)

###### 1. Quiz Topics 
- Enter 1 to see the quiz topics menu.

###### 2. Topic High Scores
- Enter 2 to see the high scores board.

###### 3. Quick Start Random Quiz
- Enter 3 to quick start a random quiz.

###### 4. Quiz Instructions
- Enter 4 to see a detailed explanation of the game instructions. 

###### 5. EXIT
- Enter 5 to exit the application. 

##### If you've had enough of reading and just want to jump in, please be my guest! You can enter 3 from the main menu and the app will select a random quiz for you to get started on. 

---

## Quiz Topics

![Quiz Topics](images/quiztopics.png)

The Quiz Topics menu shown above displays the quiz topic genres available and their corresponding numeral selection values. To start any of the quizzes please enter their numeral value. 

- Enter 1 for Music 
- Enter 2 for History 
- Enter 3 for Capital Cities 
- Enter 4 for Computer Science 
- Enter 5 for General Knowledge 
- Enter 6 to return to the Main Menu 

## Playing the Quiz

If you chose to take a quiz, a 'get ready' timer bar will run before your quiz and timer starts. 
![Timer bar](images/Screenshot2024-04-30at2.31.27pm.png)

##### Ready, Set, Go!

When the the bar reaches 100%, it's time to play!

The question is displayed followed by a choice of options which are labelled as A, B, C, or D. The user is then prompted to enter one of the option selections, once a selection has been entered the user is notified if they their answer is correct or incorrect, and if incorrect, the correct answer is displayed to the user. 

![Quiz question example](images/Screenshot2024-04-30at2.32.59pm.png)

If the user enters a character that is not from the selected options, they are notified that their selection was invalid and they will not be able to re answer the question, or shown the answer. 

![Invalid quiz answer](images/Screenshot2024-04-30at2.39.04pm.png)

Once the user has answered all the questions, score percentile, time and total points are displayed as results. Total points is a function that takes the user's score and time taken and provides a total points score for the sake of the high scores board. If the total points score is a new high score for the topic the user is notifed at the end of the quiz, after their results, as shown in the image below. 

![Quiz Results](images/scores.png)

The image above is notifying username - 'Tommy' that they have achieved a new topic game high score of 1148.51 points! 


## Topic High Scores

![Topic High Scores](images/highscoresboard.png)

Accessible by entering 2 from the main menu is the topic high scores table. Here, any user on the device can view the top 3 highest scores for each topic and the username of the user who achieved the score. Luckily, high scores are not just viewable for the current username signed in but for all users, allowing users to compete against one and other for top spot! 

If no quizzes have been attempted the high scores table is not shown, instead the user is notified that there are no quiz scores to be displayed when entering 2 from the main menu. 

## Quick Start Random Quiz

This option from the main menu is for those who don't like waiting! This allows users to jump straight in and let the app decide which quiz topic the user will play. Those topic choices are of course music, history, captial cities, computer science and general knowledge. 

## Quiz Instructions

Unlike the random quiz selection above, 'instructions', accessible by entering 4 from the main menu, is for those who like to understand the ins and outs of the app before playing. Or, of course, if the user doesn't understand something. The instructions also point the user to the readme for further help. 

## EXIT

Maybe you've had enough, or, more likely, your sister wants to try and beat your new high score! 

You can probably guess what entering 5 does from the main menu..? Yes, you're correct, it exits the app. 

```"Goodbye from all of us here at Quiz Night. We hope to see you again soon!```

---

## FEATURES

##### For further explanation and with visual representation, please refer to the in-code comments in the main.py, quiz_functions.py and quizzes.py Python files. 

### Feature 1. Sign In/Up 

The sign in / up feature requires a username and password to be be assigned before playing the quiz. The main reason for this feature is because of the high scores table and the username associated with the scores. Just having the scores by themselves on a high score board with no username attached would not be the same. 

The sign up feature requires the user to enter a username that is five characters or more long, it is then converted to a title (capital first letter) to greet the user once sign up is completed. The next user requirement is a password, this also needs to be 5 or more characters long and is written invisibly to the user usering the getpass package. The username and password is then written to a csv file called user_names.csv to facilitate the sign in function. 

The sign in function require the user to enter their previously entered username and password, entered during the sign up feature, that opens and reads the user_names.csv file. While reading the file, using a for loop, the application checks to see if their is a matching username and password. If the entered two values match an existing two values, the user is granted entry to the quiz under the entered username and welcomed using that name. If a match is not found, the user is then asked if they would like to sign up with a new account, or, try signing in again. 

- Import csv system package.
- Create a csv file called user_names.csv and assign it to the second_file_name variable.
- Open the variable under write mode so that a file is created if one does not already exist.
- Write username and password to the file seperated by commas as a list.
- Close the app, because 'with' was not used.

##### Sign Up

- Input username that is at least 5 characters long. 
- Input password that is at least 5 characters long.
- Write new username and password to csv file.
- Welcome username.

##### Sign In

- Input username.
- Input password. 
- Open csv file variable in 'r' (read) mode. 
- Loop through each row of csv file and see if username matches index 0 in the row list, if a match is found, check if password matches index 1 of that row list. 
- If found, Welcome username to the Quiz Night app.
- If not found, notify the user they have not entered the right username or password. And, give them an option to return to the sign up function. 

Error handling has been ulitised by printing a incorrect username or password string if there isn't a match, the user then has the opportunity to retry or enter s to sign up. If the user enters a character other than Y or N, then 'Invalid input' is printed to the screen, and then 'please enter Y or N' is displayed. Try and except code error handling has also been added in case of the unlikely event that an error is thrown during the main, sign_in or sing_up functions. 

```"Oops! Something seems to be not working, please try again."```

If I were to develop a similar app in the future, I would include a loop that looks through the csv file for usernames when signing up, and if the name was already taken display "username" unavailable. Or something along those lines... This would not be difficult or take much time, but I simply did not have the free time to write before the assignment deadline. 


### Feature 2. The Quiz 

Some may think, hmmmm, writing code for a quiz must be pretty easy... Well, I've got news for you! 

Let's put aside time taken and total points for now, I'll explain them later. 

Initally, a function was written that takes the topic choice, question, four guess options, answer and username as arguments. The questions, answers and options must then be bundled together and randomly sorted so that their indexes remained constant between the sets but shuffled for each quiz attempt. This allows the question order to be at random, eridicating the chance of users writing down or memorising the answers and inputting them without reading the question. 

This is achieved by zipping the lists, using the random shuffle package to shuffle, and then assign the newly shuffled lists to new variables - shuffled_questions, shuffled_options, shuffled_answers. These new variable lists can now be used for the quiz and will have the same corresponding indexes, so the questions, options and answers still marry up. 

```combined = list(zip(questions, options, answers))```\
```random.shuffle(combined)```\
```shuffled_questions, shuffled_options, shuffled_answers = (*combined)```\

Confused? Let's walk through it...
- The combined zipped variable results in a tuple including an index from each list - one question, four guess options and the answer. 
- Since they are now zipped in seperate tuples, the tuples can now be shuffled without getting mismacthing questions, options or answers. This is executed with the help of the random.shuffle package.
- The * is then used to unpack the combined zipped variable into new 'shuffled' tuples with new a random order but with all questions, options and answers still matching.
- They are then assigned to new shuffled variables, and this happened every time before a quiz is called!

A score counter is initiated and set to 0, that increases by one every time the users guess and answer match. This final score is then displayed at the end of the quiz as a percentile. Using ```score = int(score / len(shuffled_questions) *100)```. It is also used to calculate the total points along with the total time taken in the next feature.

A variable question_num is set to 0, and a for loop is used to loop through the shuffled questions, options and answers, using question_num for the constant index of each of the new lists for each loop, which is then increased by 1 after displaying the result to the user at the end of the loop. Since the questions data is a set, the for loop will loop through question in questions until there are no more questions. 

The quiz is executed using a for loop, where for question in shuffled questions the question is printed, and then a nested for loop to print the four options as ```for option in shuffled_options[question_num]:``` because this is a nested loop it will keep looping until all options in shuffled_options has been looped for whatever index the question_num is on. If the users guess equals the shuffled_answers and the same question_num idex then, you guest it, correct guess! And the score counter increasese by 1. The users guess is also appended to a guesses list to display at the end of the quiz. The user guess is also made a capital because you'd be pretty annoyed if you entered an a when the answer was A and you were marked incorrect. An elif statement is used for if the users guess is incorrect, which is displayed and also an else statement if the user enter something that isn't A, B, C, or D. Finally at the end of the loop, the question_num counter is increased by one so that the shuffled lists index all match for the next loop. 

The counter question_num was implemented so that the quizzes can be manipulated in the future, maybe to add more questions, or even change the data for CS Fundamental test revision next semester. It also allows for the topic points function to run when quiz topics have different numbers of questions. 

The results are then displayed as answers and guesses, a percentile score and total time. 

![Results](images/results.png)

Error handling has been utilised by printing 'Incorrect!' if the user enters a wrong answer, followed by a string displaying the correct answer. If the user enters an input that doesn't match the options, A, B, C or D, the a message is displayed that the input was not a valid answer. This alone should handle most errors, but just in case a try and except code is executed in case of any unlikely errors. The progress bar also has a try and except block, just in case it doesn't work on some operating systems. 


### Feature 3. Total Points and Time Taken 

To eliminate the chance of a user googling the answers a total points scoring function is created using score, number of questions and total time as arguments. It was achieved by basic multiplication, adding and subtracting, plus some trial and error with constants (allocated time and score *). 

A time stamp is saved to a start_time variable which happens after the get ready progress bar has reached 100%, this is achieved by using the time package. The quiz loop then runs for all questions and then another time stamp is saved to a end_time variable. The total time is calculated by subtracting the start time and from the end time which is displayed to the user as 'total time taken' in the results section and then passed to the calculate_points function to calculate total points. 

The calculate points function take the score, which is a percentile and multiplies is by 50, and saved to the score points variable. This is done to give the calculation some room to move when taking time into account. A variable max time is calculated by muliplying the number of questions in the quiz with the allocated time of 30 seconds per question, if the user takes less time than the allocated 30 seconds per question max time for the overall quiz, then that time difference is added to the score points variable. 

```time_points = (max_time - total_time) if total_time < max_time else 0```

If total_time is less (<) max_time, time_points equals the result, but if max_time is bigger than total return 0. This is a form of error handling, if the user takes the maximum time allocated of 30 seconds per question or longer, this code ensures 0 is returned, and no extra points will be added to total points. 

This might be a little confusing... so here's an example to clear things up. 

- If there was 5 questions in the quiz
- And the user got 3 questions correct 
- Their score would be 60% (correct guesses / number questions * 100)
- Their score points would be 300 (score * 50)
- Their max time would be 150 seconds (number of questions * 30) 
- Let's say time taken was 120 seconds 
- Their time points would be 30 (max time - time taken)
- Their total points would therefore be 330 (score points + time points)

Pretty simple when you break it down right?

This way the user is rewarded when they take less time than the allocated 30 seconds per question.

![Total points](images/totalpoint.png)

The total points, username and quiz topic are then appended to the list.csv so that the high scores feature can read, then reverse sort the lists based on total points so that the 3 highest scores can be displayed and their username. 

A csv file is created at the start of the quiz "w" write mode if it has not been made already and the headings topic, score (total points) and username are written to the first row. The data is then appended to the list so it can be read at different stages of the app. 

Error handling has been implemented into the code by using try and except on the quiz function itself, in which the time variables are assigned locally. The calculate points function also has try and except incase any unlikely errors should occur. 


### Feature 4. High Scores Board 

The high scores board opens the list.csv file that was saved to the variable file_name in 'r' read mode, and appends each row entry of topic, score and username as a list, to a parent list. 

![List Headings](images/listhaedings.png)

Because the file was opened with ```with``` the file does not need to be closed. This then seperates the scores into their topics, which is important so that the board can display the highest scores for all 5 topics and not just the highest overall. This is achieved by using a for loop, and sorting the row lists into seperate new lists based on their first topic index ```i[0]```. If ```i[0]``` equals 1 for example, then the username ```i[2]``` and score ```float(i[1])``` are appended to their own topic list. The data index position of the new lists is index 0 is now username, and total points now index 1 - and the same for all other list topics. Topic is not appended to the list because it has already been used to seperate the data into their topic lists and all child lists would have the same topic. 

Once the loop has appended all the row lists to their corresponding topic lists, the lists are then sorted using the .sort method and reverseed based on index 1, ```x[1]``` or total points, so that the highest scores are at the start of the list and lowest at the end.  

List comprehension is then used to extract the first 3 highest scores in each list. ```list[:3]``` iterates over the first three child lists within the parent topic list. These topic score lists and then used to represent the top three highest score data in the corresponding table rows using the rich external package. ```[f"{score[0]} - {score[1]:.2f}" for score in music_highscores[:3]]``` As we know the the username in the new topics list is index 0, or score[0], and index 1 is total points, or score[1]. A for loop is then used to iterate and display the username and total_points data for three iterations [:3]. Knowing the username who achieved the high scores is crucial in a competative game. 

Also, ```:.2f``` means that only two decimal points will be displayed of the float, the rest will be cut off, otherwise the total points can be too long. 

These results are then printed to the termal as a rich external package module table in different colours for 1st, 2nd and 3rd.  

![High Scores Board](images/highscores.png)

During the writing of this function, a bug arose where if the topic high scores were called when the csv scores list had not been created yet. In this scenario the application was trying to read a file that did not exist, so it threw a tantrum (error). After some trial and error coding, this bug was resolved by using try and except, if the file did not exist, it means that no one has attempted a quiz yet, because the write file is at the start of the quiz function. This file could have been moved so that it was created earlier, but I decided to use the except block to print ```Sorry, there's no quiz scores to show right now.``` instead. This way the user is more inclined to want to attempt a quiz so they can see what the high scores board looks like!

A parent try and except was also used at the very start of the function so if any unlikely errors were to occur they would be caught and a more appropriate message would be displayed. 


### Feature 5. Random Quiz 

The function uses the random package to assign a random integer between 1 and 5, because there are 5 quiz topics, to the variable rand_quiz. That variable rand_quiz integar is then passed to the quiz topics function as an argument and the rand_quiz integer variable is then assigned to topic choice which runs the quiz with the corresponding random integar as the topic choice. The quiz topic table is not ran because the rand_quiz argument has a value. 

For example: 

- If the random integer is 1, the topic choice is 1 and the music quiz is ran.
- If the random integer is 4, the topic choice is 4 and the computer science quiz is ran. 

The random quiz feature takes the username variable as an argument, passed from the sign in/up to the main menu, to the topic choice through to the random quiz function. This is so the users quiz total points and username can be appended to the list csv file. The username must also be passed as an argument through other functions so it is mostly accessible. The rand_quiz argument must also be set to equal None in the quiz topics function if it is not passed a value, so that if the function is called from the main menu, rand_quiz doesn't impact what quiz is ran. 

Error handling was implemented to this function by using try and except. The random integer can also only be between 1 and 5 which corresponds to each quiz, so that no errors can occur. 

---

## PROJECT MANAGEMENT

For project management and planning a Trello Board was created, this provided a due date for each feature and a checklist of items needed to be completed to satify the completation of the feature. Once completed, the feature card is able to be moved to the 'Done' category, this greatly helped in organisation, time management and lessened the stress of not knowing which feature to focus on. Successfully using project and time management I was able to treat the assignment as lots of smaller tasks which felt great ticking off, or, moving to the done column. The due dates were mainly organised into a few different dates that was based around my schedule and what days I would be able to dedicate to study. 

I used the trello board regularly throughout the planning and development process, checking in everyday that I was able to study and slowly moving the cards from 'to do', to 'doing', to 'done'. Which felt great! It was especially useful when I had not been able to study for a couple of days and needed a refresher of what needed doing, instead of feeling overwhelmed, I was able to jump straight in. It definitely saved me time, which led to handing up the assignment a day earlier than I had planned. 

Pre planning was also done over the weekend of the 20th, where I read about many different terminal app ideas out there, and brainstormed what could be a fun idea for my app assignment. I decided that by the 24th an idea needed to be decided upon so that I had sufficient time to create a high quality functioning app. I wanted to develop an app that could help me in some way in the future, be that in life or study, and knowing that we have regular CS Fundamental tests and exams coming up in Term 2, a quiz game was decided upon. The quiz data sets are easily changable, so using it in the future for study will be an easy, fun and rewarding way to prepare. 

### Sign Up/In

Due date: 3rd May \
Completion: 1st May

- Import csv system package.
- Create a csv file called user_names.csv and assign it to the second_file_name variable.
- Open the variable under write mode so that a file is created if one does not already exist.
- Write username and password to the file seperated by commas so the app can access each during sign in/up.
- Close the app, because 'with' was not used.

##### Sign Up

- Input username that is at least 5 characters long. 
- Input password that is at least 5 characters long.
- Write new username and password to csv file.
- Welcome username.

##### Sign In

- Input username.
- Input password. 
- Open csv file variable in 'r' (read) mode. 
- Loop through each row of csv file and see if username matches index 0 in the row list, if a match is found, check if password matches index 1 of that specific row list. 
- If found, Welcome user to the Quiz Night app and return their username.
- If not found, notify the user they have not entered the right username or password. Or, give them an option to return to sign up function. 

![Trello Sign In/Up](images/trello.signin.png)


### Quiz 

Due date: 1st May\
Completation: 1st May

- Write a quiz function that takes the index, or question number, and accesses each index within the three questions, options and answer lists, then returns if the users guess is equal to the answer.
- Input quiz questions, options and answer data as sets. 
- Shuffle the questions, answers and options using the random function so that the order of questions change each time.  
- Keep track of scores using a score += counter per correct user guess. 
- Write a string that informs the user if their guess was correct or incorrect per question. 
- Display a string of the users guesses and the correct answers.
- Display the users score as a percentile. 

![Trello Quiz](images/trello.quizfunction.png)


### Total Points and Time Taken

Due date: 3rd May\
Completion 1st May

- Write a time stamp to use as start time.
- Write a time stamp to use as end time.
- Write a calculation that works out total time taken.
- Write a function that takes total time taken and score and calculates a total points score that produces a higher score the less time the user takes. 
- Write a string that display total points at the end of the quiz. 
- Error handling so if an error occurs during the calculate points function of quiz function.

![Total Points Trello](images/totalpoints.trello.png)


### High Scores Board

Due date: 4th May\
Completion: 2nd May

- Open the csv file which hold the topics, scores and username in read mode. 
- Append row data to new lists based on topic number.
- Sort list from highest score to lowest score.
- Display first three lists within list username and score for each new list.
- Add this data to display in a table.
- Write error handling for function itself and if the csv list doesn't exist.
- Test it works. 

![High Scores Trello](images/highscores.trello.png)


### Random Quiz

Due date: 4th May\
Completion: 2nd May

- Import Random. 
- Write random function that generates random a integer between range 1 and 5 inclusive each time it is called. 
- Pass that number to the Quiz function so that the random integar equals the quiz topic value.
- Ensure the high scores board does not produce an error if the scores csv file has not yet been created. 
- Write error handling should an error occur. 
- Test it works. 

![Random Quiz Trello](images/random.trello.png)


### Other Cards

Some other cards used in the project management Trello board but not mentioned above are:

##### Project Planning
Due date: 24th of May\
Completion: 24th of May
##### Package research
Due date: 27th of May\
Completion: 27th of May
##### Quiz Data
Due date: 27th of May\
Completion: 27th May
##### Main Menu
Due date: 27th of May\
Completion: 26th of May
##### Quiz Topics Menu
Due date: 3rd of May\
Completion: 26th of May
##### Aesthetics 
Due date: 4th of May\
Completion: 2nd of May
##### Error Handling
Due date: May of 4th\
Completion: 3rd of May
##### Write Scripts
Due date: 4th of May\
Completion: 4th of May

##### Work in progress Trello Board

1st of May 2024
![WIP Trello Board](images/WIPTrello.png)

##### Completed Trello Board

4th of May 2024
![Completed Trello Board](images/completedtrello.png)

### Testing

Due date: 4th May /
Completed 4th May

Testing is the final step from a project management perspective. This will be achieved manually by trying to run through every possible scenario. The file will also be passed to my fellow students, preferably running different operating systems, to test the functionality of the quiz. And that the bash scripts install the correct packages and run successfully in the virtual encironnent. 

---

Given user terminals are often ran with a black background, the app colours were tested against different backgrounds to ensure the visability of the app was adequate. With some minor adjustments the colours used with a black terminal look great! And have a high contrast that should be easily visable for most. It is recommended to only use white or black backgrounds, as different colour backgrounds may interfere with the app colours and limit legibility. 

##### Main Menu on dark background

![Main Menu on Dark Background](images/mainmenudark.png)

##### Quiz Topic Menu on dark background

![Quiz Topic Menu on Dark Background](images/topicmenudark.png)

---

## Error Handling

Error handling has been used at the start and end of all functions using try and except, this means the user will not be shown any ugly terminal errors, instead they will see ```Oops! Something seems to be not working, please try again.```

Error handling has also been implemented into some of the child functions and loops that may cause an error, like the progress bar, just in case it doesn't work on a different operating system. Else statements have also been used to as a likely input or to catch invalid inputs or unexpected errors. 

---

## Flowchart

Here is a simple flow chart to visualise the overall flow of the app. 

![Flow Chart](images/flowchart.png)

## Challenges 

#### DRY

Initally the menus were called in a one function, but due to wanting to add emojis and extra columns and rows, plus table styling from the rich module, it was decided to write them seperately. I understand that a function could have been used but this would have come at the expense of the overall quality and user experience of the app. 

#### Pep 8

In some instances the Pep 8 guidelines were overridden based common sense and readability. This occured mainly during the table rows and columns, where the recommedned line length was exceeded. I thought it was important that each column and row stayed as one line of code to avoid messy and confusing code. 

#### No Global Variables

I chose to assign variables locally within functions and either return them, or pass them as arguments between functions. This was mainly used for the username, which was created during the sign in stage and passed through the quiz so that it could be written to the total points csv file and then be accessed for the high scores board. I wasn't sure if this was standard Python 3 practice and a google search gave me a mixed response, therefore it was decided to stay with the original method which is less messy code. 

---

## Reference List

- Hattori, H n.d., autopep8: A tool that automatically formats Python code to conform to the PEP 8 style guide, PyPI.
- Python 2019, Download Python, Python.org, Python.org.
- van Rossum, G, Warsaw, B & Coghlan, N 2001, PEP 8 – Style Guide for Python Code, peps.python.org.
