# !!! Github + Jenkins + Docker !!!

## Task Descrition

# JOB#1
If Developer push to dev branch then Jenkins will fetch from dev and deploy on the dev-docker environment.
# JOB#2
If Developer push to master branch then Jenkins will fetch from master and deploy on the master-docker environment. As they both dev-docker and master-docker environments are on different docker containers.
# JOB#3
Manually the QA team will check (test) for the website running in the dev-docker environment. If it is running fine then Jenkins will merge the dev branch to master branch and trigger #job 2