__BearShop__
=============

> John Hammond | August 17th, 2016

------------------------------

This repo is dedicated to housing all materials and code for an idea that I have titled "BearShop." My classmates have came to me with an idea to create a buy/trade/sell store for the USCGA, so this is all the work put in for my rendition of it.

I plan to do this project in [Python] with [Flask].

File & Directory Information
----------------

* [`skeleton/`](skeleton/)
    
    This directory holds some code from a recent CTF platform I tried to build on my own. I am using elements from it, so I just snagged to code to be able to cherry-pick off of it and change what I need to get this project rolling.

* [`schema.sql`](schema.sql)    
    
    This is the [SQL] schema file that is used to create the database for the webpage. It should create and define tables for things like users, the products on sale, and anything else that may be deemed necessary.

* [`setup.sh`](setup.sh)    
    
    This is the [`bash`][bash] script that I planned on using to initially create the server. It sets up the database, creates private keys to be used, and modifies a "base" rendition of the server [Python] script to add all of the configuration variables that can be set _in the [`setup.sh`](setup,sh)_ script.




[Python]: https://www.python.org/
[Flask]: http://flask.pocoo.org/
[SQL]: https://en.wikipedia.org/wiki/SQL
[bash]: https://en.wikipedia.org/wiki/Bash_(Unix_shell)