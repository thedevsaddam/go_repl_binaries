GO REPL binary
==================================================
GO REPL is a simple application promising to write/compile/run code in terminal, inspired by python shell

![Task screenshot](https://github.com/thedevsaddam/go-repl/blob/master/screenshot.png)

## Download

| OS      	| x86                                                                                      	| x86_64                                                                                      	|
|---------	|------------------------------------------------------------------------------------------	|---------------------------------------------------------------------------------------------	|
| Mac     	| [Download](https://github.com/thedevsaddam/go_repel_binaries/blob/master/v1/mac_x86.zip)     	| [Download](https://github.com/thedevsaddam/go_repel_binaries/blob/master/v1/mac_x86_64.zip)     	|
| Linux   	| [Download](https://github.com/thedevsaddam/go_repel_binaries/blob/master/v1/linux_x86.zip)   	| [Download](https://github.com/thedevsaddam/go_repel_binaries/blob/master/v1/linux_x86_64.zip)   	|
| FreeBSD 	| [Download](https://github.com/thedevsaddam/go_repel_binaries/blob/master/v1/freebsd_x86.zip) 	| [Download](https://github.com/thedevsaddam/go_repel_binaries/blob/master/v1/freebsd_x86_64.zip) 	|
| Windows 	| [Download](https://github.com/thedevsaddam/go_repel_binaries/blob/master/v1/windows_x86.zip) 	| [Download](https://github.com/thedevsaddam/go_repel_binaries/blob/master/v1/windows_x86_64.zip) 	|

### Installation
On MacOS/Linux download the binary file and copy the file to `/user/local/bin/` and set permission to executable
```bash
$ cp gorepl /usr/local/bin/gorepl
$ sudo chmod +x /usr/local/bin/gorepl
```
On Windows set the `gorepl` path in your environment and run in terminal

If you are interested to build the code for your computer then
```bash
$ git clone https://github.com/thedevsaddam/go-repl.git #clone into your $GOPATH/src/
$ ./build
```

### Usage
After writing your code use a blank line then
write `:cr` and hit `enter` to ***compile*** and ***run*** code

Please see the example
![Task screenshot](https://github.com/thedevsaddam/go-repl/blob/master/sum.png)

### Contribution
If you love the application please feel free to send pull requests or rise issue

### **License**
The **GO REPL** is an open-source software licensed under the [MIT License](https://github.com/thedevsaddam/go-repl/blob/master/LICENSE.md).