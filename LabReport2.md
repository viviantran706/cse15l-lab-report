## Lab 2 Report - Servers and SSH Keys (Week 3)

# Part 1
![Image](https://raw.githubusercontent.com/viviantran706/cse15l-lab-report/main/Screenshot%202023-10-18%20190330.png)
1. Looking at the method it called, it called the first method. Which goes to the second if statment because we called for the
 "add-message" which will slit the query from the '='. This method will just get it to return the word onto the page.
2. The relevant arguments to the method is the num, returnValue, newWord, and stri.
3. How does the relevant fieilds of the class change form this specific request:
   - int num: this returns the word count, this did change from the request because this is the second word I added to the list.
     So it changes from 1 to 2.
   - String returnValue: this was already had "1. hello" before the request. Form the number that was incermented, the new string
     added to this string is "2. Money".
   - String newWord: this gets the url and goes to the query to split into an array to be added to return value. This does
     change form the previous one becuase every different word will have a different and new array. THe sole purpose of this it
     call for the first element in the array to be added to the String returnValue.


![Image](https://raw.githubusercontent.com/viviantran706/cse15l-lab-report/main/Screenshot%202023-10-18%20190330.png)
1. Looking at the method it called, it called the first method. Which goes to the second if statment because we called for the
 "add-message" which will slit the query from the '='. This method will just get it to return the word onto the page.
2. The relevant arguments to the method is the num, returnValue, newWord, and stri.
3. How does the relevant fieilds of the class change form this specific request:
   - int num: this returns the word count, this did change from the request because this is the third word I added to the list.
     So it changes from 1 to 2.
   - String returnValue: this was already had "2. Money" before the request. Form the number that was incermented previous, the new string
     added to this string is "3. Dollars".
   - String newWord: this gets the url and goes to the query to split into an array to be added to return value. This does
     change form the previous one becuase every different word will have a different and new array. The sole purpose of this it
     call for the first element in the array to be added to the String returnValue.


------------
# Part 2

```
Private key for my SSH key (on my computer):
![Image](https://raw.githubusercontent.com/viviantran706/cse15l-lab-report/main/Screenshot%202023-10-21%20145957.png)
```
```
Public key for my SSH(in my remote ieng6 account):
![Image](https://raw.githubusercontent.com/viviantran706/cse15l-lab-report/main/Screenshot%202023-10-21%20150026.png)
```
```
Terminal when loging onto my ieng6 account (with being asked for  the password):
![Image](https://raw.githubusercontent.com/viviantran706/cse15l-lab-report/main/Screenshot%202023-10-21%20153405.png)
```
----
# Part 3

Something that I learned that form week 3, was that there is a shortcut to loging on to our ieng6 accoount. Becuase for the pass few weeks I have been doing it through the long way. Where I would have to enter the password the whole time. Through this process, I learned more mkdir .ssh, but more specficiallt abour how mkdir works. I learned that creates a directory with in the current directory which can be a good way to create directories to store more files and other directories.
