# Said Abdou Mattar code fellows 301 coding journey..
Day 15:
Today I have learned about applications deployment.
Heroku lets you deploy, run and manage applications written in Ruby, Node.js, Java, Python, Clojure, Scala, Go and PHP.
Dependency mechanisms vary across languages: in Ruby you use a Gemfile, in Python a requirements.txt, in Node.js a package.json, in Java a pom.xml and so on.
The source code for your application, together with the dependency file, should provide enough information for the Heroku platform to build your application, to produce something that can be executed.
When you create an application on Heroku, it associates a new git remote, typically named heroku, with the local git repository for your application.
As a result, deploying code is just the familiar git push, but to the heroku remote instead:
$ git push heroku master
An application’s configuration is everything that is likely to vary between environments (staging, production, developer environments, etc.). This includes backing services such as databases, credentials, or environment variables that provide some specific information to your application.

Heroku lets you run your application with a customizable configuration - the configuration sits outside of your application code and can be changed independently of it.
The configuration for an application is stored in config vars (Links to an external site.)Links to an external site..
Applications consist of your source code, a description of any dependencies, and a Procfile.
Procfiles (Links to an external site.)Links to an external site. list process types - named commands that you may want executed.
Deploying applications involves sending the application to Heroku using either git, GitHub, Dropbox, or via an API.
Buildpacks (Links to an external site.)Links to an external site. lie behind the slug compilation process. Buildpacks take your application, its dependencies, and the language runtime, and produce slugs.
A slug (Links to an external site.)Links to an external site. is a bundle of your source, fetched dependencies, the language runtime, and compiled/generated output of the build system - ready for execution.
Config vars (Links to an external site.)Links to an external site. contain customizable configuration data that can be changed independently of your source code. The configuration is exposed to a running application via environment variables.
Add-ons (Links to an external site.)Links to an external site. are third party, specialized, value-added cloud services that can be easily attached to an application, extending its functionality.  

A release (Links to an external site.)Links to an external site. is a combination of a slug (your application), config vars and add-ons. Heroku maintains an append-only ledger of releases you make.
