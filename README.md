#### Copyright 2013 
##### Sudheesh Singanamalla <sudheesh1995@outlook.com>. 
#### All Rights Reserved.

This console software helps you to download lectures (videos and slides) from Coursera.org
You can choose any to download. Its console based.

Current supported completed/userenrolled courses:
1, Model Thinking
2, Game Theory
3, Cryptography
4, Software as a Service
5, Probabilistic Graphical Models
6, Design and Analysis of Alogrithms I
You can just add courses by yourslef in main() if you registered them on time before. 

Developed with pyton 2.7.
Dependent on 'mechanize'. Use 'easy_install mechanize' first if 'mechanize' not installed.
Be sure to change the email and the password in main() to yours first before running.
Only support single thread to download right now.

See the mechanize library attached as a folder with this repo. Install it.
Follow these steps for it.

In case you are using the library attached in the mechanize folder with this code distribution.<br>
[1] Do ```python setup.py install```

In case you wish to install mechanize to your shell so that you can use it in projects later. Go ahead.<br>
[1] Install pip.<br>
[2] Do ```pip install mechanize```<br>
[3] You can get pip from http://www.pip-installer.org/en/latest/ <br>


Once its installed.
```
Run as: 'python downloadcourse.py' will download to CWD.
Run as: 'python downloadcourse.py <dir>' will download to path <dir>.
```

For download contents selection input, already handled common intuition from the beginning. 
```
Valid input: 3, 5, 7-18 or 3,5,7-18 or 3 5 7-18 or multiple space or comma seperated. 
Range input supports 7-18 or 7:18.
```

Version 1.0 :

Current links resolve and match method is not elegant. 
To solve all video and subtitle matching problem, need time to change the current link and name extracting method.
Will solve this later. 

In case any of you wish to make this program/project better. Go ahead. Community Project.