# LambdaLadies.com

This repository holds the source code for [http://www.lambdaladies.com](http://www.lambdaladies.com). The instructions below explain how to run a local copy of the website to test any proposed changes. We welcome pull requests.

If you would like to contribute a blog post to the site, please see [these instructions](CONTRIBUTING.md).

## Testing Locally

To build and run the site locally you will need Ruby (>= 1.9.3), Ruby Gems, and the 'bundle' Gem. Once you have these dependencies installed, fork and clone this repository and run the following commands from the cloned repo: 

    git checkout source
    bundle install
    jekyll serve --watch

Add your changes on the 'source' branch and test them locally. When you are happy with them, please send us a pull request.

## Updating the Site

Those with commit access to this repository can build and push a new version of the site to GitHub and GitHub Pages with the following commands: 

    git checkout source
    jekyll serve
    git add -A
    git commit -m "Message explaining changes"
    git branch -D master
    git checkout -b master
    git filter-branch --subdirectory-filter _site/ -f
    git checkout source
    git push --all origin

## Jekyll Theme Credits

### Authors

Originally built for [sendtoinc.com](https://sendtoinc.com), your workspace for sharing and organizing knowledge.

**Karri Saarinen**

+ [http://twitter.com/karrisaarinen](http://twitter.com/karrisaarinen)
+ [http://github.com/ksaa](http://github.com/ksaa)

**Jori Lallo**

+ [http://twitter.com/jorilallo](http://twitter.com/jorilallo)
+ [http://github.com/jorde](http://github.com/jorilallo)

### Copyright and license

Copyright 2013 Kippt Inc. under [The MIT License ](LICENSE)

