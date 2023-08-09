THIS IS A SKIN "HACK". IT DOES GIVE YOU CLIENT-SIDED SKINS.

(wip) better inventory manager for valorant, kinda like destiny item manager but not really

Installation/Usage
  1. Download the latest release (executable)
It is recommended that you use the latest release as compatibility is continuously phased out for old versions as development continues.

  2. Run VIM.exe
As long as VIM.exe is running, the randomizer/other features will remain running. The website does not always need to be open for VIM to work. Since VIM is packaged into a single file and requires no installer, it is recommended that you move the executable from the downloads folder to a more accessible location, like your taskbar or desktop.

  3. Open the web client
Open https://github.com/colinhartigan96/valorant-inventory-manager to interact with VIM! You can set favorite skins, manage the randomizer, and change other settings from there.

Building the server from source
Understandably, some people may want to build the client companion (server) on their own machine due to concerns about the unsigned executable... if you know a way around this or a potential way around the false-positive AV detections please reach out on the Discord server.

  1. Clone the repository
git clone https://github.com/colinhartigan96/valorant-inventory-manager
The client/ directory is not used, so feel free to delete it.

  2. Install Python packages
cd server
python -m pip install -r requirements.txt
2.1. (optional) Modify client config debug settings
In /server/src/client_config.py, feel free to mess with the debug settings.

UNLOCK_ALL_SKINS can be enabled to make it appear as if you own all the skins, but equipping them doesn't actually do anything.

  3. Build the server executable
cd server
./build.bat
The executable will be dumped to dist/.

  Features
    Completed
        better inventory UI/UX than VALORANT's native system
        skin favorites, post-match randomizer
        buddy searching, favoriting, randomizing
        loadout profiles with favorite skins per profile
  Planned
        favorite skin/buddy combos
  Contributing
  
If you have improvements or ideas to improve the design or code of the app, please open a pull request with your changes. Planned/indev features are listed on the projects page.

Legal
This project is not affiliated with Riot Games or any of its employees and therefore does not reflect the views of said parties. This is purely a fan-made project to enhance VALORANT's inventory management.

Riot Games does not endorse or sponsor this project. Riot Games, and all associated properties are trademarks or registered trademarks of Riot Games, Inc.
