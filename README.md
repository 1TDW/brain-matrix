# How to contribute

### Requirements
Make sure these are installed:
- node
- npm
- git

I am using parcel, so if you dont have that installed run this command:
`npm install -g parcel`

### Git
Click a button which says "fork" which makes a clone of the repository
It should be somewhere on the top right

Then in your forked repository, click the "code" button
Copy the url under the HTTPS tab
Clone the project into a directory
`git clone <url>`
If it doesnt work then use the url of your forked repository
Then go into the project directory

Before continuing make sure your remote is working right
This should be automatically done by git, but you never know...
`git remove -v`
If theres no remote then do this
`git remote add origin <url>`

Make a new branch
`git checkout -b <branch name>`
Name it something like "new-features"

Now you can make changes to the files, and to test the changes you can run this command
`parcel src/index.html`

When you like your changes, you should commit, which is basically another word for save

First add all your modified or added files to the commit
`git add .`
Then commit
`git commit -m "your message here"`
And to add all your commits to your repository, you have to push with this command
`git push origin <branch name>`
If it gives you an error, try this instead:
`git push -u origin <branch name>`
If that gives you an error too, wait for a few minutes and try again
If theres still an error, then I dont know ask chatgpt or something

Finally, to request to add your changes officially, find a button which says pull request
Do all the things it asks you to do until you see another button which says "create pull request"