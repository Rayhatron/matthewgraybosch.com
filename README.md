# matthewgraybosch.com

[![Build Status](https://travis-ci.org/matthewgraybosch/matthewgraybosch.com.svg?branch=master)](https://travis-ci.org/matthewgraybosch/matthewgraybosch.com)

This is [my website](https://motherfuckingwebsite.com). There are [many like it](https://bettermotherfuckingwebsite.com), but [this one is mine](https://www.matthewgraybosch.com). 

If you want to fork it, you can, but please check the [forking](#forking) section first. :cat:

## Built with...

* [Jekykll](http://jekyllrb.com)
* [Travis CI](http://travis-ci.org)
* [Links](http://mrmrs.io/links/)
* [Material Design colors](https://material.io/guidelines/style/color.html#color-color-palette)
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
3. Replace ```googled52e2c0a5887f7f5.html``` with a file provided by [Google Webmaster Central](https://www.google.com/webmasters/verification/home?hl=en) to verify ownership of your own domain.
4. Update ```humans.txt```.
5. Change all of the settings in ```_config.yml```.
6. Remove the items under ```before_install``` in ```.travis.yml```.
7. Replace ```deploy_rsa.enc``` with your own copy [using these instructions](https://oncletom.io/2016/travis-ssh-deploy/).
8. Clean out the following directories: 
  * ```_drafts```
  * ```_posts```
  * ```_pages```
  * ```_assets/images```
9. Have fun.
