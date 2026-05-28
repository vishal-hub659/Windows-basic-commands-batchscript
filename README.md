# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"
<img width="596" height="101" alt="image" src="https://github.com/user-attachments/assets/9f5a01a9-47c4-40db-b8cc-6feafb8b986d" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="478" height="36" alt="image" src="https://github.com/user-attachments/assets/48c091f3-70cf-4887-9ee1-2658854411af" />


## COMMAND AND OUTPUT


Create the file Rose.txt
<img width="445" height="32" alt="image" src="https://github.com/user-attachments/assets/09d2ec14-1263-46c4-855c-ce48ed668753" />

## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection
<img width="501" height="42" alt="image" src="https://github.com/user-attachments/assets/7fac7860-5f57-482f-af8f-c119d7745426" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
<img width="519" height="68" alt="image" src="https://github.com/user-attachments/assets/45151205-0cbf-45f0-8c2c-c208c823370c" />

## COMMAND AND OUTPUT

Remove the file hello1.txt
<img width="400" height="33" alt="image" src="https://github.com/user-attachments/assets/0026f363-d887-4289-97d1-ba75d3cee1ca" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
<img width="451" height="78" alt="image" src="https://github.com/user-attachments/assets/724fed91-0784-4de2-acab-d6d053328c7a" />

## COMMAND AND OUTPUT

List out all the associated file extensions 
<img width="555" height="674" alt="image" src="https://github.com/user-attachments/assets/23b3c24c-8528-4726-83a4-4780e2d1138d" />

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
<img width="500" height="149" alt="image" src="https://github.com/user-attachments/assets/93aa15a8-8aca-4cba-882e-95542afbd23b" />



## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="489" height="78" alt="image" src="https://github.com/user-attachments/assets/20770bf0-5c57-4825-a547-bad4c6549a53" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.




## OUTPUT
<img width="602" height="172" alt="image" src="https://github.com/user-attachments/assets/3b58e88f-405f-4e93-987e-e28814a4c509" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="499" height="192" alt="image" src="https://github.com/user-attachments/assets/5786cfa1-8e96-42e3-a90f-58a4564f8785" />





Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):



## OUTPUT
<img width="455" height="69" alt="image" src="https://github.com/user-attachments/assets/a4112869-927d-42ec-a535-621576c02fcc" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="274" height="152" alt="image" src="https://github.com/user-attachments/assets/12381db1-ab29-4acd-9495-62c310f78855" />



# RESULT:
The commands/batch files are executed successfully.

