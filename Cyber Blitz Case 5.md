
# Test Case 5 - functional test of the Main Menu (scene 02_MainMenu) when loaded from a paused game and game setup (loaded from scenes testing both keyboar-moause and game controller input
### Team_E(xcellence) G. Broughton, B. Heath, T. Womack
### 10/24/17
### Ver. 0.8
* Test Case ID:
  * 005
* Test Case Name:
  * 005 - Functional test of the MainMenu (Scene 02_MainMenu)
* Component: 
  * Game Main Menu scene - 02_MainMenu
* Test Case Designer:
  * Travis Womack
* Creation Date:
  * 10/17/2017
* Modified By:
  * Travis Womack
* Modified Date:
  * 10/24/2017
* Requirements Covered:
  * The user can make perform desired actions on the menu: Play, Quick Play, Controls, Settings, Quit and Credits
* Test Description/Purpose:
  * Perform detailed functional tests on Cyber Blitz game 02_MainMenu when accessed from a paused match/game
  * Main Menu test the button functionality and navigation of this scene
* Pre-Test Conditions:
  * Current build of the game will run on Windows 7 and 10 in a standalone environment.
  * The PC has both a game controller and mouse attached.
  * Game started normally, user stated match, paused match and clicked the Main Menu button on the Pause panel.
## Test Steps: 
####  Main Menu (02_MainMenu) Main Menu and all buttons function
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Click 'Play' | Display transitions to the game setup scene (03_GameSetup) "Choose Yout Blitzer" panel | √ |			
| 2 | Click 'Quick Play' or press controller A | Go to the default scene (Cave Arena) and play the default match | √ |			
| 3 | Click 'Controls' or press controller A | Drops a 'Help' panel that explains the controls | √ |
| 4 | Click on 'Close' or press controller A | 'Help' panel raise from screen | √ |
| 5 | Click 'Settings' or press controller A | Drops a Settings panel that allows the user to change some settings | √ |
| 6 | Click on 'Close' or press controller A | 'Settings' panel raise from screen | √ |
| 7 | Click 'Credits' or press controller A | Drops a panel with game credits and copyrights | √ |	
| 8 | Click on 'Close' or press controller A | 'Settings' panel raise from screen | √ |
| 9 | Click 'Quit' or press controller A | Exits the application | √ |			

## Overall Test Status:
was able to load the menu from the pause mode, but help did not load. All other systems were good.

## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | Dec /3/2017 | Gbroughton | Passed Test - Help menu didn't  load  |			
| 2 | | | |			
| 3 | | | |	

