## Lab 2 Report - Servers and SSH Keys (Week 3)

![Image](https://raw.githubusercontent.com/viviantran706/cse15l-lab-report/main/Screenshot%202023-10-18%20190330.png)
1. Looking at the method it called, it called the first method. Which goes to the second if statment because we called for the
 "add-message" which will slit the query from the '='. This method will just get it to return the word onto the page.
2. The relevant arguments to the method is the num, returnValue, newWord, and stri.
3. How does the relevant fieilds of the class change form this specific request:
   - int num: this returns the word count, this did change from the request beucase this is the second word I added to the list.
     So it changes from 1 to 2.
   - String returnValue: this was already had "1. hello" before the request. Form the number that was incermented, the new string
     added to this string is "2. Money".
   - String newWord: this gets the url and goes to the query to split into an array to be added to return value. This does
     change form the previous one becuase every different word will have a different and new array. THe sole purpose of this it
     call for the first element in the array to be added to the String returnValue.



![Image](https://raw.githubusercontent.com/viviantran706/cse15l-lab-report/main/Screenshot%202023-10-18%20190342.png)