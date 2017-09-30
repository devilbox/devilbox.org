# devilbox.org

This repository holds the source code of the [devilbox.org](http://devilbox.org) web page in the [gh-pages](https://github.com/devilbox/devilbox.org/tree/gh-pages) branch.

![devilbox](devilbox-dash.png)


### How to build locally?

##### 1. Get the sources

```shell
# Clone repository
$ git clone -v https://github.com/devilbox/devilbox.org

# Checkout gh-pages branch
$ cd devilbox.org
$ git checkout gh-pages
```

##### 2. Setup Gemfile
```
$ vi Gemfile
source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins
```

##### 3. Install requirements
```shell
$ gem install bundler
$ bundle install
```

#### 4. Build
```shell
$ bundle exec jekyll serve
```


### Reference

https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/
