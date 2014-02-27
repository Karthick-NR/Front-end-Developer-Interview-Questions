####General Questions:

* What did you learn yesterday/this week?
  - prolog stands for programming logic
  - how to merge docs changes in the angular.js repo
  - z alias for jumping to a folder that's in any part of the parent path (paul irish web app dev workflow)
  - regressive enhancement (remy sharp's what is a polyfill blog post)

* What excites or interests you about coding?
  - abstractions
  - community
  - programming language design
  - pedagogy of programming
  - sociopolitical implicaitons of labor shift

* What UI, Security, Performance, SEO, Maintainability or Technology considerations do you make while building a web application or site?
  - who is the audience
  - what devices are they using
  - what connections are they on
  - what is the major value proposition of the user experience
  - how big is the team, how stable is it
  - what experience does the team have
  - what code already exists
  - who are the primary stakeholders, what control do they have over the feature pipeline

* Talk about your preferred development environment. (OS, Editor, Browsers, Tools etc.)
  - chrome, chrome dev tools
  - sublime for code editing, vim for git
  - browserstack
  - grunt for automation
  - jshint/jslint, beautifier
  - bash terminal
  - prefer rebase to merge

* Can you describe your workflow when you create a web page?
* Can you describe the difference between progressive enhancement and graceful degradation?
  * Bonus points for describing feature detection
* Explain what "Semantic HTML" means.
* How would you optimize a websites assets/resources?
  * Looking for a number of solutions which can include:
    * File concatenation
    * File minification
    * CDN Hosted
    * Caching
    * etc.
* Why is it better to serve site assets from multiple domains?
  because most browsers have a limit for number of parallel component downloads per domain
  * How many resources will a browser download from a given domain at a time?
  - http://www.yuiblog.com/blog/2007/04/11/performance-research-part-4/
  back in the day it was 2 (http/1.1 spc) (stairstep pattern) (IE and firefox)
  - firefox used  to do 8! (http/1.0)
  - too many parallel downloads can also degrade performance


* Name 3 ways to decrease page load. (perceived or actual load time)
  - reduce page weight
    - minimization (unecessary white space, comments)
    - move inline scripts and css to external pages
    - HTML tidy
  - minimize number of files

* If you jumped on a project and they used tabs and you used spaces, what would you do?
  * Suggest the project utilize something like EditorConfig (http://editorconfig.org)
  * Conform to the conventions (stay consistent)
  * `issue :retab! command`
* Write a simple slideshow page
  * Bonus points if it does not use JS.
* What tools do you use to test your code's performance?
  * Profiler, JSPerf, Dromaeo

* If you could master one technology this year, what would it be?
* What are the differences between Long-Polling, Websockets and SSE?

* Explain the importance of standards and standards bodies.
  - stan

* What is FOUC? How do you avoid FOUC?
  - flash of unstyled content
  - browser engine renders the page before the style sheet is loaded
  - priorities programemd into the browser
  - more prevalent because of multiple stylesheets
  - @import statements
  - cascading nature of CSS rules encourage some browsers to wait until all the style data is collected before applying it

  - hide content until fully loaded

* Do your best to describe the process from the time you type in a website's URL to it finishing loading on your screen.