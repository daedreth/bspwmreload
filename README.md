# bspwmreload
Reload bspwmrc at runtime without executing unrelated commands.

I wonder why you are able to reload sxhkd easily but for bspwmrc you need to look for funny python scripts of questionable quality on github.


# Usage

You need python3 for this, which you probably already have.

  ~~~ sh
  $ wget https://raw.githubusercontent.com/daedreth/bspwmreload/master/bspwmreload
  $ sudo chmod +x bspwmreload
  $ sudo cp bspwmreload /usr/bin/bspwmreload
  ~~~

Just invoke `bspwmreload` whenever you want to you reload the configuration. 

# License
It's MIT, but it's just a little script.

Do what you must.
