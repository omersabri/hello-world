Describe the difference between fetch and pull and show (briefly) how each would be used. AC3.4
git fetch only downloads the latest data from the remote repository; it does not modify your local working files.
git pull does two things in one step: it downloads the data (fetch) and then automatically merges it into your current local branch (merge).