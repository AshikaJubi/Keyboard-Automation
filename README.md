
# Exercise-9 Keyboard Automation - Simulate Keystrokes

### Reg No : 212221040020


## AIM: 
 To automate typing and keyboard shortcuts in a desktop application (Notepad) using UiPath to simulate keystrokes, specifically typing a message and saving the file.
## Activites Required:

  1.Start process
  2.Use Application/Browser
  3.Type Into Activity
  4.Send Hotkey Activity
  
## Procedure:

1.   Open Notepad on your computer.

2.   Open UiPath Studio and create a new project called KeyboardAutomation.

3. In the  Activities Panel  , search for Start Process and drag it into the   Designer Panel  .

4. Set the FileName property to notepad.exe.

5. Add a Type Into activity after Start Process and indicate the area in notepad to type.

6. In the Type Into properties:
   - Set the Text property to "This is an automated typing example.".
   
7. Add a Send Hotkey activity to perform a save operation:
   - Set the Hotkey to Ctrl + S.

8.   Save and Run the workflow.

     
      
## Workflow:
![image](https://github.com/user-attachments/assets/b0fb9ce0-5f76-43a8-bfc9-3f491201ada0)




## Output:
![image](https://github.com/user-attachments/assets/68f41013-16a0-4d7d-97d6-509a444b2a5d)



## Result:
  Thus, the workflow that automatically types the text in notepad  is implemented successfully.
