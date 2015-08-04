Hugo Docker Demo - EVLUG
========================
(Built and tested on Ubuntu 14.4 AWS AIM)  

Dependancies:  
	- [git](http://www.git-scm.com/)  
	- [go](http://golang.org) (language)  
	- [hugo](http://gohugo.io)  
	- [docker](http://docker.com)  

	
Git:  
(for more detailed or other OS instructions please see: [Git Docs](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git))  
	- install git
		`$ sudo apt-get update`
		`$ sudo apt-get install git`  

Go:  
(for more detailed or other OS instructions please see: [Go Docs](http://golang.org/doc/install))  
 	- Add `/usr/local/go/bin` to PATH environment variable  
		`$ sudo export PATH=$PATH:/usr/local/go/bin`  
	- Install Go (language)  
		`$ sudo apt-get install golang`  
	
Hugo:  
(for more detailed or other OS instructions please see: [Hugo Docs](http://gohugo.io/overview/installing/))  
	- install hugo  
		`$ export GOPATH=$HOME/go`  
		`$ go get -v github.com/spf13/hugo`  

Docker:  
(for more detailed or other OS instructions please see: [Docker Docs](http://docs.docker.com/installation/))  
	- Install Docker  
		(Check if wget installed)  
		`$ which wget` <- If installed skip next two commands  
		(Installing wget)  
		`sudo apt-get update`  
		`sudo apt-get install wget`  
		`wget -q0- https://get.docker.com/ | sh`
