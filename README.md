#Minicraft
Minicraft is a chatonly minecraft client, with the main goal of keeping in touch with the server on much less resources than a full client.

##Binaries
Warning...you should know better than to download an exe file from a stranger and give it your credentials!

Feel free to either ignore my warning or trust me when I say I'll do nothing harmful with the software.

[Download](http://elera.dk/download/minicraft_qt.exe) (26MB because it bundles python and qt)

##Building or running from source
I personally used 32bit python 2.7.3 for this build. and it should just be a matter of running ``python setup.py py2exe``

###Dependencies
 * [PyQT4](http://www.riverbankcomputing.com/software/pyqt/download)
 * [keyring](http://pypi.python.org/pypi/keyring)
 * [pycrypto](https://www.dlitz.net/software/pycrypto/)
 * [pywin32](https://www.dlitz.net/software/pycrypto/)
 * [Py2exe](http://sourceforge.net/projects/py2exe/files/py2exe/0.6.9/)