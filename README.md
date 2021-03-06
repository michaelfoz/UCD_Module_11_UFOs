# UFOs
Please view this link for my GitHub Page which hosts the Module 11 Challenge (Deliverable 1): https://michaelfoz.github.io/UCD_Module_11_UFOs/

Collectively, I have all of my files that I worked on throughout Module 11 in my 1st UFOs repository, and I have my actual project uploaded into my 2nd repository (UCD_Module_11_UFOs).

(My UFOs repository: https://github.com/michaelfoz/UFOs)


To avoid confusion, I created a this (2nd) repository for the Module 11 Challenge (I named this repository "UCD_Module_11_UFOs"). 

Deliverable 1 has instructions to rename the original app.js (which was created throughout Module 11) to app_1.js, 
and to rename the ufo_starterCode.js file to app.js for the Module 11 Challenge. 

Initially, I created a separate folder in my 1st repository [UFOs](https://github.com/michaelfoz/UFOs) that I named "[Module 11 Challenge](https://github.com/michaelfoz/UFOs/tree/main/Module%2011%20Challenge)" because I wanted to keep the files I worked on throughout the module separate from the new files that would be created/used for Deliverable 1. 
I wanted to keep them separate because I put in notes/comments within each files that would help me keep track of the changes/progression I made throughout the module and better understand the code.

I ran into the problem of not being able to specify or tell my GitHub Pages that I wanted to display or host my Module 11 Challenge folder and the finished index.html file it contains onto my website, which is why I created this 2nd repository (UCD_Module_11_UFOs). 
I tried to follow the instructions in this link ([Configuring a publishing source for your GitHub Pages site - GitHub Docs](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)), but I still could not understand what to do.

After creating a new GitHub Pages for this repository, I was able to see that the GitHub Page was displaying my finished project. (Please let me know if there is a specific way to choose a root/docs in GitHub Pages).

# Overview
In Module 11, we learn about a front end development language, JavaScript.  This language is used to add functions and customizations (in this case, a dynamic webpage wherein a user is able to enter search criteria into a field, which prompts the webpage to load results that match the entered criteria). All of the data is initially stored in the JavaScript file data.js in the form of a list (var data = []). The JavaScript file app.js builds a table from this list. All of the data is displayed in the script of the html.index file which references both the data.js file and the app.js file.

# Results
Using the webpage is straight-forward and user-friendly. On the left-hand side of the webpage are fields or input boxes wherein the user can enter a date, a city, a, state, a country, or shape. When pressing "enter," the webpage then loads the data from the data.js file with what the user enters.

![screenshot](https://github.com/michaelfoz/UCD_Module_11_UFOs/blob/main/UFO_Finder_State_Filter.png?raw=true)

Below, is an example of what the webpage loads when the user enters "ar" when searching a specific state.

![screenshot](https://github.com/michaelfoz/UCD_Module_11_UFOs/blob/main/UFO_Finder_State_Filter_ar.png?raw=true)
# Summary

Though the webpage is up and running, it could be more helpful to the user if there were a list of options to choose from when it comes to entering search criteria. The html.index file could be edited do display these options for the user.

The script also seems to be case-sensitive. In the image above, the user would have to type ar (for Arkansas) exactly in lowercase, otherwise nothing would populate or load on the webpage.  Additional script could be added so uppercase as well as lowercase entries are accepted when the user enters their search criteria into the field(s)/input boxes.
