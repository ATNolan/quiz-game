# A Simple Timed Quiz Game

A Simple Timed Quiz Game Written With Golang

# HOW IT WORKS!

This program reads in a quiz provided via a CSV file and will then give the quiz to a user keeping track of how many questions they get right and how many they get incorrect. Regardless of whether the answer is correct or wrong the next question should be asked immediately afterwards.

The CSV file should default to problems.csv, but the user should be able to customize the filename via a flag.

You can assume that quizzes will be relatively short (< 100 questions) and will have single word/number answers.

The default time limit should be 30 seconds, but should also be customizable via a flag.

Your quiz should stop as soon as the time limit has exceeded. That is, you shouldn't wait for the user to answer one final questions but should ideally stop the quiz entirely even if you are currently waiting on an answer from the end user.

Users should be asked to press enter (or some other key) before the timer starts, and then the questions should be printed out to the screen one at a time until the user provides an answer. Regardless of whether the answer is correct or wrong the next question should be asked.

At the end of the quiz the program should output the total number of questions correct and how many questions there were in total. Questions given invalid answers are considered incorrect.

# HOW TO PLAY GAME

1. You must have GO installed on your local machine.

2. Create a folder, and clone the files into it.

3. Then open your terminal, and run the command below:

      # go run main.go
      
4. The above command should automatically start the the quiz....

5. Have fun!

# BONUS

- You can as well edit the "problem.csv" file, add couple of questions and use it as a daily mathematics drill test for kids.
