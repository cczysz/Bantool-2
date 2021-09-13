<h1>Bantool 2</h1>

<h3>New:</h3>
<ul>
<li>Doesn't need a focused window anymore</li>
<li>Controls its own version of Firefox with multiple instances running in parallel</li>
<li>Keeps track of banned users per channel</li>
<li>You can now set multiple channels to run on</li>
</ul>

<h3>DO NOT USE THE CLIPBOARD WHILE THIS TOOL RUNS (no copy/paste)</h3>

Namelist at: https://github.com/LinoYeen/Namelists

# Installation

This package should be installed using Python >= 3.8. Check your current Python version using `python3 --version` in a terminal window.

If you have the correct Python version, navigate to the `Bantool-2` directory and run:

```shell
pip install .
```

This will install the `bantool` terminal application.

## Windows Installation

<h3>How to use:</h3>
<ol>
<li>Unzip FirefoxPortable.7z</li>
<li>navigate to and open \Bantool-Firefox\FirefoxPortable\App\Firefox64\Firefox.exe</li>
<li>type about:profiles into the URL tab</li>
<li>create a new profile called "bantool" save it in the bantool folder \Bantool-Firefox\ <br>
	If it doesn't create a proper profile folder (looks like ugcmlygs.bantool) create one yourself</li>
<li>open bantool profile new window and if needed, set as default
<li>close and reopen firefox
<li>log into Twitch
<li>close out of firefox again

---
Install Python3.8 from the Microsoft Store: <https://www.microsoft.com/en-us/p/python-38/9mssztt1n39l#activetab=pivot:overviewtab>

Download the Bantool-2 code as a zip file, and unpack.

Double click the `windows_install.bat` file.

First, a virtualenv directory will be created under a `venv\` directory.

Then, a `config.json` file and a `namelist.txt` file will be created, if those do not already exist.

<li><h4>edit the config file:</h4>
<ul>
<li>"twitch_channels": ["NAME OF CHANNEL", "NAME OF SECOND CHANNEL", "NAME OF THIRD CHANNEL"],</li>
<li>"command": true/false,</li>
<li>"Number_of_browser_windows": 1,</li>
<li>"Firefox_profile": "NAME OF PROFILE FOLDER"</li>
<li>"Greeting Emote": the emote it should put in chat once the browser is ready to work</li>
<li>"Chunk size": The number of names after wich a browser window should restart and save its progress (to fix memory leaks)</li>
</ul></li>

<li>The amount of browser windows you should put set is dependent on your computer, but 4 is reccomended</li>
<li>After filling the namelist and setting the config double-click the `windows_run_bantool.bat` file</li>
</ol>


<h3>CVS_Exporter:</h3>
A tool to crudely filter out followbots from your current followers using commanderroots followlist tool (https://twitch-tools.rootonline.de/followerlist_viewer.php) <br>
It will go through the list and if more than 10 people followed in a single second (highly unlikely for normal follows, but common for followbots), it will sort them into the output file

<h3>User_validator</h3>
A tool to filter out users from a namelist if they don't have a valid twitch account anymore

<div>
<h3> If you wanna throw me a few bucks, here is my paypal. (All donations are appreciated but will never be necessary):</h3>
https://www.paypal.com/donate?hosted_button_id=Y6MFY2BENXA2C
</div>
