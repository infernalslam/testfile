# How to install วิธีลงโปรแกรมครับ
* install chrome

```
sudo apt-get install google-chrome-stable

```

* install sublime text2 
```
sudo add-apt-repository -y ppa:webupd8team/sublime-text-2
sudo apt-get update
sudo apt-get install sublime-text
```
## แก้erorr
*_Unable to locate package sublime :ERROR_
```
sudo rm /var/lib/apt/lists/lock
sudo rm /var/cache/apt/archives/lock
sudo apt-get update
```










