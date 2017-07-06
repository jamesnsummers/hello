# hello
My First Go App

#### What is Go?

Go is an open source programming language that makes it easy to build simple, reliable, and efficient software.

Since Go is mainly used to build software, it was a little difficult finding a good resource for using it to build a web app. Below is a link to best resource I found from Peter Bourgon:

[Tutorial on How I Start.](http://howistart.org/posts/go/1/)



The following is the first portion of the tutorial offered by Mr. Bourgon:

### Install Go

```
brew install go
```
### Verify Installation of Go

```
$ go version
go version go1.8.3 darwin/amd64
```

### Set your GOPATH

```
$ echo 'export GOPATH=$HOME' >> $HOME/.profile
$ source $HOME/.profile
$ go env | grep GOPATH
GOPATH="/Users/jamesnsummers"
```

### Create a LocalDirectory for a New Project
```
$ mkdir -p $GOPATH/wdi/src/github.com/jamesnsummers
gmkdir: created directory '/Users/jamesnsummers/wdi/src'
gmkdir: created directory '/Users/jamesnsummers/wdi/src/github.com'
gmkdir: created directory '/Users/jamesnsummers/wdi/src/github.com/jamesnsummers'
```
### Create a New Empty Repo on Github
-Name the repo "hello"

### Clone Github Repo to Local Repo

```
$ cd  wdi/src/github.com/jamesnsummers/
$ git clone https://github.com/jamesnsummers/hello.git
```

-Change directories into the hello directory<br>
-Create a new file called main.go

```

$ cd hello
$ touch main.go
```

### Write Your First Go Program!
Copy the following into main.go:
```
package main

func main() {
    println("hello!")
}
```

### Invoke Go Build in the Terminal
```
$ go build

```

### Run the Hello Program in the Terminal
```
$ ./hello
hello!
```

##### That's it! You wrote a Go Program!
##### To quote Mr. Bourgon:
"Easy! Even after several years of writing Go, I still start all of my new projects like this. An empty git repo, a main.go, and a little bit of typing."

### Closing Thoughts
After going through the tutorial offered on the main [Go website](https://golang.org/), I quickly found myself in uncharted waters. Go seems to be a language used mainly to build software platforms. It also seems to be closer to the computer language; there were a lot of comparisons to C and Java in some of the tutorials, neither of which I have tried to tackle, yet.

There were a few things that stood out to me about this language:

-The syntax is simple but not very easy to grasp on first read.<br>
-Using it to build a web app may be overkill, as it seems to mainly be used to build fairly complex software systems.<br>
-There are some similarities with JavaScript: variables, functions, constants, if/else statements, for loops, arrays<br>


It was a bit daunting to jump into, but after looking over [this tutorial](http://howistart.org/posts/go/1/) from Mr. Bourgon, I feel more confident in my ability to continue to pursue learning this language. Whether or not this is the best language to use to build web apps, as a coder it can be useful to have this as a skill when pursuing new career opportunities. 
