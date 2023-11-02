## Lab Report 3 - Bugs and Commands (Week 5)

# Part 1- Bugs

A input that produces a failure

`


public void testReverseInPlace() {
    int[] input1 = { 3 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 3 }, input1);
	}

 
`

Input that does not produces a failure:
`
public void testReversed() {
    int[] input1 = { };
    assertArrayEquals(new int[]{ }, ArrayExamples.reversed(input1));
  }
`

![Image](https://raw.githubusercontent.com/viviantran706/cse15l-lab-reports/main/Screenshot%202023-04-20%20123739.png)
`
The symptom of the array was it was in the wrong order, In the photo above we see that in ReverseInPlace method failed beycase of the test from the filure-inducing out cut.
`


Coding before the change:

![Image](https://raw.githubusercontent.com/viviantran706/cse15l-lab-reports/main/Screenshot%202023-04-23%20185324.png)


The coding after changes:

![Image](https://raw.githubusercontent.com/viviantran706/cse15l-lab-reports/main/Screenshot%202023-04-23%20185700.png)

# Part 2
Looking at teh command find. The 4 intresting command line options to use these commands are: 
-name , -type, -perm, and -user. Following the general syntax of fine, which is 
`
find [options] [path] [expression]
`

```

Looking at -name, this command prompt tells the find command to search for the file by its name
and what ever it is followed by that is the name that the find command will search for.

For exmaple, from the files and directories form ./technical:
`
find ./technical -name "reports*"
`
This will find all the files in the **./technical** directory that starts the name reports. This is
really useful when searching through a huge directory for files that starts with a certain name.

`
find ./technical -name "*"
`
This would fina all the fiels in the **./technical** with out any type of specification.
The point of htis command prompt isto search for all the files in the **./technical** directory 
This is good to retreieve all the iteam in the directory.

```
