# CSE15L LAB 4 REPORT 

For the lab report this week, I am going to reproduce the task from above on my own. For each numbered step(so steps 4-9), I will take a screenshot,
and write down exactly which keys I pressed to get to that step



**Log into ieng6**

For this step, you just need to type in "ssh" + your cs15L usernmane. 
Then you'll be asked to enter your password to fully login to ieng6.

Command
``` 
ssh cs15lsp23eo@ieng6.ucsd.edu <enter>

 ``` 

Output

![Image](ieng6.png)



**Clone your fork of the repository from your Github account**

For this step, you'll want to access your github account on your internet browswer. 
Find the lab 7 repository and fork it. Then once you have a copy of the repository. Now copy the url of YOUR lab 7 repository.  
Then go the VS Code and enter this command

Example 1 

Command
``` 
git clone "url" <enter>

 ```
 Output
 
![Image](gitClone.png)
 

**Run the tests, demonstrating that they fail**

For this step, since the code already fails, all we need to do is run the test. 
Todo that, we must enter this command. 

Command
``` 
bash test.sh <enter>

 ``` 

Output

![Image](testFail.png)


**Fix the Error**

For this step, we are already told where the error is and how to fix it. Rather than going to trying to open the file on a text editor. 
We are going to use the command "vim" along with the file that we want to open.  
Then we are goin to going to click <i> to start editing the file. 
To fix the error we need to change the variable "index1" to "index2" underneath the comment line. 
Once you are done editing click "esc" then ":wp"

Command
``` 
1. vim ListExamples.java <enter>
2. "fix the error" 
3. <esc>
4. :wp <enter>

 ``` 
Output

![Image](fixCode.png)

**Run the tests, showing that they pass now**

For this step now all we have to do is call bash test.sh again. 
Which we can call by clicking the up arrow twice and then clicking enter

Command
``` 
<up> <up> <enter>

 ``` 
 Output

![Image](testCleared.png)
 
 **Push to GitHub**
 
 For this step, you just ened to write these three commands and then you'll have your code push and commited to your gitHub account. 
 
 Command
``` 
git add ListExamples.java
git commit -m "commit message"
git push 

 ``` 
 
 THE END
 
