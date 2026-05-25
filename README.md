<img width="411" height="110" alt="image" src="https://github.com/user-attachments/assets/aadd2409-c33c-4c4b-ac8f-beced9188ddf" /># Windows-basic-commands-batchscript
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

## COMMAND AND OUTPUT

<img width="442" height="97" alt="image" src="https://github.com/user-attachments/assets/aae477aa-89e0-491a-8d03-5adbdc7421ad" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="411" height="110" alt="image" src="https://github.com/user-attachments/assets/162051c8-3dbc-4ed6-b4e0-bb2f703d9b7d" />


Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="696" height="284" alt="image" src="https://github.com/user-attachments/assets/3caa3411-3807-4cdf-b4d7-cf4a2537cba8" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="600" height="117" alt="image" src="https://github.com/user-attachments/assets/403ff3b1-0065-4c48-a9ab-f7ccae3029c5" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="547" height="179" alt="image" src="https://github.com/user-attachments/assets/1bc867d6-592f-47e5-80e5-3e02a2314fef" />

Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="428" height="45" alt="image" src="https://github.com/user-attachments/assets/7e2a4f5e-65c4-4aa2-8de1-2f1fb538fa38" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="506" height="232" alt="image" src="https://github.com/user-attachments/assets/8b7dc4a6-18f2-4db8-b099-314185857368" />

List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="523" height="431" alt="image" src="https://github.com/user-attachments/assets/c1679079-3732-49fb-a4f3-2250dfcf9634" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="532" height="203" alt="image" src="https://github.com/user-attachments/assets/06975518-ad6a-47c6-9324-023aa0bffcba" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


## OUTPUT

<img width="482" height="146" alt="image" src="https://github.com/user-attachments/assets/8c5df2d1-05bc-4867-81a6-b3e9b2cdeb82" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

## OUTPUT

<img width="648" height="337" alt="image" src="https://github.com/user-attachments/assets/99b8f45b-9faa-4f79-aad7-b25fa11b2743" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

## OUTPUT

<img width="467" height="213" alt="image" src="https://github.com/user-attachments/assets/71801bdf-e939-40b1-911a-36c3dd432476" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="614" height="286" alt="image" src="https://github.com/user-attachments/assets/9de9a9cc-ef31-401f-9e55-c806fda632b1" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="469" height="464" alt="image" src="https://github.com/user-attachments/assets/0e9fac54-e091-4119-a676-49046c3501a0" />


# RESULT:
The commands/batch files are executed successfully.

