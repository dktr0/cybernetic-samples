# cybernetic-samples

CC0 sample bank created by the Cybernetic Orchestra

## Instructions for Contributing

Important: Please ensure that all samples you contribute are samples where you are 100% sure that either (a) you are the original creator and thus copyright holder, or (b) the samples are are clearly and verifiably in the public domain. Consider adding a .txt file to any folder you add briefly indicating how the samples were produced.

- Create an account on github.com (just once).

- Fork the repository by going to the central copy of it on github at https://github.com/d0kt0r0/cybernetic-samples and clicking on the Fork button (just once).

- Clone *your*copy* of the repository from github to a computer in your posession. For example:

```
cd ~
git clone https://github.com/yourUserNameOnGithub/cybernetic-samples.git
```

- Add sample folders and files to the cybernetic-samples folder on your computer (if you follow the instruction above exactly, it will be in your home folder).

- To share changes with others, first check what differences exist in your folder:

```
cd ~/cybernetic-samples
git status
````

- If the list of changed files from git status looks right, add them all to a pending commit (terminal code here assumes you are still in the cybernetic-samples folder):

```
git add .
```

- By contrast, *if* the list isn't completely right, you can get around this by adding the right things one by one:

```
git add someSampleFolder/someSoundFile.wav
```

- After you've added, wrap that up as a "commit" with a descriptive message and push it to your github.com copy of the repository:

```
git commit -m "a message describing what you are changing/adding"
git push
```

- Go on github.com, to the page about your copy of the repository, and click pull request. dktr0 will get a message about it and will be able to merge it with the central copy.

- To get an updated version of the central copy from time to time, you must first have added + committed any of your own changes, then:

```
cd ~/cybernetic-samples
git pull https://github.com/d0kt0r0/cybernetic-samples.git main
```
