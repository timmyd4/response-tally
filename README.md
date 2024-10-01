# response-tally

An exercise for counting responses to a survey.

## Getting Started
Fork and clone this repository. You can look at the instructions from our [previous exercise](https://github.com/auberonedu/github-intro) as a reminder of how to do this. MAKE SURE TO CLONE YOUR FORK, NOT THE ORIGINAL.

## Data Format
There is a file `responses.txt` that contains the data we'll be working with. Here's a sample of it:
```
TODO: add sample
```

The first string on each line is a pseudonymous id of a student. The second string is a topic they want to know more about.

## Template Code
Look at `Tallyer.java` to see the already provided code. Take a look over it and predict what it will do when you run it.

### Running the code
1. Open your terminal in VS Code. On Mac/Linux, it should have the right type of terminal by default. On Windows, follow [these instructions](https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal) to make Git Bash the default terminal. (You do not need to do step 1 because you already have installed git).
1. Verify you are in the `response-tally` directory by running `pwd` (print working directory) on the terminal. The printed directory should end in `response-tally`.
1. Compile the Java files by running `javac src/**/*.java`
1. Run the main method of Tallyer by running `java -cp src Tallyer < responses.txt`

## Modifying the code
### Wave 1
Implement `tallyTopics`. Read the Javadoc carefully to understand what the method is meant to do.
### Wave 2
Implement `tallyTopicsFiltered`. Read the Javadoc carefully to understand what the method is meant to do.