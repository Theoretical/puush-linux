puush-linux
===========

A Bash script for uploading files to puush.me from Linux. Many thanks to @Westie for his insights on puush's undocumented API :)

Using
-----

* Get curl if you don't have it already. Most package managers have it as `curl` (apt-get install curl, yum install curl), or check this page: http://curl.haxx.se/download.html
* Get puush from here: https://github.com/blha303/puush-linux/raw/master/puush
* Copy 'puush' to /usr/local/bin, and use `chmod +x /usr/local/bin/puush`.
* Use it with `puush file.name`. 

You'll need to set up an environment variable, PUUSH_API_KEY. You can do this per-session with `export PUUSH_API_KEY="apiKeyHere"`, or by putting that command in `~/.bashrc`.
