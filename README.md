pwdhash in Go
=============

This is a command-line implementaton of the pwdhash algorithm in Go. It was mostly ported from the JavaScript version in the Firefox Add-on. This fork of [peterh/pwdhash](http://github.com/peterh/pwdhash) is more secure in that it does not permit the user to put the root password as a CLI argument, which can get saved to bash history files.

Usage
-----
    pwdhash <domain>

The prompt is interactive. The output may be piped to tools like `pbcopy` for convenient pasting.

See Also
--------
http://crypto.stanford.edu/PwdHash/
https://addons.mozilla.org/en-US/firefox/addon/pwdhash/
