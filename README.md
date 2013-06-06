Tracker - Ticketsystem build on Oro-Platform
=======

**Project status: Pre-alpha** (Brain-Storming)

NOTES:

Feel free to participate in evewry way you want. If you find some tasks interesting, just write your name next to the task.
Under the topic interests you can provide your special needs an skills, if you don't want to fetch a specific task this early.

suggested Timeline:
- Brain-Storming: until 16.06.
- Hangout "pitch": Monday, June 17th, 18:00 CEST
to make small discussions about tasks, select tasks for first milestone, allocate task(s) on 

Core Features Tasks
------

*what is really necesssary in this system and should be implented first*

- Ticket handling -> made by YOU?

	-- Functions: create, edit, delete
- User handling -> made by YOU?

	-- Functions: create, edit, delete

Features Collection
------

*currently unpriorized*

In brackets: inspired by ... (does not mean the feature is only available in the mentioned project, but at least it is well done there)

  - Plugin System (might come via composer for free)
  - Multi Projects Capability / Config inheritance [Mantis]
  - Time tracking [Mantis]
  - Calendar, Gant-Diagram [Redmine]
  - Ticket workflow [Mantis]
  - Source Code integration [Mantis, Redmine]
  - Kanban Support (Ticket to board, board with editable columns)
  - Scrum Support [Redmine AgileDwarf]
    - Sprints
    - Absolute Priorization by Ordering of Tickets
    - Assigning Tickets to Sprints
  - Web API Support [Redmine]
  - ScreenShot Tool [Bonfire clone], but: which runs in the Browser, based on [feedback.js](http://experiments.hertzen.com/jsfeedback/) requires WebAPI and could be an external tool
  - Git-Support [Redmine]

Installation
-----

* Install composer
* Clone the git repository
* As a developer: Call `composer.phar install --prefer-source`. This allows you to easier contribute to the upstream git repositories. (especially oro-platform)
* If you are not a developer: You do not need the --prefer-source option


Scribbles and Mockups
-----

  - see mockup-folder, feel free to do own stuff here, avogt is redmine-user so, some "mockups" are just screenshots if they are useable
  - Redmine demo: http://demo.redmine.org/
  - mantis demo: http://www.mantisbt.org/demo/view.php?id=3209
  - OTRS demo: http://www.otrs.com/de/software/otrs-itsm/online-demo/
  - Jira demo: http://www.atlassian.com/de/software/jira/demo

Ideas and Thoughts
------------------

  - What about mobile: Apps over API like redmine or responsive from scratch?
  - see Features Collection, as we are still Brain-Storming

Team
----

(or as I like to call them in this chapter: interested people)

* Andreas Vogt [avogt](http://www.github.com/avogt), [@a_v_o_g_t](http://twitter.com/a_v_o_g_t)
* Alexander Menk [amenk](http://www.github.com/amenk), [@s3lf](http://twitter.com/s3lf) - PHP, User Experience

Interests
---------

* avogt: Kanban Integration, User handling


Sponsors
--------
I think webvisum GmbH could spend some resources on their dev-machine if needed
?

Version: ????



