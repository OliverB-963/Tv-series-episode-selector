# Tv-series-episode-selector
A program built to be able to input the number of seasons and the number of episodes in each season using a Tkinter GUI. Then storing and being able to use the randomiser to provide a season and episode to watch in the show, storing that result to ensure it doesn't show you again

How to run. 
EpisodeSelector is the main file of the program which should be run to open the program

Creating .exe
if you dont already have pyinstaller
run: pip install -U pyinstaller

then locate the directory of Tv-series-episode-selector in a command line and run
pyinstaller --onefile -w EpisodeSelector.py

this will then create a build and dist folder in the directory. The executable will be located in the dist folder
