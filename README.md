example-website
===============

this is a dead-simple website for use in testing network issues with hosting.

my typical use-case for this is:
- provision vm
- install git
- install thttpd
- create a "ryan" user
- clone this repo
- thttpd -d /home/ryan/example-website -p 80 -l /home/ryan/thttpd.log
- run tcpdump while generating some traffic to this website.

This is basically my handy "lorem ipsum" website.
