## What is inside JIRA Stack?
* [JIRA Server](https://hub.docker.com/r/matisq/jira-server/) + sidekick with volume data
* Postgres Database + sidekick with volume data

## Info
* In default JIRA stack will create `jira` postgres database with `jira` user.  
* Additional variables `http_proxy` and `https_proxy` are included, which can be helpful in some cases.
* Once JIRA Server will start, make sure you setup correct information in setup page.
* For easy upgrades there are sidekicks for both Postgres and JIRA Server with dedicated storage.
