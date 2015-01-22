# chat-example

This is the source code for a very simple chat example used for 
the [Getting Started](http://socket.io/get-started/chat/) guide 
of the Socket.IO website.

Please refer to it to learn how to run this application.

# how to run on heroku

```
$ git clone https://github.com/yosuke-furukawa/iojschat.git
$ cd iojschat
$ heroku create
$ heroku ps:scale web=1
$ git push heroku master
```
