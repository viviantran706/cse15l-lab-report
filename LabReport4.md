## Lab 4 Report - Vim (Week 7)

Started form steps 4.
# Step 4 - Log into ieng6
![Image](https://raw.githubusercontent.com/viviantran706/cse15l-lab-report/main/Screenshot%202023-11-19%20145648.png)

*Keys pressed: entered `ssh cs15lfa23` account*

# Step 5 - Fork of the repository form my Github
![Image](https://raw.githubusercontent.com/viviantran706/cse15l-lab-report/main/Screenshot%202023-11-19%20145905.png)

*Keys pressed: <ctrl + c> and <ctrl +v>, copied and paste from the Week 7 lab `git clone https://github.com/ucsd-cse15l-s23/lab7` *

# Step 6 - Run Tests (failed)
![Image](https://raw.githubusercontent.com/viviantran706/cse15l-lab-report/main/Screenshot%202023-11-19%20201015.png)

*Keys pressed: entered `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` then `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests`*

# Step 7 - Edit the Code File ListExamples.java

![Image](https://raw.githubusercontent.com/viviantran706/cse15l-lab-report/main/Screenshot%202023-11-19%20202316.png)

*Keys pressed: vim + <space> + ListExamples, <ctrl + end>, <up> siz times, press <1 +e> then <i>, <delete>, push 2 in, <escape>, <:wq>*


# Step 8 - Run Test (passed)
![Image](https://raw.githubusercontent.com/viviantran706/cse15l-lab-report/main/Screenshot%202023-11-19%20201044.png)

*Keys pressed: <up><up><up><up><enter> four times to searched through the search history to access `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` 
then <up><up><up><enter> to access the next commands `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests`*

# Step 9 - Commit and Push
![Image](https://raw.githubusercontent.com/viviantran706/cse15l-lab-report/main/Screenshot%202023-11-19%20201410.png)

*Keys pressed: entered `git add .` `git commit` then `git push`*
