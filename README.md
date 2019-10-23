# Django-Python-Web-Application
Work done with Prosper IT Consulting Dev Ops Team


# Live Project

## Introduction

I took part in a non-paid internship with Prosper IT Consulting working as a software developer as part of a Dev Ops team that worked on building a project that is a web scraping application built with Django and Beautifulsoup.  The application will gather data from the web that is relevant to the user, who is looking to travel.  It will include weather, flights info, events, restaurants, etc.  We will be getting the data with webscraping and APIs.

This project leveraged the power of .NET frameworks and MVC.  The main programming language used was C# in addition to the front-end languages.

Below are descriptions of stories I helped work on in an AGILE environment along with code snippets and navigation links.  

*Jump to: [Back End Stories](#back-end-stories), [Front End Stories](#front-end-stories), [Other Skills](#other-skills), [Page Top](#live-project)*




## Back End Stories
* [NewAppBudgetApp](#newappbudgetapp)
* [CleanUpDashboard](#cleanupdashboard)


### NewAppBudgetApp

Story Decription: Grounds up back and front design for a budgeting app that could help the user plan and budget for potential trips then implemented to Django.

Before Snippet
Include photo reference link

After Snippet
Photo reference link


*Jump to: [Back End Stories](#back-end-stories), [Front End Stories](#front-end-stories), [Other Skills](#other-skills), [Page Top](#live-project)*


### CleanUpDashboard

Story Decription: Setting up the dashboard as the main relay or switchboard for the user to connect with each app that was being built. Improving also upon the visual side to help the user have a friendlier experience.

Before Snippet
Include photo reference link

After Snippet
Photo reference link

*Jump to: [Back End Stories](#back-end-stories), [Front End Stories](#front-end-stories), [Other Skills](#other-skills), [Page Top](#live-project)*


## Front End Stories
* [FrontEndFixLogo](#frontendfixlogo)
* [FrontEndIconsUpgrade](#frontendiconsupgrade)
* [HTMLSpecialCleanupBugFixes](#htmlspecialcleanupbugfixes)
* [FrontEndFixTemplates](#frontendfixtemplates)
* [BugFixSortRenderingDependencies](#bugfixsortrenderingdependencies)


### FrontEndFixLogo
Story Decription

Before Snippet
Include photo reference link

After Snippet
Photo reference link

*Jump to: [Back End Stories](#back-end-stories), [Front End Stories](#front-end-stories), [Other Skills](#other-skills), [Page Top](#live-project)*


### FrontEndIconsUpgrade
Story Decription

Before Snippet
Include photo reference link

After Snippet
Photo reference link

*Jump to: [Back End Stories](#back-end-stories), [Front End Stories](#front-end-stories), [Other Skills](#other-skills), [Page Top](#live-project)*

### HTMLSpecialCleanupBugFixes
Story Decription

Before Snippet
Include photo reference link

After Snippet
Photo reference link

*Jump to: [Back End Stories](#back-end-stories), [Front End Stories](#front-end-stories), [Other Skills](#other-skills), [Page Top](#live-project)*

### FrontEndFixTemplates
Story Decription: At the time, some of the applications that were completed had their own html templates and some were located inside the general/global template folder.  The director wanted to maintain the practice of following things the Django way which meant every app had its own template exclusively for that app.  At this stage we wanted to relocate all misplaced html templates that were inside the global template folder to be stored within their own designated apps.  We aniticpated this would have issues with routing and dependencies.

Before Snippet
Include photo reference link

After Snippet
Photo reference link

*Jump to: [Back End Stories](#back-end-stories), [Front End Stories](#front-end-stories), [Other Skills](#other-skills), [Page Top](#live-project)*

### BugFixSortRenderingDependencies
Story Decription:  At the time the main problem...  Our overall app is growing in size and complexity, this is good.  But there is the problem that some of the smaller apps are relying on the base.html file and we're about to be flooded with dependencies(links, scripts, etc).  This can cause overriding of scripts and which app is dependent on them.

The proposed solution: Have our apps handle their own dependencies by either:
--Having each app use SimpleBASE.html that can be rendered to the MAIN BASE.html every time the user calls/uses the app THEN have that SimpleBASE.html handle the rendering of each .html inside that app  
--OR--
--Apply each dependency on each .html inside that app and render when that .html is called.

Note: Make sure to sort these dependencies correctly and remove them from the main BASE.


Before Snippet
Include photo reference link

After Snippet
Photo reference link

*Jump to: [Back End Stories](#back-end-stories), [Front End Stories](#front-end-stories), [Other Skills](#other-skills), [Page Top](#live-project)*


## Other Skills

* Teaming with a group of developers working to identify both front-end and back-end issues/bugs and finding solutions to improve usability and efficieny in an application.
* Attending stand-up meetings physically and remotely, discussing any questions or concerns with team members to improve overall organization and communication.
* Practice with Team/Pair Programming when a developer has issues solving a particular problem.

*Jump to: [Back End Stories](#back-end-stories), [Front End Stories](#front-end-stories), [Other Skills](#other-skills), [Page Top](#live-project)*


This is under construction and will have revisions in the future.
Thanks for viewing :)

