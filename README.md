##ss.conf for Surge!
This is a conf file for Surge!

In order to use shad0ws0cks in Surge.

> `ssconf.py` can generate both gfwlist and whitelist, and auto update the gfwlist and adlist, whitelist's auto update function is not implement yet.

##Proxy list 
Proxy list was generated from gfwlist, all marked with `force-remote-dns`.

White list come from https://goo.gl/tBixve.

##Anti ads
Ad's list from https://goo.gl/70DG6i.


##How-to-use
Just use `gfwlist-main.conf` or `whitelist-main.conf` directly. Both in `configFileHere` directory!

>Or use `ssconf.py` to generate config file.

Once you generated the config,you can use sub-config to add more server config.

For example:

    US-Node4.conf:

    #!PROXY-OVERRIDE:gfwlist-main.conf

    [Proxy]
    Proxy = custom,127.0.0.1,1080,rc4-your_password_here,https://github.com/R0uter/ss.conf-for-surge/raw/master/ss.module

So next time you can just update `gfwlist-main.conf` or `whitelist-main.conf` instead of update all config file!

###Note:
Make sure edit `ssconf.py` or config file first!

change your ss server config, like server ip, server port, and your password.


    #Your SS IP or Domain here
    server = '127.0.0.1'
    #Your SS port
    port = '1080'
    #Your SS method
    method = 'aes-256-cfb'
    #Your SS password
    passwd = 'your_password_here'

##MIT License (MIT)

The MIT License (MIT)

Copyright (c) 2015-2016 R0uter

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

