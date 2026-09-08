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

```
mkdir 25018756
```
<img width="512" height="58" alt="image" src="https://github.com/user-attachments/assets/1598fd69-a1fb-41e4-994f-80addadd27ee" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"
```
rmdir 25018756
```

<img width="667" height="66" alt="image" src="https://github.com/user-attachments/assets/a56d0cab-59a6-4a4f-8682-6b840c841630" />


## COMMAND AND OUTPUT

Create the file Rose.txt
```
COPY CON Rose.txt
A clock in a office can never get stolen
Too many employees watch it all the time
```
<img width="917" height="442" alt="image" src="https://github.com/user-attachments/assets/11e77909-df47-4285-bef7-26159332836c" />


## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection
```
echo "hello world" > hello.txt
```
<img width="700" height="132" alt="image" src="https://github.com/user-attachments/assets/a67f1184-f936-40e3-a70e-33975a665615" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
```
copy hello.txt hello1.txt
```
<img width="632" height="85" alt="image" src="https://github.com/user-attachments/assets/e9e80a0b-a7ef-44d8-bd1e-698aa0b8631d" />



## COMMAND AND OUTPUT

Remove the file hello1.txt
```
del hello1.txt
```
<img width="477" height="50" alt="image" src="https://github.com/user-attachments/assets/c333f632-9048-43f6-8f51-ff2bbf1103ca" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
```
dir hello1.txt
```
<img width="577" height="199" alt="image" src="https://github.com/user-attachments/assets/b0d94290-156d-42d6-80fd-9b285b3b9678" />


## COMMAND AND OUTPUT

List out all the associated file extensions 
```
assoc | more
```
<img width="907" height="1000" alt="image" src="https://github.com/user-attachments/assets/8a53abf5-abf2-4e70-afb3-d0594219579e" />


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
```
fc hello.txt Rose.txt
```
<img width="577" height="240" alt="image" src="https://github.com/user-attachments/assets/64cb0f3e-62f5-404e-b462-98fbbd0df490" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="571" height="172" alt="image" src="https://github.com/user-attachments/assets/f9d54bbf-711b-47bb-8b7b-d312751af92c" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="655" height="237" alt="image" src="https://github.com/user-attachments/assets/b26c6b04-0a24-4ec6-a678-b1c378122d32" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="511" height="190" alt="image" src="https://github.com/user-attachments/assets/522bab97-a69b-401d-bb02-e106d4bac13e" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="477" height="135" alt="image" src="https://github.com/user-attachments/assets/cb3e9436-7b5a-4c72-9e2a-dda03225b1d4" />



Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="640" height="482" alt="image" src="https://github.com/user-attachments/assets/59acc01d-d026-4b24-a83c-66631a342cec" />




# RESULT:
The commands/batch files are executed successfully.
