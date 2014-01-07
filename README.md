bower_lab
=========

A project to get my hands dirty with bower, a package manager utility by Twitter.

## A Quick Sumary
* Bower is a front-end package management utility tool.
* It's like [Bundler](http://bundler.io/) in the RoR world.
* bower.json is to Bower, like Gemfile is to Bundler
* Newer versions of Bower use bower.json to store package dependency information. The older versions of Bower were using components.json.
* Bower runs over Git, and is package-agnostic. A packaged component can be made up of any type of asset, and use any type of transport (e.g., AMD, CommonJS, etc.).

## Bower CheatSheet for my quick reference
* To create a new file in the project repository, just ``` bower init ```
* To install a package, simply type ```bower install package_name#version``` as in
``` bower install jquery``` and ```bower install jquery#1.2.3```
* Use --save option during install, to record the dependency in bower config. Example command: ```bower install <package> --save```
* ```bower list``` or ```bower ls``` will list the packages you currently have installed
* If you’d like to see what repository URL a certain package refers to, use the ```bower lookup <package>``` command
* To know what versions of a package are available, use ```bower info <package>``` command
* The ```bower install <package>``` command saves a copy of it to ```~/.bower/<package>``` to speed up later installations of the same package
* ```~/.bower`` is the bower cache. You can clear the cache with the command: ```bower cache-clean```

## Prerequisites
* [Node](http://nodejs.org)
* [NPM](https://npmjs.org)

## Contributors
 * [Karthik Sirasanagandla](https://github.com/karthiks)

## References:
* [Bower](http://bower.io/)
* [Net Tutplus](http://net.tutsplus.com/tutorials/tools-and-tips/meet-bower-a-package-manager-for-the-web/)

