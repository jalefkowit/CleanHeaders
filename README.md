This is a plugin to stop WordPress from injecting a bunch of stuff that nobody uses on CMS-oriented sites into the HEAD of every page.

Currently it suppresses:
* Feed autodiscovery links
* Windows Live Writer endpoint
* Content navigation links: Parent, Next, Previous, Start pages
* Really Simple Discovery (RSD) endpoint

Currently it does NOT suppress:
* GENERATOR tag indicating version of WordPress in use
* Canonical URL META tag
