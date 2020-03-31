Overview
========

luadec-openwrt-tplink is a Lua decompiler for lua 5.1 , and experimental for lua 5.2 and 5.3.
However, this version is specifically patched for lua 5.1 according to the changes made by openwrt and some additions from TP-Link sources


It is based on viruscamp's luadec https://github.com/viruscamp/luadec and Hisham Muhammad's luadec which targeted lua 5.0.x and LuaDec51 by Zsolt Sz. Sztupak.

luadec-openwrt-tplink  is free software and uses the same license as the original LuaDec.


Compiling
---------
```
git clone https://github.com/RE-Solver/luadec-openwrt-tplink
cd luadec-openwrt-tplink
cd lua-5.1
make linux
cd ../luadec
make LUAVER=5.1
```


Usage
-----
* decompile lua binary file:  
  luadec abc.luac  
* disassemble lua source or binary  
    luadec -dis abc.lua  


Use -h to get a complete list of usable parameters


Credits
-------

Originally forked from viruscamp's luadec https://github.com/viruscamp/luadec

# luadec-openwrt-tplink
