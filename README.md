sa-git
======

[![Build Status](https://travis-ci.org/softasap/sa-git.svg?branch=master)](https://travis-ci.org/softasap/sa-git)

Git has released 2.8.1 version on Apr 03, 2016. Git is a free and open source distributed version control system . Git 2.8 comes with the large number of updates verses previous release 2.7. It is designed to handle a small to very large projects with speed and efficiency. No reason to keep default outdated git version on your system.

Playbook help you to install recent version of Git core software on your Ubuntu 16.04 LTS, 15.10, 15.04, 14.10, 14.04 LTS & 12.04 LTS systems using PPA.

Tests cover LTS releases only

Example of usage (all parameters are optional)

Simple

  roles:
    - {
        role: "sa-git"
      }


Advanced:


  roles:
    - {
        role: "sa-git"
      }
