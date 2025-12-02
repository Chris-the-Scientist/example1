# Notes on using Github
## Uploading onto Github
- initiate an file using git init "name"
- move into the directory of choice.
- add markdown file using git add 'readme.md'. This puts file into staging area.
- Commit the file with added message using git commit -m 'message'.
- On Github start a new repository and copy the URL.
- Utilize git remote add origin with the URL in the terminal window.
- use git push u- main, (master is not supported any longer).
- At this point you may need to generate a classic token and utilize the url: https://"token"@github.com/"name"/"repo"
- Upload this new url onto terminal window with git remote add origin.
- Now try git push u-main again, enter in your username.
- Then in the password copy the token.
- Wala you should have uploaded your first Github project.

## Branching
- git branch allows you to add a branch into the directory you are currently in.
- git branch alone will show you the branches with a * and highlighted text indicating which branch you are currently within.
- git checkout 'name' allows you to access the new branch of your choice.
- using open 'readme.md' allows you to open the markdown file associated with the uploaded Github repo.
- once you edit and save the markedown file in your notebook (mine is pulsar), you can add and commit that markdown file.
- Lastly, using git push origin 'name' will push the updates up onto Github for you to view your new branches.
