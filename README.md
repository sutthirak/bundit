#Bundit

Bundit is an application for creating a **service** or **daemon** in Linux enviorment

User just copy the file that was created by Bundit to `/etc/init.d` and start a service with command like this

```
sudo service *you_app* {start|stop|restart}
```

##Requirement

Bundit was written in Go. You have to install Go by following this document first.

https://golang.org/doc/install

Then you can get and install Bundit with Go command

```
go get github.com/sutthirak/bundit
go install github.com/sutthirak/bundit
```

Now you can start Bundit with this command

```
bundit
```
