* [The mission](#The-mission)
* [Site documentation](#GWT-Documentation)


# The mission

This is an initiative to update the GWT site and enrich with new content, the gaol is to update the current content and to add content that refers to the new libs/frameworks related to GWT.

Also make the site a good place for starters, by adding tutorials, demo, and tools that help them start using GWT with minimum efforts. 

## Improvments outlines

### The Home page has 4 main links :

- #### Overview

	- The overview seems to be ok needs some update. maybe the list of the Apps built with GWT.

  - Why should i use GWT.

  
- #### Download

	Maybe we need to set the maven/gradle dependencies here.
  also if we build a CLI tool here we might add here maybe, also might provide it with sdkman.

- #### Getting started
	this needs most of the work.

	- This still uses ANT, so we need to use MAVEN at least here.

  - uses OLD devmode so might change to super devmode.

  - Create a simple CLI to get started with GWT.

  - Make use of the mvp4g web project generator.

	- Introduction to use GwtBoot starters.

- #### Docs

	- Split the tutorials from the documentation maybe add them on the home page.

  - Add tutorial for each section in the documentation maybe at the end of each section.

  - Add tutorials for new GWT libs and frameworks provided by the lib/framework author.

  - Rest is common, so maybe introduce a rest tutorial with different rest clients.

  - Introducing the new RPC from colin.

  - Tutorials for building GWT apps with different back-end techs spring-boot, vertx ..etc

  - Tutorials for JsInterop and how to interact with other JS Libs.


**In the home page we can introduce the following new topics:**

- Community

  - Listing GWT libs and frameworks
  - Built with GWT.


- JCL/GWT3
  - GWT3.0 progress
  - Writing APPs for GWT3.0
  - GWT3 VS GWT2
  - Help get GWT3 out.


- Tutorials - moved out from Docs

  - List all tutorials.


- News, Blogs and Article - moved out


- Social Media
  - Twitter account.
  - Face book account
  - Be more active on Linked-in, G+


# GWT Documentation

* GWT documentation is published under http://www.gwtproject.org/doc/latest/DevGuide.html

## Reference

* Markdown processor: https://github.com/sirthias/pegdown

## Adding content

* See: http://www.gwtproject.org/makinggwtbetter.html#webpage

## Building

If you have Grunt installed :
* build the assets using Grunt: `grunt`
* then run: `mvn clean install`
* after that you will find the generated documentation in `target/generated-site/`.

If you don't have Grunt installer :
* build the assets using Maven and Grunt plugin: `mvn clean install -Pgrunt`
* after that you will find the generated documentation in `target/generated-site/`.

### Running locally
Run the site locally for easy visual testing

* Change to the `target/generated-site` folder.
* Open the `index.html` file in your browser.
* Additionally, you could run any local HTTP server in this folder.

