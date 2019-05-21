# SayHello

*Say hello to the world.*

Demo: http://sayhello.helloflask.com

![Screenshot](http://helloflask.com/screenshots/sayhello.png)

## Installation

```
$ git clone https://github.com/cardinalion/sayhello.git
$ cd sayhello
$ virtualenv venv
$ source venv/bin/activate
$ flask forge
$ flask run
* Running on http://127.0.0.1:5000/
```

## License

This project is licensed under the MIT License (see the
[LICENSE](LICENSE) file for details).

## Main Packages

1. Front-end: Bootstrap-Flask(bootstrap, rendering), Flask-Moment(timestamp)
2. Back-end: Flask-SQLAlchemy(database), Flask-WTF(forms)
3. Others: Faker(fake posts), Flask-DebugToolbar(debug), python-dotenv(enviroment variables)
