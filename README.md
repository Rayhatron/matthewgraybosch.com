# matthewgraybosch.com

[![Build Status](https://travis-ci.org/matthewgraybosch/matthewgraybosch.com.svg?branch=master)](https://travis-ci.org/matthewgraybosch/matthewgraybosch.com)

This is [my website](https://motherfuckingwebsite.com). There are [many like it](https://bettermotherfuckingwebsite.com), but [this one is mine](https://www.matthewgraybosch.com). 

If you want to fork it, you can, but please check the [forking](#forking) section first. :cat:

## Built with...

* http://jekyllrb.com
* http://travis-ci.org
* http://mrmrs.io/links/
* http://clrs.cc
* heavy metal
* weapons-grade kitten love

...in Harrisburg, PA and hosted by [Dreamhost](https://dreamhost.com)

## Roadmap

* Add content from old sites.
* Add [service worker to make site available offline](https://fossbytes.com/get-jekyll-blog-work-offline/).
* Add short stories.
* Add cleaned-up version of the 2009 *Starbreaker* draft for visitors to read for free.
* Begin serializing *Blackened Phoenix* online.
* Create a "site starter" based on this repository so people can fork *that* instead. 
* Create a theme gem, too?

## Forking

If you decide to fork this project, please do the following in your copy:

1. Create a Travis CI account if you don't already have one.
2. Get yourself a host that offers SSH access and allows uploads via SFTP and rsync.
3. Change all of the settings in ```_config.yml```.
4. Remove the items under ```before_install``` in ```.travis.yml```.
5. Replace ```deploy_rsa.enc``` with your own copy [using these instructions](https://oncletom.io/2016/travis-ssh-deploy/).
6. Clean out the following directories: 
  * ```_drafts```
  * ```_posts```
  * ```_pages```
  * ```_assets/images```
7. Have fun.
