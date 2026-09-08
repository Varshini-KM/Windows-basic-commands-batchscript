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
mkdir 24900165
```
<img width="490" height="58" alt="Screenshot 2026-09-05 150233" src="https://github.com/user-attachments/assets/31392eed-b285-420f-907e-d8f68493e1fd" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"
```
rmdir 24900165
```

<img width="667" height="61" alt="image" src="https://github.com/user-attachments/assets/580c4a2d-5b09-4a26-871e-a7e1a5b2df43" />


## COMMAND AND OUTPUT

Create the file Rose.txt
```
COPY CON Rose.txt
A clock in a office can never get stolen
Too many employees watch it all the time
```
<img width="917" height="392" alt="image" src="https://github.com/user-attachments/assets/e0e8cd9c-c077-4448-90e0-2785425413be" />


## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection
```
echo "hello world" > hello.txt
```
<img width="700" height="102" alt="image" src="https://github.com/user-attachments/assets/9136f797-d499-49cc-b13e-d9ddeda77745" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
```
copy hello.txt hello1.txt
```
<img width="632" height="91" alt="image" src="https://github.com/user-attachments/assets/fc3632f9-a8be-4180-b237-a9b45e1bb022" />


## COMMAND AND OUTPUT

Remove the file hello1.txt
```
del hello1.txt
```
<img width="477" height="57" alt="image" src="https://github.com/user-attachments/assets/d3d96eee-de2a-48a0-8c9a-da8f8b697240" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
```
dir hello1.txt
```
<img width="577" height="150" alt="image" src="https://github.com/user-attachments/assets/a8b80748-75d9-47ef-a70a-4c0892e7b086" />


## COMMAND AND OUTPUT

List out all the associated file extensions 
```
assoc | more
```
<img width="907" height="912" alt="image" src="https://github.com/user-attachments/assets/6897c768-8d36-4782-a043-1c4d8a76748c" />


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
```
fc hello.txt Rose.txt
```
<img width="577" height="240" alt="image" src="https://github.com/user-attachments/assets/e2a8d5a3-9fa0-46e4-8f24-920da135a37f" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="571" height="172" alt="image" src="https://github.com/user-attachments/assets/bf0d1593-5e50-4e01-afd4-f10514213cd2" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="655" height="237" alt="image" src="https://github.com/user-attachments/assets/74f8d20d-0d79-4a53-838d-e98bfc1bd0d7" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="511" height="190" alt="image" src="https://github.com/user-attachments/assets/48016707-9255-439e-b42e-a01993acc42d" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="477" height="95" alt="image" src="https://github.com/user-attachments/assets/f579d24d-1546-49fe-8003-242815e6e920" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="640" height="422" alt="image" src="https://github.com/user-attachments/assets/a51175ab-f278-4909-91f2-d006a1b8895c" />



# RESULT:
The commands/batch files are executed successfully.
