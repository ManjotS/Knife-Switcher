Knife-Switcher
==============

An easy way to switch knife.rb configurations for chef

Installation:
-------------

git clone, then copy to /bin/

Run ```chmod +x /bin/knife-switcher```

Make sure you:

* you do **not** have a file named knife.rb
* you **do** have your files named as knife-[server name here].rb
* have your configurations/rb files in ~/.chef/


Flags: 
------

-y	prevents prompt to confirm overwrite of knife.rb

Notes:
------

I like to alias this as ku
```alias ku='knife-switcher -y'```
