# CSE15L LAB 5 REPORT 

For the lab report this week, I am going to replicate an EdStem conversation that a student and a TA would have. 

**Part 1**

**Student**

Hello, I'm using a mac operating system, and I'm coding on VS Code for Lab 3. I'm not sure my code is failing the test. 
I created a test.sh file to test my files when I call <bash test.sh> on the bash script. 

Heres my code
![Image](errorCode.png)

Heres my test.sh file 
![Image](commandSH.png)
 
Heres my output
![Image](errorTest.png)
 
Command
``` 
ssh cs15lsp23eo@ieng6.ucsd.edu

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
git clone <url>

 ```
 Output
 
![Image](gitClone.png)
 

**Run the tests, demonstrating that they fail**

For this step, since the code already fails, all we need to do is run the test. 
Todo that, we must enter this command. 

Command
``` 
bash test.sh

 ``` 

Output

![Image](testFail.png)


**Fix the Error**

For this step, we are already told where the error is and how to fix it. Rather than going to trying to open the file on a text editor. 
We are going to use the command "vim" along with the file that we want to open.  
Then we are goin to going to click <i> to start editing the file. Once you are done editing click <esc>

Command
``` 
vim ListExamples.java

 ``` 
Output

![Image](specNamelab3.png)

The "-name 'Annual_fee.txt'" allowed the user to find exact file within the directory media.


Example 2

Command
``` 
find Post_Rate_Comm/* -name 'Cohenetal_comparison.txt'

 ``` 
Output
![Image](nameComLab3.png)

The "-name 'Cohenetal_comparison.txt'" allowed the user to find exact file within the directory media.


Source: ChatGPT

