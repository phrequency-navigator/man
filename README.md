# man

This is a collection of manual pages referencing various topics to be hosted at prime.8s.

There are a couple of hoops to jump through. I don't want to write a script to append anything
to your .zshrc (in my case). Plop the directory wherever you like, and then append this to your
shell init dotfile.

	export MANPATH="$MANPATH:$HOME/man"
	export MANSECT="$MANSECT:8s"

Then, my manpages are accessable by `man 8s page`
