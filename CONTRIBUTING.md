# How to Contribute



- Fork this repository 
- Clone the forked repository into local space
- Choose any topic from any language you know and you have to put all the code which you know or you have learn with the comments explaning the code you can upload.
- Paste the code in new file and name it in following format:
  the file should contain name of the code(please choose the names accordingly so that it properly describes the code present inside of it),
and so on create different file but keep in mind that if you know multiple programming languages than you should have to make different folders do not messed up the file(like if you want to put cpp code so put it in one folder 📂) 
- Place your source code file in respective folder (you can create a new folder if it is not present)
- Add and commit the changes. (Please do not make changes in any other file, but if you want to work on bug/improvement then add an issue first)
- Don't forget to add your name, image url, country and the language used in the contributors table in the README.md file
- Generate a Pull Request (Optional: add problem name in the title and url to the problem in description)
- And last Just an easy step, Just follow me and I will follow you too, and just give a star to any of the repo in the profile.
- That's it, you have successfully completed your 1 out of 4 PRs. Well Done!


# How to Sync Forked Repo from Upstream Repo


1. Add the original repository as an upstream repository
```javascript
$ git remote add upstream https://github.com/[Original Owner Username]/[Original Repository].git
```
Hence, in this repository, it would be
```javascript
$ git remote add upstream  https://github.com/Naman9761/All-about-Coding.git
```

2. Fetch all the changes from the repository. Note that commits to the original repository will be stored in a local branch called, upstream/master
```javascript
$ git fetch upstream
```

3. Make sure that you are on your fork's master or working branch
```javascript
$ git checkout [working branch]
```
For example,
```javascript
$ git checkout master
```

4. Merge the changes from the upstream/master into  your local master or working branch. This will sync the fork's master branch with the upstream repository without losing your local changes. If you have made any changes that create conflict, you will have to resolve the conflict before you can complete the merge
```javascript
$ git merge upstream/master
```

5. At this point, your local branch is synced with the upstream/master branch. In order to update the remote branch in Github, you need to push your changes
```javascript
$ git push origin master
```
