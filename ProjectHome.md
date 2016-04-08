## SQL Injection and Web Attack Framework ##
Enema is not auto-hacking software for script kiddies. This is dynamic tool for professional pentesters.

### Current stable version: 1.7 ###

  * Whats new:
    1. Added custom plugins support.

Latest development version:

```

svn checkout http://enema.googlecode.com/svn/trunk/ enema
```

  * Requirements:
    1. [Python 3.2](http://python.org/download/releases/3.2.2/)
    1. [PyQt4](http://www.riverbankcomputing.co.uk/software/pyqt/download)


---


  * Features:
    1. Multi-platform.
    1. User-friendly graphical interface.
    1. Multithreaded.
    1. Dump.
    1. Customise your queries
    1. Create your custom plugins to automate attacks

  * Supported for today:
    1. POST, GET, Headers (User-Agent, Cookie, Referer, X-Forwarded-For, Custom Header ...)
    1. MSSQL >=2000 and MySQL>=5.0

  * Injection methods supported for today:
    1. Error based injection.
    1. Union based injection (using subquery).
    1. Blind (time and boolean based)

![http://img856.imageshack.us/img856/6650/dbstructure.png](http://img856.imageshack.us/img856/6650/dbstructure.png)

![http://img33.imageshack.us/img33/4853/queryn.png](http://img33.imageshack.us/img33/4853/queryn.png)

![http://img827.imageshack.us/img827/447/dumpf.png](http://img827.imageshack.us/img827/447/dumpf.png)