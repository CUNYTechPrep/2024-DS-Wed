# Week 3; Data Analytics, Dat Viz and BI Tools 


## Agenda 
0. Remind me to 
	* Start recording
	* Turn on CC's 
	* Enable screen sharing for everyone (for breakout rooms)
0. Best way to ask questions on slack. 
    * Include a full screen shot of your error message and you did / the code to get the error.  
0. Review HW  [15min]
    * Review exemplary LinkedIn 
    * Best Slack message. 
    * Share screen HW check, one error you encountered. 
0. [Google Slide Lecture](https://docs.google.com/presentation/d/1Z6SShSi8QSN4px6FbAGc8EO_VcYZ6Lo9a9_ihC8d7lY/edit?usp=sharing) [20min] <---- Update Link
0. BREAK
0. Analytics Lecture.ipynb [45min]
0. Start Analytics HW in Breakout Rooms 
0. Review whats due for next week 
0. Weekly survey. 


# HW DUE [~1.5hrs]

### Pre-Class for Next Week's Lecture [~30min]
0. Pre class stuff
0. Post in Slack thread 1 thing you learned about the video or Tableau. 


### Exercise [~45min]
0. MAKE A COPY of the Exercise file.
0. Complete the questions.
0. Save and push to github
0. Open https://public.tableau.com/
0. Paste link your HW Submission sheet. 

### LinkedIn Post [~10min]
__Submit by putting the link to your LI post under the "LinkedIn Post" column.__

This week, your post can be about something you found and like that is related to your field of interest. 

* Post a video, article, paper or another LinkedIn post you liked say/describe why you liked it. 
    * 'commenting' on another post does not count. 
    * you can repost instead. 
    * Maybe do a poll.


# Updating your Fork
Now that there are new files in the main fork, you will need to pull those files into your fork.


#### Setting upstream
0. Adding upstream.  Run this again just incase
    * `git remote add upstream INSTRUCTOR-ADD-URL-TO-YOUR-REPO-HERE`
	* If it says `fatal: remote upstream already exists.` That is GOOD and means you listened the first time and already added the upstream.

#### Getting new files by pulling or fetching and merging. 
0. Try doing `git pull` that works for 20% of students. 
0. Else, if `git pull` doesn't work...
0. Fetch the new files
	* `git fetch upstream` 
0. Merge/download the newly added files.
	*  `git merge upstream/main`
	* If a crazy screen comes up that looks like this, just type `:wq` then hit `enter` to close it and you should be fine.
    
    <img src="https://github.com/zd123/images-for-class/blob/main/forking-image-instructions/98-strange-screen.png?raw=true" width="55%">  
    
    Just type `:wq` then hit `enter` on your keyboard.  It should close that window. 
0. Now check that the new files are in your repo.
#### Adding the new files into your repo. 
As of right now, the files are on your local machine, but not in your repo yet.  

0. Run `git stuats` and you will see a bunch of new green files.
0. Add all of the files from the new week. 
    * `git add Week-02-DS-Overview-and-Data/*`
    * `git commit -m 'adding week 2 files'`
    * `git push`

<br>
<br>
<br>
<br>

# Finding Data in the Wild

#### Finding Data your project. 
0. Here we are going to mock data for a project about dogs. 
0. Google dog dataset. [google it, find kaggle and data world and stanford and opennyc]
0. Go to the dataworld link, about 5 links down you'll see the dog [NYC Dog Licensing Dataset](https://data.world/city-of-ny/nu7n-tubp). 
0. Point out it was last updated 2021-07-29.
0. Then go the the source, and see the source was updated this year. 
0. In the source, point out the data dictionary and user guide, scroll down to see the column descriptons. 
0. maybe sidetrack on doing one of those evolution trees (how to look how to make one of those evolution trees for dogs)
    * google dog evolution tree data
    * find research gate
    * see realted images
    * see the word 'phylogenetic', thats a new google term you can use. 
    * open paper, use command+f search for 'data' or 'download' 


#### [How I got the data for this lecture]
0. Google, ["pandas data cleaning tutorial"]((https://www.google.com/search?q=pandas+data+cleaning+tutorial&oq=pandas+data+cleaning+tutorial+&gs_lcrp=EgZjaHJvbWUyCAgAEEUYHhg5Mg0IARAAGIYDGIAEGIoFMg0IAhAAGIYDGIAEGIoFMg0IAxAAGIYDGIAEGIoFMgoIBBAAGIAEGKIEMgoIBRAAGIAEGKIEMgoIBhAAGIAEGKIE0gEINTAzNWowajGoAgCwAgA&sourceid=chrome&ie=UTF-8))
0. Open a few links. But end up on the [w3 schools tutorial](https://www.w3schools.com/python/pandas/pandas_cleaning.asp). 
0. Try and get that data. 
    - I did, copy and paste into sublime and did removing whitespace tricks in there. 
    - Then copy and did pd.read_clipboard() which works very well. 
0. Now load that data into the notebook and flow into the data cleaning lecture. 

# HW Assignment
Due 1 day before class at 12:01pm (Noon).

## Pre-Class Videos
1. Watch this 
2. Do this tutorial 


## Exercise
0. Make a copy of the exercise file (see instructions above).
0. Complete the code in your new copy of the exercise file. 
0. Push that file to your fork. 
0. Copy that exact link, and paste it into the HW submission sheet.
0. Create a dashboard in Tableau public that matches the 2 bar charts and 2 tables in your python HW


## LinkedIn Post



### Other shit
[NYC Open Data proposals](https://2025.open-data.nyc/) due Nov 1st.
