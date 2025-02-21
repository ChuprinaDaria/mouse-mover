# mouse-mover
Mouse Mover Bot is a script designed to automatically move your mouse cursor at regular intervals, keeping you active in apps like Microsoft Teams, Zoom, Skype, or any other platform that monitors user activity.
🖱️ Auto Mouse Mover Script
This Python script uses pyautogui to automate mouse movement. It continuously moves the cursor in a square pattern, preventing the computer from going idle. It's useful for keeping the system active during long-running tasks.

Features:

🔄 Moves the mouse diagonally by 100 pixels and returns it to its original position.
🛑 Built-in fail-safe: Move the cursor to the top-left corner (0, 0) to immediately stop the script.
⏱️ Adjustable delay between movements to control the speed of the automation.
🚪 Allows manual termination with Ctrl + C.
How to Use:

Install required libraries:
bash
Kopiuj
Edytuj
pip install pyautogui
Run the script:
bash
Kopiuj
Edytuj
python mouse_mover.py
Stop the script:
Move your mouse to the top-left corner of the screen.
Or press Ctrl + C in the terminal.
Dependencies:

pyautogui for mouse control
time for managing delays
Use Cases:

Prevent your computer from going to sleep.
Simulate user activity for long-running processes.
Warning:
The fail-safe feature helps stop the script quickly, but always use with caution, especially on systems where automated movement could interfere with other processes.
