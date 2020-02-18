# NS CTF FEB W1

## Challange: 1

In this challange i did run Nmap on host for identify ports and version of service.

![](https://github.com/pritessh/NS-CTF-1/blob/master/images/1.png)

Port 80 was opened so i accessed that ip in broswer.

![](https://github.com/pritessh/NS-CTF-1/blob/master/images/2.png)

After visting website i was scrolling webpage and reached end of the page then noticed one thing which was showed website built in wordpress.

![](https://github.com/pritessh/NS-CTF-1/blob/master/images/3.png)

Then i used wpscan on host for identify version of wordpress, plugins and other things vulnerble or not and it was showed following infomrmation.

![](https://github.com/pritessh/NS-CTF-1/blob/master/images/4.png), ![](https://github.com/pritessh/NS-CTF-1/blob/master/images/5.png)

I noticed one thing which is plugin and it was reflex-gallary and version was 3.1.3. So i did search in google about that plugin with version and it showed reflex-gallary 3.1.3 vulnerable to Arbitrary file upload vulnerability.

![](https://github.com/pritessh/NS-CTF-1/blob/master/images/6.png)

I used metasploit for exploit this vulnerability and gain reverse shell of the system. 

![](https://github.com/pritessh/NS-CTF-1/blob/master/images/7.png)

After getting the shell i went to home directory and there were 4 directories but i could access only one directory which was ganeshgaitonde.

![](https://github.com/pritessh/NS-CTF-1/blob/master/images/8.png)

Then i went to ganeshgaitonde directory and there were many files and directories in which .gopalmath hidden file was contain flag.

![](https://github.com/pritessh/NS-CTF-1/blob/master/images/9.png)

And i got first flag.

![](https://github.com/pritessh/NS-CTF-1/blob/master/images/10.png)


## Challange: 2

In this challange i searched lots of directories and files after that i got one directory var which was contain many directories.

![](https://github.com/pritessh/NS-CTF-1/blob/master/images/11.png)

Then i went to trivedi directory which contain Yayati file and I opened file which contain second flag.

![](https://github.com/pritessh/NS-CTF-1/blob/master/images/12.png)
