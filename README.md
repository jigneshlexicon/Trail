# Trail
Generate SSH Key and link it to your github account.(Refer:LexiconRepo Guide V1.4, topic-Using SSH Keys.)

The default branch is set to **development**.

### Contributing to this repository.
Team members are given **Read access** to this repository.
You need to fork this repository ,push your work to your fork, and send pull-request to the main repository.
>e.g. a user named User will create a pull-requset as base:LexiconNetworksPvtLtd/Trail---for-yourname head:User/Trail---development

#### Fork the main repository
Open [LexiconNetworksPvtLtd/Trail](https://github.com/LexiconNetworksPvtLtd/Trail).
Fork main repository to your account, now you will have *yourusername/Trail*.
You will be pulling/pushing, from/to your fork. Example urls for your forks will look like
https clone url-https://github.com/yourusername/Trail.git
ssh clone url-git@github.com:yourusername/Trail.git
#### Setting your local environment via git bash/terminal
- Change directory to the desired directory e.g.
```Shell
$ cd d:
$ cd Trail
```
- Initialise a local repository and switch to development branch.
```Shell
$ git init
$ git checkout -b development
```
- Pull the directory structure(initial setup) from your fork(repository) i.e. yourusername/Trail
```Shell
$ git pull <ssh clone url of your fork>
```
- Now, you can see the directories are on your local machine.
- You can now start your work locally, when you are done,
To push your work you need to add, commit then push it to your fork
```Shell
$ git add .
$ git commit -m "<mandatoty commit message here>"
$ git push <ssh clone url of your fork>
```
- Now you just need to create a pull-request for the main repo and contribute with your work.
>e.g. a user named User will create a pull-requset as base:LexiconNetworksPvtLtd/Trail---for-yourname head:User/Trail---development
