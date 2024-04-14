# PythonWheels4Termux
Helps to use some hard packages or helps build other packages, that weren't compiled for termux. 

## Install (optional)
If you don't want to add ```--extra-index-url``` argument everytime, you can type this command
```
pip config set global.extra-index-url https://Loamf.github.io/PyW4Termux/WHLs-index
```
and pip will use PyW4Termux as 2nd package index

## Usage
```
pip install some_packages --extra-index-url https://loamf.github.io/PyW4Termux/WHLs-index
```
________________________________________

Lib libcurl-impersonate-chrome for curl-cffi requires some modules, install them using
```
pkg install rtmpdump libgsasl libpsl openldap
```

________________________________________

If you want me to upload some other wheels, you can say about it in [issues](https://github.com/Loamf/PyW4Termux/issues)


