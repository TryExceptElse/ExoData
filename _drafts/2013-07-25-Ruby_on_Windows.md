---
layout: news_item
title: "Jekyll 1.0.0 Released"
date: "2013-05-06 02:12:52 +0200"
author: Dan Stroot
version: 1.0.0
categories: [release]
---

# Install Ruby on Windows

1) go to http://rubyinstaller.org/ and download the version you need.  While you are here also download the appropriate devkit.
2) install Ruby - but make sure you select all three boxes on the first screen (for some reason these are unchecked by default):
http://3.bp.blogspot.com/-mIcllnUR1lQ/TzAeDUMHfeI/AAAAAAAAD-M/y18m6M1tGik/s400/RubySetup.png
You can ensure the Ruby is installed correctly by opening PowerShell and type in "irb". If you see irb(main):001> you are good.
3) Install the devkit.  This is a less polished.  Create a C:RubyDevKit directory and copy the downloaded devkit file to this directory and run it.  It will self extract into the directory.  Then run “ruby dk.rb init” and “ruby dk.rb install” to bind it to ruby installations in your path.
4) type "gem update --system" to update your RubyGems.

OK - you should be good to go.  


### References
- http://ntotten.com/2012/03/02/github-pages-with-jekyll-local-development-on-windows/
- http://www.racap.net/2012/02/how-to-install-ruby-on-rails-in-windows.html
- http://rubyinstaller.org/downloads/
- https://github.com/oneclick/rubyinstaller/wiki/Development-Kit 