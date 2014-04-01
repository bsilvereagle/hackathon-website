hackathon-website
=================

Official website for the OSU Hackathon

requirements
------------

* Sections of our report, presented as individual posts / pages
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
    sudo apt-get install ruby 1.9.3
    sudo apt-get install rubygems ruby-bundler
    cd /etc/alternatives
    sudo ln -sf /usr/bin/ruby1.9.3 ruby
    bundle install
```
- bundle install will take care of dependencies
