# Development Log #7 (5/05/23)
This is the seventh development log of NoLexa.


## Notice
Development will be slightly delayed for temporary reasons, and will be back within a week or two.


### Sneak Peek
While updating Tasks I accidentally leaked some code of NoLexa, so it would be a great time to go through and explain what it does since NoLexa's development will be delayed.


### IsUpToDate()
![image](https://github.com/byronbytes/NoLexa/assets/53088136/261b290b-a118-480f-8e23-b7e3baabd0b0)
This is a simple function, it checks whether or not NoLexa is up to date by comparing the string with an online string. GetCloudVersion has been slightly modified for Tasks, but the code is almost the same.


### StartUpdate()
![image](https://github.com/byronbytes/NoLexa/assets/53088136/ecfecb29-6d41-47ef-a0a8-ae6072807b90)
This starts the update function, which was left almost unchanged besides the URL, Agent, and zip name.



![image](https://github.com/byronbytes/NoLexa/assets/53088136/ce674ea8-0238-404e-9e1c-fff82f79bc6a)


This creates the temporary directory to hold the update files, hence the name UpdateCache.


![image](https://github.com/byronbytes/NoLexa/assets/53088136/38e82dd9-c87a-4a38-ac7e-2b71b8dc079f)


This moves the downloaded file into the temporary directory, and unzips the file into the directory.


![image](https://github.com/byronbytes/NoLexa/assets/53088136/a2b67f62-18c1-4285-9846-38bad11a2548)


Finally, it runs the newest version. At the time of developing the Update function for NoLexa, I was using Tasks to test how it worked, which is why it does `Process.Start("Tasks.exe");`.
