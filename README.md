# OpenBSD Ports #

These are the OpenBSD ports that correspond to the Tor browser bundle.
They are a work in progress.  Please beware that until we make release
announcements you should be careful using this stuff.  You must be
runing OpenBSD -current and have your ports and src synced up (like I
said: running -current).

I am tracking the latest in the 4.0.x (stable) series of Tor browser
releases; the development/beta version is 4.5.x and maybe I'll do a
port of that as well, but for now we'll stick with stable.

I also try stay consistent with the version of Firefox ESR that is in
ports wrt. which version of tor-browser I base the port on.

I keep notes in notes.org.  You're welcome to look over my shoulder
but then don't be offended by what I say.

## Beware: Experimental Until Otherwise Stated ##

You should be aware that there might be bugs or issues that could
e.g. screw over your non-tor `~/.mozilla` directory over if you aren't
careful.  Naturally we try to avoid this but if you want to play along
then be careful: don't run a non-tor-browser at the same time, make
sure you back up all of your precious bits before using tor-browser
(like `~/.mozilla`), etc.  I generally build and test on amd64 first,
i386 second.  Testing on other architectures greatly appreciated.

`--attila`
