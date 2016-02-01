# Installation Instructions

## Building the awssh binary from source

**Assumption:  You have Golang installed and your GOPATH is properly set as per the instructions in [Getting Started.](https://golang.org/doc/install) as well as have all of the common version control systems installed(git, mercurial, subversion, and bzr)**

Open up your shell and do the following

```
mkdir -p $GOPATH/src/github.com/msanterre/
cd $GOPATH/src/github.com/msanterre

git clone https://github.com/msanterre/awssh.git
cd awssh/

go get && go build
```

This will build and place the binary in the current directory, which can then be moved into your PATH or aliased in the shell configuration of your choice.