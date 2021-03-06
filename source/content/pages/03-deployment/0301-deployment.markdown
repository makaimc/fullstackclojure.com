title: Deployment
category: page
slug: deployment
sort-order: 031
choice1url: /web-frameworks.html 
choice1icon: fa-code fa-inverse
choice1text: Show me Clojure web frameworks I should use to create an app. 
choice2url: /introduction.html
choice2icon: fa-fast-backward fa-inverse
choice2text: Let me start over from the Full Stack Clojure introduction.
choice3url: /future-directions.html
choice3icon: fa-magic
choice3text: Show me what sections will be added to this guide in the future.
choice4url:
choice4icon:
choice4text:


# Deployment
Deployment involves packaging up your Clojure code as a .war (Web 
application ARchive) file then copying the file to a directory where it will
be recognized and run up by a web application server.


## Why is deployment necessary?
Your web application must live somewhere other than your own desktop or 
laptop. A production environment is the canonical version of your current 
application and its associated data.


## Deployment hosting options
Four options exist for hosting your web application. Three of them involve
setting up the operating system, system packages, security and Clojure 
dependencies during deployment. The fourth, using a platform-as-a-service,
abstracts away much of the set up at the cost of higher pricing and loss of
infrastructure control. The four options are

1. ["Bare metal" servers](/servers.html)

2. [Virtualized servers](/servers.html)

3. [Infrastructure-as-a-service](/servers.html)

4. [Platform-as-a-service](/platform-as-a-service.html)



## Deployment resources
* [Thoughts on web application deployment](http://omniti.com/seeds/thoughts-on-web-application-deployment)
  walks through deploying apps with source control, continuous deployment and
  monitoring.

* [Practical continuous deployment](http://blogs.atlassian.com/2014/04/practical-continuous-deployment/)
  defines delivery versus deployment and walks through a continuous deployment
  workflow.


### How would you like to deploy your web app?
