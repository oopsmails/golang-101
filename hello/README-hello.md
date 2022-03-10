
# Golang Hello

## Good Resources

- old, but will take a look

https://www.youtube.com/watch?v=0NTKMKDsCTE&list=PL64wiCrrxh4Jisi7OcCJIUpguV_f5jGnZ&index=44

https://www.youtube.com/watch?v=OSPNUKoN81o&list=PLq9Ra239pNZC0MgMN4j6ZiPHv_c0UPnBX&index=1

## Install

- Download zip and put in ~/Documents/programs

~/.bashrc

export GRADLE_HOME=/home/albert/Documents/programs/gradle-7.3.3
export PATH=$PATH:$GRADLE_HOME/bin

- vs code, install Go extension, from Go Team

Error: visual code golang extensions cannot find package

```
albert@albert-mint20:~/Documents/sharing/github/golang-101$ go mod init hello <-------------- init project, will generate go.mod in project folder
go: creating new go.mod: module hello
go: to add module requirements and sums:
        go mod tidy
albert@albert-mint20:~/Documents/sharing/github/golang-101$ cd hello/
albert@albert-mint20:~/Documents/sharing/github/golang-101/hello$ go mod tidy <-------------- will check libraries and generate go.sum
go: finding module for package rsc.io/quote
go: downloading rsc.io/quote v1.5.2
go: found rsc.io/quote in rsc.io/quote v1.5.2
go: downloading rsc.io/sampler v1.3.0
go: downloading golang.org/x/text v0.0.0-20170915032832-14c0d48ead0c
albert@albert-mint20:~/Documents/sharing/github/golang-101/hello$ go run hello.go <-------------- run hello.go
Hello, World!
Don't communicate by sharing memory, share memory by communicating.
```






