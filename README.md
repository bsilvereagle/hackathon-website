hackathon-website
=================

Official website for the OSU Hackathon

requirements
------------

* Sections of [our report](http://arnab.org/files/HackathonReport.pdf),
presented as individual posts / pages
* A Call for sponsors
* Catalog of past winners
* Timeline of the next event

wants
-----

I'd prefer it be a static website, clean and nice. We can use any materials
from the [old hackathon website](https://library.osu.edu/find/hackathon) or
also [the twitter](https://twitter.com/@osuhackathon).

--------

# Dev environment

- Ruby 1.9.3: In Ubuntu 12.04:
```
    sudo apt-get install ruby1.9.3
    sudo apt-get install rubygems ruby-bundler
    cd /etc/alternatives
    sudo ln -sf /usr/bin/ruby1.9.3 ruby
    bundle install
```
- `bundle install` will take care of dependencies
- `bundle exec middleman` will start a server at http://localhost:4567/
- `bundle exec middleman build` will create the static site and automatically clean the build directory. 

# Copyright and License

Where possible, content is copyright The Ohio State University Open Source Club and is distributed under a [Creative Commons Attribution-Share Alike 4.0 License](https://creativecommons.org/licenses/by-sa/4.0/). 

However, this does not apply to all assets in this project. For a list of objects excluded from the CC-BY-SA license, see `source/copyright.html.erb`. 
