# Queue Assist

Queue Assist is a League of Legends auto queue acceptor and champ select team reveal tool.  

This script utilizes the League of Legends LCU (League Client Update) API to automate the acceptance of ready checks during queue as well as auto start queues. Additionally, it pulls up teammate stats on u.gg for quick reference during champion selection.

## How to Use

1. Clone the repository to your local machine.
2. Make sure your League of Legends client is open.
3. Run the provided GUI script.
4. Toggle the button to enable the script.
5. Queue up for a game.

Once the script is toggled on, it will automatically start your queue if you are in a lobby. For ranked lobbies, you must input your position prefernce first. After matchmaking starts, it will accept all ready checks that appear during champion select. Then, following a short delay, it will open u.gg multisearch to display the stats of your teammates for quick reference.

## UPDATES 
v1.1 
- Checkboxes have been added for auto queue acceptance and champ select reveal so the user can have optionality in these areas
- Cosmetic GUI updates
- Auto matchmaking start functionality was added - once user makes a lobby script will automatically search

## Future Additions

This script can benefit from the following additions and improvements:

Error Handling: Improve error handling to effectively capture connection errors, handle potential issues in finding the configuration file, and address other possible error scenarios.

Executable or Batch Functionality: Provide a method to package the script as an executable file or a batch file, enabling easy execution without the need for Python installation. This would allow users to run the script with a simple double-click.

Enhanced GUI and Customization: Enhance the graphical user interface (GUI) to offer a more intuitive and user-friendly experience. Consider incorporating additional options and settings for customization based on user preferences.

Auto Play Again/Requeue: Extend the script to include an auto play again or requeue feature. This enhancement would enable users to automatically queue up for another game once the current one ends. It simplifies the gameplay experience by eliminating the need for manual interaction between matches.

Feel free to explore and customize the script further to meet your specific needs and preferences. Any feedback, contributions, and improvements are welcome.
