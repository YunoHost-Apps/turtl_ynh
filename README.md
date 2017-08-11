# Turtl app for YunoHost

- [Yunohost project](https://yunohost.org)
- [Turtl website](https://turtlapp.com/)

![Turtl logo](https://avatars1.githubusercontent.com/u/5256479?v=4&s=200 "Turtl logo").

**WARNING**: this is a work in progress, test it at your own risks!

## Todo

- [ ] test on x86 (only tested on arm for now)
- [ ] upgrade script
- [ ] backup script
- [ ] restore script
- [ ] check_process

------------------------------

## What's Turtl

Turtl lets you take notes, bookmark websites, and store documents for sensitive projects.
From sharing passwords with your coworkers to tracking research on an article you're writing, Turtl keeps it all safe from everyone but you and those you share with.

You will need apps to use Turtl. Get them from <https://turtlapp.com/download/>.

## Nota bene

The `rethinkdb_2.3.6_armhf.deb` debian package in `conf` directory of this repository is a cross-compiled RethinkDB package for ARM architecture since no ARM package is provided by RethinkDB.
