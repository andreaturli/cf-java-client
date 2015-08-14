# Tools We Use

For team:

* Email and groupware: Google apps for business
* Docs: Google docs, Github markdown/wiki, markdown in projects, Atlassian Jira (older stuff)
* Chat:
  *(please tune in to all of these ... you get used to it!)*
  * Skype - person-to-person
  * gitter.im - internal private, customer private, some public)
  * IRC - #brooklyncentral public chat

For dev:

* Code: public and private Github accounts; some (older projects) use our own svn or Atlassian SVN/git (older)
* CI: cloudbees, our own jenkins servers
* Repository: Sonatype, and our own Artifactory (not much anymore?)
* IDE: up to you, blend of Eclipse and IntelliJ mostly (with IJ licenses available for Apache Brooklyn)


# A New Employee should...

* Update [Team Contact Info](https://docs.google.com/a/cloudsoftcorp.com/spreadsheets/d/1G3Jzhc7DqgwroBgu4XYKo167O40ltb2VRRKNgFUgc6U/edit?usp=sharing)

* Add public key [here](https://docs.google.com/a/cloudsoftcorp.com/spreadsheets/d/1VeayXm3AQNAHd97Ssb0t8EWKg1SxWwiwhfI5y0jfMq4/edit?usp=sharing)

* Join Gitter:
  * https://gitter.im/cloudsoft is a PUBLIC room (shared with some of our clients)
  * https://gitter.im/cloudsoft/cloudsoft is a PRIVATE room (Cloudsoft team only)

* Join the Apache Brooklyn community:
  * Subscribe to the "dev" list by sending a blank email to [dev-subscribe@brooklyn.incubator.apache.org](mailto:dev-subscribe@brooklyn.incubator.apache.org)
  * Join the IRC channel: `#brooklyn` on Freenode, OR the channel is mirrored to a [Gitter room](https://gitter.im/brooklyncentral/brooklyn)

* Browse these docs, Google docs, company github, Apache Brooklyn and set up the tools listed above, ensuring you have access (someone has done the instructions below!) and they kinda make sense; ask in Gitter if questions, and update this page if needed

* Read the [company handbook](Company Handbook)

* File an ICLA with Apache. [Instructions here](File-an-ICLA-with-the-Apache-Software-Foundation).

* For company-paid software and services (asking, buying, then expensing if you need something), update [the inventory tracker](https://docs.google.com/a/cloudsoftcorp.com/spreadsheets/d/1USPTY37bXWWU_rd9hnt3ZXHCPjfg9BcZXppiNVamFpY/edit?usp=sharing)

* For company-issued laptops:
  * update [the inventory tracker](https://docs.google.com/a/cloudsoftcorp.com/spreadsheets/d/1USPTY37bXWWU_rd9hnt3ZXHCPjfg9BcZXppiNVamFpY/edit?usp=sharing)
  * create a standard cloudsoft admin user `cloudsoft/1c3gsd0104`
  * create the user for you, usually also as admin, and set up all the software you need (following Brooklyn build instructions at brooklyn.io is a good starting point)
  * to use Time Machine backups, see [instructions here](https://github.com/cloudsoft/cloudsoft/wiki/Time-Machine-Backups).

As the information above changes, i.e. you move or get a new machine or software, update the above.


# To onboard a new employee, Cloudsoft should...

* Create a new Google Apps account [here](https://www.google.com/a/cpanel/cloudsoftcorp.com/Organization#Organization)
  * Also add the user to relevant groups [here](https://www.google.com/a/cpanel/cloudsoftcorp.com/GroupList)
  * Add account to Calendar (TODO - shouldn't this work automatically with groups above?)
  * Add account to Docs (TODO - shouldn't this work automatically with groups above?)

* Add employee's github account to Cloudsoft team at `github.com/cloudsoft` (this enabled them for Gitter also)

* Edinburgh office access:
  * Request a swipe card from `reception@thisiscodebase.com`
  * Get a key made
  * Forward alarm information (or add it here and update the above)

* Issue AWS credentials, point the person at the Wiki with cloud credentials, inform of SoftLayer is the preferred cloud, and warn about the cloud cleaner.

* Add a website/wordpress account if the employee is/will be blogging. [Add new user](http://www.cloudsoftcorp.com/wp-admin/user-new.php)

* Deprecated and semi-deprecated things:
  * (Semi-deprecated) Create a new Atlassian Jira account, in `cloudsoft-users` group [here](https://cloudsoft.jira.com/secure/admin/user/UserBrowser.jspa) (Note: cloudsoft-users is not the same as users!)
  * (Semi-deprecated) Install employee's SSH public key onto `cruiser@releng1:.ssh/authorized_keys`
  * (Deprecated) Create Cloudsoft web-site account with moderator permissions on GetSatisfaction
  * (Deprecated) Create an account on deveng1 enabled for Subversion, `adduser NedBaker wheel`
