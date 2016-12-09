# PollUp
Repo for the PollUp polling website 
To Run: npm start
Browser Address: http://localhost:3000

Instruction: go to http://localhost:3000
Click "Create Poll" to create a poll. The poll will be saved into polls-data.json in public folder.

Go to http://localhost:3000/landingPage.html
Click "Create Poll" to create a poll. The poll will be saved into polls-data.json in public folder

For all the sortPages html files inside public folder, it fetches json files from the server, then process the data.

For the resultPage.html, we weren't able to make it work, but we do have a demo of how voting work. The template html: testVote.html send a POST request to the server and make changes to the vote counts in the JSON file.

If the directory does not exist, it gets routed to 404.html