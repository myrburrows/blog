---
title: "Ooli Project Post"
date: 2023-09-10T10:32:56-05:00
draft: false
---
Welcome to the Ooli project.
<!--more-->
# I.  Prerequisites
### A.  Microsoft Visual Studio Code 
 1.  INSTALL on your local Windows PC.  Provides both editor and terminal.
### B.  git
 1.  INSTALL on your local Windwos PC.
### C.  GitHub
 1.  CREATE a GitHub account

   
# II Create the Ooli project
### A. GitHub
 1. CREATE or LogIn to your personal GitHub account
 2. CREATE a new empty repo named Ooli
 3. COPY the Quick Setup string (a URL) for this repository
  NOTE: https://github.com/myrburrows/Ooli.git
### B. VS Terminal
 1. cd ~/Downloads/repos/
 2. git clone https://github.com/myrburrows/Ooli.git
 3. git status
  NOTE: "on branch main"
 4. cd ~/Downloads/repos/Ooli
### C. GitHub
 1. Download the 3 files from https://github.com/myrburrows/Ooli/
  NOTE: index.html, styles.css, and app.js
  
# III. Create the app
### A. VS Editor
 1. OPEN  folder ~/Downloads/repos/Ooli
 2. EDIT index.html
 3. ADD content to the 3 files per the "Ooli files" tab
 ### B. VS Live Server
 1. RUN "Live Server" to open the Ooli app in a tab of your browser
 2. TRY the Ooli app in all its many facets
  
# IV. Deploy on GitHub
### A. VS Terminal
 1. git add .
 2. git commit -m "initial commit"
 3. git push origin main
### B. GitHub
 1. INSPECT on GitHub.  Note that the 3 files are in the online repo.
 2. Click on Settings, then Pages on the left
 3. DEPLOY from a branch (main), and Save
 4. CLICK link at "Your site is live at ____", appears after a couple of minutes