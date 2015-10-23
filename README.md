# How to install วิธีลงโปรแกรมครับ
* install chrome

```
sudo apt-get install google-chrome-stable

```

*install sublime text2 
```
sudo add-apt-repository -y ppa:webupd8team/sublime-text-2
sudo apt-get update
sudo apt-get install sublime-text
```
**_แก้ERROR_**
**_Unable to locate package sublime :ERROR_**
```
sudo rm /var/lib/apt/lists/* -vf 
sudo rm /var/lib/apt/lists/lock
sudo rm /var/cache/apt/archives/lock
sudo apt-get update
```

* sublime launcher : install packet 

```
>
1.  view -> show console
2.   copy message :

 import urllib2,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); os.makedirs( ipp ) if not os.path.exists(ipp) else None; urllib2.install_opener( urllib2.build_opener( urllib2.ProxyHandler()) ); by = urllib2.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); open( os.path.join( ipp, pf), 'wb' ).write(by) if dh == h else None; print('Error validating download (got %s instead of %s), please try manual install' % (dh, h) if dh != h else 'Please restart Sublime Text to finish installation') 

**CR** >> https://packagecontrol.io/installation#st2
3.  paste enter -> esc
4.  you should close program now 
5.  open program again for install packet etc..
```
-------------------------------------------------------



*install packet !!! (sublime)
```
1. emmet 
2. htmlbeautify
3. standard fomat
4. theme : better for implement : Search for { Devastate } is nice!!
https://packagecontrol.io
```

------------------------------------------------------------------------------------
*install node.js
```
1. sudo apt-get install nodejs
2. sudo apt-get install npm
```
----------------------------------------------------------------------------------
**if error!**
**The program 'node' can be found in the following packages:**
* node
* nodejs-legacy
**Try: sudo apt-get install <selected package>**
```
1. sudo ln -s `which nodejs` /usr/local/bin/node
```
------------------------------------------------------------------------------
**check node !! code**
```
1. node -v
2. npm -v
```
----------------------------------------------------------------------------------
**_npm install_**
**£ express (you should create a directory)**
```
1. npm init
2. npm install express --save
```
**£ socket.io**
```
1. npm install --save socket.io
```









