# InstagramBot
Based off of Colorscreams grayvee bot. This will pickup posts from the given tag list in info.txt, visit them and like or comment alternatively.
Note: This uses implicit wait statements so a slower network than the one this was designed for will cause the script to timeout and crash.

# Instructions
1. Run CreateFiles.py
2. Create both log and info file
3. Replace username and password with your credentials
4. Set your tags
5. Install the selenium library via pip install selenium 
5. Run script

In order to run it for posting rankings set randomise to False and num_posts to 1

For the same function as the colorscreams video set randomise to True and increase num_posts to your liking

Comments have been divided into sections for their use cases.

The datatype of info is basically a python dictionary and log is a python list(in hindsight a csv wouldve probably been better).

The script will not run unless you have selenium
