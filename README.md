Fork specific notes
===================
This fork is only intended for multi-user deployments. Install it as root with bin/installBrew.rb and every user should be able to install his brews in ~/.brew without requiring rights change to /usr/local. Unforeseen bugs may be present.

Homebrew
========
Features, usage and installation instructions are [summarized on the homepage][home].

What Packages Are Available?
----------------------------
1. You can [browse the Formula directory on GitHub][formula].
2. Or type `brew search` for a list.
3. Or visit [braumeister.org][braumeister] to browse packages online.

More Documentation
------------------
`brew help` or `man brew` or check our [wiki][].

Troubleshooting
---------------
First, please run `brew update` and `brew doctor`.

Second, read the [Troubleshooting Checklist](https://github.com/Homebrew/homebrew/wiki/troubleshooting).

**If you don't read these it will take us far longer to help you with your problem.**

Who Are You?
------------
Homebrew's current maintainers are [Misty De Meo][mistydemeo], [Adam Vandenberg][adamv], [Jack Nagel][jacknagel], [Mike McQuaid][mikemcquaid] and [Brett Koonce][asparagui].

Homebrew was originally created by [Max Howell][mxcl].

License
-------
Code is under the [BSD 2 Clause (NetBSD) license][license].

Donations
---------
We accept tips through [Gittip][tip].

[![Gittip](http://img.shields.io/gittip/Homebrew.svg)](https://www.gittip.com/Homebrew/)

[home]:http://brew.sh
[wiki]:https://github.com/Homebrew/homebrew/wiki
[mistydemeo]:https://github.com/mistydemeo
[adamv]:https://github.com/adamv
[jacknagel]:https://github.com/jacknagel
[mikemcquaid]:https://github.com/mikemcquaid
[asparagui]:https://github.com/asparagui
[mxcl]:https://github.com/mxcl
[formula]:https://github.com/Homebrew/homebrew/tree/master/Library/Formula/
[braumeister]:http://braumeister.org
[license]:https://github.com/Homebrew/homebrew/tree/master/LICENSE.txt
[tip]:https://www.gittip.com/Homebrew/
