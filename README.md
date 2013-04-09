Monitor Invalid Mail
===============

Receives and collates error and status data from applications via mail. Major highlights:

* Written in Go!
* Receives error reports via email; compiles the reports and displays them in a friendly UI. (In Progress)
* Can receive routine status information and post to a social network (Twitter, App.Net) or to a feed (JSON, RSS) (Complete)
* Graphs past performance in charts (In Progress)

Currently in alpha. Demonstration of system status posting at https://alpha.app.net/app 

#Overview

Most logging platforms can generate emails when errors occur. However, these messages can quickly stack up and fill your inbox. Monitor Invalid Mail allows an administrator to receive these error emails and view/search them through a web interface.

#Invalid Mail

The definition for **invalid** means *A person made weak or disabled by illness or injury.* The name of this service comes from the idea that error emails are sent from ill systems; therefore, invalid mail.
