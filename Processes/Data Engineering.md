Data Engineering: Rules of Engagement
=====================================

The Agile Scrum methodology has a concept of [working agreements](https://www.scrumalliance.org/community/articles/2015/march/how-to-create-agile-team-working-agreements). 
While this document was not modeled after a formal working agreement the intentions are the same.  This document describes how the data engineering team have agreed to handle shared responsibilities, like on call rotation.

## The Team
@bigbadace
@kschrodes
@richhaase
@roycehaynes
@spucci <- changing roles
 
## On Call Rotation

* [process] If you can't get to a page reach out to someone who can get to it.
* [task] Change the on call rotation so that each person is secondary on call the week before they become primary.
* [task] Change the on call rotation so that Sam and Samir are the 3rd tier of escalation for Data Engineering, Data Science and Web.
    * Requires approval from other teams.
* [task] Always make a ticket for every victorops issue that comes in while you are on call.
    * [task] Tutorial on how to create a ticket in Jira

## Alert Feedback

* [process] Pair program when fixing alerts, and update the docs for the next engineer!
* [issue] We have a gap between the contents of a victorops alert and the documentation for that alert.
    * [task] Add documentation links to each alerts
* [process] Always look for opportunities to optimize feedback loop on alerts.
* [task] Kill bug emails in favor of alerting via Nagios/VictorOps
      
## Bugs
We agree in principle that bugs should always come first.  However, we also came up with a long list of
exceptions to that rule without even trying. So, the bullets below are ideals we will strive for rather than unbreakable rules.
        
* [process] Self select to work on bugs.
* [process] If you have a scoped bug in your queue that should be your top priority work item.
* [process] Pair with someone on bug work to help expand the knowledge base of the team and decrease time to resolutions.
