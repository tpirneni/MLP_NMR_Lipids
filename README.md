# Hayden
Repository for Hayden to add the codes of all the projects. Projects should be managed in separate folders in the repository.

The first thing you need to do is download git bash from: https://git-scm.com/downloads
After installing git bash, use the following commands as per required.
The basic git commands are:
- git clone <repository-url>: Start git bash in the desired folder and use the command <b>git clone https://github.com/tpirneni/Hayden.git</b>. This will download everything from the online repository and setup git local repository in your folder. 
- git add -A: It adds all the changes in you computer to the <b>local</b> git repository. The "-A" option in the command signifies that we want to add all our changes. You can also select specific files to add. Basically, this command selects the changes that we want to send to the git cloud. It just makes the changes ready to be commited. Remember, mostly, you should use the below (git commit) code after "git add -A".
- git commit -m "Message": After selecting the files, this command saves those selected files in the <b>local</b> git repository. The "-m" is a required option for this command. It lets you add a message why you are saving these changes. For eg: you can do <b>git commit -m "Modified Readme by adding description"</b>
- git push: Note in the previous two commands, we were working with <b>local</b> repositories. The changes are saved locally i.e. in you computer but has not been uploaded to the <b>git cloud</b> (online git repository). You should use <b>git push</b> to upload all those locally commited changes to the online repository.
- git pull: This command downloads the latest changes from the <b>online</b> repository to the local repository in your personal computer.
- git status: It helps us to see what changes has been added, commited or pushed. This is a very helpful command.

