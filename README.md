# nus-devops
Day 3 Devops CI/CD Assignment is demo-ed on another repo.

Demo is shown using Jenkins on the repo, but will not be generating any file.

I have used a project I did previous to be updated by Jenkins. The URL to the repo is https://github.com/njw95/main

When there is a new commit that is pushed to the repo, Git will inform Jenkins of the update. Jenkins will authorize and start building the project. By default it should build the jar file, but it is not enabled in this showcase. The reduction in number of queries by Jenkins querying the GitHub server is nullified to reduce load.
