# hpfeeds3

hpfeeds is a lightweight authenticated publish-subscribe protocol. It has a simple wire-format so that everyone is able to subscribe to the feeds with their favorite language in almost no time. Different feeds are separated by channels and support arbitrary binary payloads. This means that the channel users decide the structure of data. It is common to pass JSON over hpfeeds.

This project aimed to deliver a modern python 3 compatible broker written on top of asyncio as well as a python 3 compatible client. It achieved these goals and the work was merged upstream. It is now archived.

Please use github.com/hpfeeds/hpfeeds going forward. hpfeeds==3.0.0 is more or less identical to hpfeeds3==0.9.10 if you want to start with an easy migration.
