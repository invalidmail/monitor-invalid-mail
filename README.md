Monitor Invalid Mail
===============

Receives and collates error and status data from applications via mail. Major highlights:

* Written in Go!
* Receives error reports via email; compiles the reports and displays them in a friendly UI. (In Progress)
* Can receive routine status information and post to a social network (Twitter, App.Net) or to a feed (JSON, RSS) (Complete)
* Graphs past performance in charts (In Progress)

Currently in alpha. Demonstration of system status posting at https://alpha.app.net/app 

##Overview

Most logging platforms can generate emails when errors occur. Invalid Mail allows a developer to receive/collate these error emails and view/search them through a web interface, or post them to another monitoring service.
