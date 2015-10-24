randomTweetFromFile 1.0d1
============
Perl script to tweet random lines from a specified file. Uses ttytter to tweet.

ABOUT
-----
The idea is a script that would be useful for posting random quotes and the
like. There are probably already solutions out there for this, but here's mine.
I decided NOT to use Net::Twitter to do this. It looks like a good module, but
to go that route basically meant I would be creating a Twitter client in Perl,
and that's not what I was looking for. I might look at switching over to that
in the future if I get uppity (or ttytter stops working) but it's unlikely.

The script only handles selecting what to tweet. Scheduling a tweet is something
the user needs to handle on their own. On OS X, this is best handled via the
launchd service. (I like using Lingon X to manage launchd jobs. Find more about
it here: https://www.peterborgapps.com/lingon/) On Linux, you could do this with
CRON. I don't know about Windows.

My perl-fu isn't the most advanced, but this is free to take and modify if you
find any bit of it useful.

Get the latest release here:
    https://github.com/r3v/randomTweetFromFile/releases/latest

FEATURES
--------
* Pulls a random line from a text file to tweet.
* Uses a random hashtag from a text file, if there is room. (Optional)
* Log file to keep track locally of what was tweeted and when.


USAGE
=====
Details on how to setup and run the script.

REQUIRED PERL MODULES
---------------------
	LIST
	THEM
	HERE

SETUP/CONFIG
------------
... sure, I'll finish this soon...
