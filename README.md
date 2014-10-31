# Frameworks and Tools for Web Development #

This is a listing of tools for web application development. These links are specific to a senior developer who has focused on Java client/server applications transitions to JavaScript based web application development - mostly using Meteor.

## Languages
* [JavaScript](http://en.wikipedia.org/wiki/JavaScript) - The programming language of the web. Not to be confused with Java
* [CoffeeScript](http://daringfireball.net/projects/markdown/) - Simpler version of JavaScript.
* [Markdown](http://daringfireball.net/projects/markdown/) - Simple to use markup language for documentation which can be converted to html. GitHub has their own [flavor of Markdown](https://help.github.com/articles/github-flavored-markdown/).

## Editors/IDE
* [JetBrains WebStorm](http://www.jetbrains.com/webstorm/) - General IDE with full debug, project management and version control. [Videos](http://tv.jetbrains.net) or on [YouTube](https://www.youtube.com/user/JetBrainsTV)
* [Atom](http://atom.io) - Free extensible editor based on JavaScript.
* [Sublime Text](http://www.sublimetext.com/) - A very popular editor among the Web Dev community.
* [Cloud 9](https://c9.io/) - a cloud based IDE for JavaScript, etc… “like Google Docs for code”
* [Plunker](http://plnkr.co/) - Sharing web development ideas online

## Version Control/Repositories
* [Git](http://git-scm.com/) - Probably the best version control out there. Speed and support for distributed development.
* [GitHub](http://github.com ) - Source repository with team and social aspects. Great integration with tools and OSes.
* [BitBucket](http) - Similar to GitHub and uses Git
* [Semver](http://semver.org/) - Semantic versioning. Rules governing software release naming.

## Package Management
* [npm](https://www.npmjs.org/doc/cli/npm.html) - Package manager for node packages and dependencies. Uses the [npmjs.org package registry](http://npmjs.org).
* [Brew (Homebrew)](http://brew.sh/) - Package manager for the Mac which uses git and Ruby underneath.
* [Bower](http://bower.io/) - A front end package manger for the web made by Twitter
* [Atmosphere](http://atmospherejs.com) - Package repository for Meteor.

## Build and Continuous Integration
* [Grunt](http://gruntjs.com/) - Task runner for JavaScript which has support for a lot of plugins. Supports Has dynamic reloading with the [contrib-watch](https://www.npmjs.org/package/grunt-contrib-watch) plugin.
* [Gulp](http://gulpjs.com) -Task runner based on streams and is wicked fast!
* [Travis](http://travis-ci.org) - Continuous integration integrated with GitHub and offers support for JavaScript/Node.js.
* [Codeship.io](https://codeship.io/) - Commercial CI which offers automated deployment to staging and production.
* [Jenkins](http://jenkins-ci.org/) - Java based CI.

## Frameworks

There is a huge ecosystem of open source JavaScript frameworks. Some are clear winners like Node.js, jQuery and Underscore. AngularJS has a lot of traction.

### Server Oriented
* [Node.js](http://nodejs.org) - Server side JavaScript framework and ecosystem.

### Middle Ware
* [ExpressJS](http://expressjs.com) - Provides routing on top of Node.js

### General Purpose
* [Redis](http://redis.io/) - Key-value cache and store (a.k.a. db) which is mostly in-memory.
* [Underscore](http://underscorejs.org) - Used by many other frameworks to provide decorators on functions, arrays and objects.
* [Modernizr](http://modernizr.com/) - Detects HTML5 and CSS3 features in the browser. Not really active and will may be deprecated as browsers adhere to modern standards.

### Client Oriented
* [jQuery](http://jquery.org) - The first great client oriented framework for DOM manipulation. Still widely used by most other frameworks.
* [AngularJS](https://angularjs.org/) - Google backed client side MVC framework
* [EmberJS](http://emberjs.com/) - An MVC framework which was the cool kid for client development before AngularJS came along.
* [BackboneJS](http://backbonejs.org/) - Another framework which gives structure to web applications by providing models, collection and views.

### Full Stack
* [Meteor](http://meteor.com) - Application framework based on concepts of 'reactive' and databases everywhere.
* [MEAN](http://mean.io) - Application framework which uses MongoDB, ExpressJS, AngularJS and NodeJS.

### Visual and Styling
* [Famo.us](http://famo.us) - Animation framework which can be integrated with AngularJS and Meteor.
* [Twitter Bootstrap](http://getbootstrap.com) - CSS stylings and provides a lot of the look of the contemporary web.
* [D3js](http://d3js.org/) - Manipulation of documents based on data. May provide some great visualizations of data.

## Utilities
* [Rubular](http://rubular.com/) - Regular expression developer and tester in Ruby (similar to JavaScript RegEx).
* [Kraken.io](https://kraken.io) - Compresses web images really well.
* [Bootsnip](http://bootsnipp.com/) - Code snippets in JavaScript/CSS for Bootstrap to provide specific features.

# Databases
* [MongoDB](http://mongodb.org/) - A document based NoSQL database.
* [PostgreSQL](http://www.postgresql.org/) - Relational database.
* [MySQL](http://mysql.com) - Relational database now managed by Oracle and part of the [LAMP](http://en.wikipedia.org/wiki/LAMP_(software_bundle%29) stack.

## Mobile
* [Apache Cordova](https://cordova.apache.org/) - Platform for building native apps from HTML, CSS and JavaScript.
* [TestFlight](https://www.testflightapp.com/) - Beta testing mobile apps by deploying them over the air.

## Design
* [Material Design](http://www.google.com/design/spec/material-design/introduction.html) - Google design language draft.

## Research and Analytics
* [Netcraft](http://www.netcraft.com/) - Market share of web servers.
* [Google Trends](http://google.com/trends) - Shows the prevalence of search terms over time and region.

## Project Management
* [Trello](http://trello.com) - Lightweight task tracking based on lists and cards.
* [Pivitol Tracker](http://pivotaltracker.com) - Agile/Scrum type tracking for larger projects.

## Deployment and Hosting
* [Amazon Web Services (AWS)](http://aws.amazon.com/) - [EC2](http://aws.amazon.com/ec2) (Elastic Compute Cloud), [S3](http://aws.amazon.com/s3) (Simple Storage Service), [RDS](http://aws.amazon.com/rds) (Relational Database Service)
* [Digtal Ocean](https://www.digitalocean.com/) - SSD only cloud hosting, fast provisioning
* [Modulus.io](https://modulus.io/) - Hosting for node which includes WebSockets, MongoDB, statistics and more. Suitable for Meteor hosting
* [Heroku](https://www.heroku.com/) - Hosting service which supports Node.js and Postgres.

## Testing
* [Mocha](http://mochajs.org/) - Unit testing for node/backend using behavior driven development (BDD).
* [Jasmine](http://jasmine.github.io/) - Behavior driven JavaScript test description framework.
* [Velocity](https://github.com/meteor-velocity/velocity) - Testing framework for Meteor which uses other frameworks for test descriptions.
* [Karma](http://karma-runner.github.io/) -Browser testing framework uses other test description frameworks like Jasmine or Mocha.

## Performance
* [Fiddler](http://www.telerik.com/fiddler) - Web performance and proxy debugging.

## Communications
* [Textual](http://www.codeux.com/textual/) - Mac based IRC Client.
* [Freenode.net](http://www.freenode.net/) - an IRC network which discusses open source software. Channels for #angularjs, #node.js, #meteor
* [irchelp.org](http://www.irchelp.org/) - Provides an overview and support for IRC

## Education
* [How to Learn JavaScript Properly](http://javascriptissexy.com/how-to-learn-javascript-properly/) - Recommended as the proper way.
* [Pluralsight](http://www.pluralsight.com/) - Longer form commercial training.
* [Tuts+](http://tutsplus.com/) - Another commercial training site.
* [egghead.io](https://egghead.io/) - Bite sized web development training focusing on AngularJS. Lots of free courses.
* [Thinkster.io](http://thinkster.io) - This is a very comprehensive AngularJS tutorial which builds on the egghead.io videos.
* [CodeWars](http://www.codewars.com/) - This site has a bunch of tiny JavaScript challenges you solve. After solving you can look at the solutions other people came up with, and the alternate solutions have ratings for things like best practice and creativity.

## Blogs and Articles
* [JavaScript Jabber](http://devchat.tv/js-jabber/) - Excellent podcast focusing on JavaScript. Full transcripts and detailed show notes.
* [Crater.io](http://crater.io) - Aggregator of Meteor specific news.
* [Meteor Podcast](http://www.meteorpodcast.com/) - Weekly discussion of Meteor topics from crater.io.
* [DailyJS](http://dailyjs.com/) - Technical JS articles delivered daily.
