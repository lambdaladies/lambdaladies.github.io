# LambdaLadies.com

This repository holds the source code for [http://www.lambdaladies.com](http://www.lambdaladies.com). The instructions below explain how the Jekyll theme it uses works and how to run a local copy of the website to test any proposed changes. Please send pull requests with any suggestions.

To build and run the site locally:

    git checkout source
    jekyll serve

To push changes to the site to GitHub and GitHub Pages:

    git checkout source
    jekyll serve
    git add -A
    git commit -m "Message explaining changes"
    git branch -D master
    git checkout -b master
    git filter-branch --subdirectory-filter _site/ -f
    git checkout source
    git push --all origin

# Jekyll Incorporated
Modern Jekyll based blog. Great for companies, products or anything. See live at [blog.sendtoinc.com](http://blog.sendtoinc.com)

## Installation & Usage
    bundle install
    jekyll serve --watch

_Note: Requires Ruby version 1.9.3 =>. For example use [rbenv](https://github.com/sstephenson/rbenv)_   
    
## Configuration
Edit: _config.yml (general options), main.css (theme colors &amp; fonts)

```
jekyll-incorporated/
├── _config.yml
├── _assets/
    ├── stylesheets/
        ├── main.scss
```

_Note: when editing _config.yml, you need to restart jekyll to see the changes.__

## Usage examples

* Adroll Engineering http://tech.adroll.com/
* Brace.io blog http://blog.brace.io/
* Spark.io blog http://blog.spark.io/
* Department of Better Technology http://blog.dobt.co/

## Authors

Originally build for [sendtoinc.com](https://sendtoinc.com), your workspace for sharing and organizing knowledge

**Karri Saarinen**

+ [http://twitter.com/karrisaarinen](http://twitter.com/karrisaarinen)
+ [http://github.com/ksaa](http://github.com/ksaa)

**Jori Lallo**

+ [http://twitter.com/jorilallo](http://twitter.com/jorilallo)
+ [http://github.com/jorde](http://github.com/jorilallo)

## Copyright and license

Copyright 2013 Kippt Inc. under [The MIT License ](LICENSE)

