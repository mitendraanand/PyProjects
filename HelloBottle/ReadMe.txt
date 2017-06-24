(py_develop_1)PS C:\Users\manan1> pip install -U bottle
Collecting bottle
  Downloading bottle-0.12.13.tar.gz (70kB)
    100% |################################| 71kB 229kB/s
Building wheels for collected packages: bottle
  Running setup.py bdist_wheel for bottle ... done
  Stored in directory: C:\Users\manan1\AppData\Local\pip\Cache\wheels\49\cf\37\132916b926fae01d6e27d94c0018e3ad07452ec37
60e24a36a
Successfully built bottle
Installing collected packages: bottle
Successfully installed bottle-0.12.13
(py_develop_1)PS C:\Users\manan1> D:
(py_develop_1)PS D:\> cd .\Project\PyProjects\HelloBottle\HelloWorld
(py_develop_1)PS D:\Project\PyProjects\HelloBottle\HelloWorld> ll
ll : The term 'll' is not recognized as the name of a cmdlet, function, script file, or operable program. Check the
spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ ll
+ ~~
    + CategoryInfo          : ObjectNotFound: (ll:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

(py_develop_1)PS D:\Project\PyProjects\HelloBottle\HelloWorld> ls


    Directory: D:\Project\PyProjects\HelloBottle\HelloWorld


Mode                LastWriteTime     Length Name
----                -------------     ------ ----
d----         6/23/2017   3:51 PM            .idea
-a---         6/23/2017   3:51 PM        138 HelloWorld.py


(py_develop_1)PS D:\Project\PyProjects\HelloBottle\HelloWorld> .\HelloWorld.py
(py_develop_1)PS D:\Project\PyProjects\HelloBottle\HelloWorld> python .\HelloWorld.py
Bottle v0.12.13 server starting up (using WSGIRefServer())...
Listening on http://localhost:8080/
Hit Ctrl-C to quit.

127.0.0.1 - - [23/Jun/2017 15:53:18] "GET /hello HTTP/1.1" 200 12
127.0.0.1 - - [23/Jun/2017 15:53:18] "GET /favicon.ico HTTP/1.1" 404 742