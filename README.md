# nus-devops
Day 3 Devops CI/CD Assignment (Jenkins update)

Demo is shown using Jenkins on the repo, but CI can also be run on Git Actions.

When there is a new commit that is pushed to the repo, Git will inform Jenkins of the update. Jenkins will authorize (if repo is private) and start building the project. By default it should build the jar file, but it is not enabled in this showcase. The reduction in number of queries by Jenkins querying the GitHub server is nullified to reduce load.


#Remarks/Extra
I have tested on another repo that consist of a Java Project (https://github.com/njw95/main)
