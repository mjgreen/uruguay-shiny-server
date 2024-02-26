---
title: "R Shiy Server uruguay"
author: "Matt and Alex"
format: html
editor: source
keep-md: true
---



Tom wrote: ***A test rshiny/rstudio server is ready. There are a number of areas
which may need attention or refinement.***

* Currently all of Scitech Psychology Staff (academic) can access
   it. They will need to know of the service, but in principle they
   are permitted to log on. Let me know if this is the intention.
   
   * Yes, this is the intention. 
   * Can you also add members of our postgrad reserach students, who are on  SciTechPsychologyResearchStudents@bournemouth.ac.uk
   * Will new members of those mailing lists inherit the permission to login when they join the list?

* A domain (current test domain is uruguay.bournemouth.ac.uk). For a
   production service would would something like psy.bmth.ac.uk not be
   better ?
   
   * Yes, 'psy' would be better than 'uruguay' but can we leave 
   'bournemouth' without abbreviating it? So, 'psy.bournemouth.ac.uk'

* Resourcing, for example how many concurrent users will be expected
   to run what type of apps ? This will affect RAM, number of
   processors and storage quotas.
   
   * A whole year group should be able to access it concurrently (N = 500) 

* R packages/libraries. Staff users, like your self, can install and
   manage their own (user) packages for the most part, but the system
   ones can not be managed with out help from the system
   administrator.
   
   * Understood: if we need to install a package that has dependencies on 
   system libraries that we would typically 'apt install ...', 
   how should we request that please? 
   
* Type of usage or workflows. I.e. staff users generating and
   managing individual content or staff users sharing and generating
   shared content ?
   
   * Staff will generate and share content to students (for example [https://uruguay.bournemouth.ac.uk/shiny/users/mgreen/shinyanova](https://uruguay.bournemouth.ac.uk/shiny/users/mgreen/shinyanova) ). This is generally produced for our students to consume.
   
   * Staff will also want to generate content associated with research articles that we publish - for this it is very important that users from other universities, and people who sit on the committees of funding providers that do not have university accounts from any university should be able to access the URLs. They don't need to be able to log in to deploy apps, but they need to be able to see the URLs where the apps are deployed without having a BU account, and without being physically located on our campus.

* Will the server host critical content e.g. content used in
   assessments ?
   
   * No - Alex?
