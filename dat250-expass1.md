
# Software Technology Experiment
The tutorial for deploying Java applications on the Heroku cloud platform includes all the commands used, so I see no need to include every command I wrote in this report. If you have questions about how I performed a task please see the [tutorial.](https://devcenter.heroku.com/articles/getting-started-with-java)

# Technical problems during installation
I didn't encounter many problems during the installation of the software development environment. The only problems i got where the usual "... is not recognised as a cmdlet" right after installation of java and maven, but this was easily fixed by refreshing the environment or restarting windows. This is also closely related to [the validation of the SDE.](#validation-of-sde) I allready had VSCode which I used as IDE and git which required no further attention.

# Validation of SDE

To validate my software development environment I used the normal commands like:

```console
$ java -version
$ mvn -version
$ heroku version
```


to show what version was insatlled or if there was anything installed at all. This also got confirmed during the tutorial when `mvn clean install` worked perfectly. ***Build success***!!!

# Heroku problems
I did not encounter any problems exept the ones I explain in [pending issues.](#pending-issues) Heroku worked as expected during the whole tutorial.

# Pending issues
The [addons part](https://devcenter.heroku.com/articles/getting-started-with-java#provision-add-ons) of the tutorial required a verified account connected. This verification was done with connecting a credit card to the account used, this made me skip this step as I saw no need to give them my credit card just yet.

The [Use a databse](https://devcenter.heroku.com/articles/getting-started-with-java#use-a-database) part of the tutorial required one to have Postgres installed locally which I also chose to skip as I assumed it would work if I had Postgres installed.

