(py_develop_1)PS D:\Project\PyProjects\HelloBottle\HelloWorld> pip install Flask
Collecting Flask
  Downloading Flask-0.12.2-py2.py3-none-any.whl (83kB)
    100% |################################| 92kB 245kB/s
Collecting itsdangerous>=0.21 (from Flask)
  Downloading itsdangerous-0.24.tar.gz (46kB)
    100% |################################| 51kB 1.1MB/s
Collecting click>=2.0 (from Flask)
  Downloading click-6.7-py2.py3-none-any.whl (71kB)
    100% |################################| 71kB 1.1MB/s
Collecting Werkzeug>=0.7 (from Flask)
  Downloading Werkzeug-0.12.2-py2.py3-none-any.whl (312kB)
    100% |################################| 317kB 1.1MB/s
Collecting Jinja2>=2.4 (from Flask)
  Downloading Jinja2-2.9.6-py2.py3-none-any.whl (340kB)
    100% |################################| 348kB 504kB/s
Collecting MarkupSafe>=0.23 (from Jinja2>=2.4->Flask)
  Downloading MarkupSafe-1.0.tar.gz
Building wheels for collected packages: itsdangerous, MarkupSafe
  Running setup.py bdist_wheel for itsdangerous ... done
  Stored in directory: C:\Users\manan1\AppData\Local\pip\Cache\wheels\fc\a8\66\24d655233c757e178d45dea2de22a04c6d92766ab
fb741129a
  Running setup.py bdist_wheel for MarkupSafe ... done
  Stored in directory: C:\Users\manan1\AppData\Local\pip\Cache\wheels\88\a7\30\e39a54a87bcbe25308fa3ca64e8ddc75d9b3e5afa
21ee32d57
Successfully built itsdangerous MarkupSafe
Installing collected packages: itsdangerous, click, Werkzeug, MarkupSafe, Jinja2, Flask
Successfully installed Flask-0.12.2 Jinja2-2.9.6 MarkupSafe-1.0 Werkzeug-0.12.2 click-6.7 itsdangerous-0.24
(py_develop_1)PS D:\Project\PyProjects\HelloBottle\HelloWorld> cd ..\..\HelloFlask
(py_develop_1)PS D:\Project\PyProjects\HelloFlask> ls


    Directory: D:\Project\PyProjects\HelloFlask


Mode                LastWriteTime     Length Name
----                -------------     ------ ----
d----         6/23/2017   4:48 PM            .idea
-a---         6/23/2017   4:48 PM        159 HelloWorld.py


(py_develop_1)PS D:\Project\PyProjects\HelloFlask> python .\HelloWorld.py
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
127.0.0.1 - - [23/Jun/2017 16:51:16] "GET / HTTP/1.1" 200 -
127.0.0.1 - - [23/Jun/2017 16:51:16] "GET /favicon.ico HTTP/1.1" 404 -