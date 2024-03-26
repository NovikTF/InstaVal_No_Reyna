# InstaVal
**Valorant fast auto instalocker app WITHOUT REYNA** *Not bannable (march 2024)* 

*I wont be publishing the source code.*

The "InstaVal" is a Python application designed to automate the selection process of agents in Valorant. Coded in python with ChatGPT.


 ## Installation:

**Click Releases, download the installer, and follow the instructions in the wizard setup**


 ## Usage:

* Launch the application.

* Select your desired agent from the dropdown menu.

* Choose your preferred resolution from the dropdown menu.

* Click the "Confirm" button to confirm your selections.

* Press F1 to toggle auto-clicking functionality on or off.

* Additionally you can press "insert" to "bring the app on top" if it got hidden bahind a different window.



 ## Features:

Agent Selection: The application provides a dropdown menu where the user can select their desired agent from a list of available options, including all agents in the game Valorant.

Resolution Selection: Users can choose between resolution options (select the resolution that you use in game).

Toggle Clicking: By pressing the F1 key, the user can toggle the auto-clicking functionality on or off. When enabled, the application automatically clicks on the selected agent's location and the "Lock In" button within the game client. Additionally the script will constantly move the mouse a little bit around the areas of the button locations, to prevent the buttons from "getting stuck" and being unable to click on.

Confirmation Pop-up: After selecting an agent and resolution, the user can confirm their choices by clicking the "Confirm" button. A pop-up window displays the selected agent and resolution for confirmation.




 ## How it works:

**1. Agent Location and Clicking:**

The application contains predefined coordinates for each agent's selection location within the Valorant game. These coordinates are stored in dictionaries, mapping each agent's name to its corresponding (x, y) coordinates on the screen.
When the user selects an agent from the dropdown menu, the application retrieves the coordinates associated with that agent from the dictionary.
To simulate clicking on the agent's selection location, the application uses the pyautogui.click() function, passing the retrieved coordinates as arguments.

**2. Lock In Button:**

Similarly, the application contains predefined coordinates for the "Lock In" button within the Valorant game client. These coordinates are also stored in the dictionary.
After clicking on the agent's selection location, the application simulates a click on the "Lock In" button using the pyautogui.click() function, passing the coordinates of the button.

**3. Mouse Movement:**

The application uses the pyautogui library to simulate mouse movements and clicks.
Mouse movements are simulated by directly setting the mouse cursor's position using the pyautogui.moveTo() function. This allows precise control over where the mouse cursor moves on the screen.
Mouse Movement for Button Locations:

**4. Slight Mouse Movement:**

After clicking on the agent's selection location and before clicking on the "Lock In" button, the application moves the mouse cursor slightly around the area where the button is located.
By periodically moving the mouse around the button area, the application ensures that the game client remains responsive to subsequent clicks and interactions.


*The primary purpose of this mouse movement is to maintain the responsiveness of the game buttons and prevent any potential issues with clicking on the buttons.*




 # External Operation and Non-Responsibility Disclaimer:

**1. External Operation:**

The application operates entirely externally to the Valorant game client. It utilizes mouse simulation to interact with the game's user interface without modifying any game files or injecting code into the game client.
This external operation ensures that the application does not interfere with the integrity or security of the game client itself. Instead, it merely automates repetitive tasks within the game's UI.

**2. Testing and Reliability:**

The application has undergone small testing to ensure its functionality and reliability. Testing includes verifying agent selection accuracy, confirming button interactions, and assessing overall performance across various scenarios.
Through testing, the application has demonstrated its effectiveness in automating agent selection while adhering to the rules and guidelines set forth by the game developers.

***3. Non-Responsibility Disclaimer:***

***Despite the thorough testing and external nature of the application, it's important to acknowledge that the use of third-party tools or applications in online games may carry certain risks.
As the creator of the application, I explicitly state that I am not responsible for any consequences that may arise from the use of the application, including but not limited to account bans, penalties, or restrictions imposed by the game developers or platform administrators.
Users are advised to exercise caution and discretion when using the application, understanding that any actions taken with third-party tools may violate the terms of service or end-user license agreements of the game or platform.
By using the application, users acknowledge and accept these risks and release the creator from any liability or responsibility for any adverse outcomes resulting from its use.***
