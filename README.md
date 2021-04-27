# TinyFaces 👦🏼👨🏾👩🏻
Free stock avatars for everyone

<img src="/Public/images/github-header.png?raw=true" width="888">

**Important Notice:** This this still works but is all built on [Vapor 1.5](https://docs.vapor.codes/1.5/). Vapor has come a long way in the past years and this isn't the best practice anymore. Check out [Vapor 4](https://docs.vapor.codes/4.0/) if you are into Server Side Swift.

Tiny Faces is a free crowd-sourced avatar gallery to use in your personal or commercial projects

Also check out our [TinyFaces Sketch Plugin](https://github.com/maximedegreve/TinyFaces-Sketch-Plugin)

## 🤖 Before building (dependencies)

* Install [Vapor Toolbox](https://github.com/vapor/toolbox)

### macOS:
* Run ```brew install gd```
* Run ```brew install mysql``` followed by ```mysql_secure_installation``` to setup a database
* Install [Xcode](https://developer.apple.com/xcode/)
* Run ```vapor xcode```, this will create the Xcode project


### Ubuntu (server):
* Run ```sudo apt-get install libgd-dev```
* Run ```apt-get install libmysqlclient-dev```

### Database:
* Create a MySQL database called ```marvel_faces```, e.g. using the mysql CLI: ```CREATE DATABASE marvel_faces;```
* [Config/mysql.json](Config/mysql.json) contains the database credentials

## 🚧 Building

### macOS:
* Run the ```App``` target in Xcode
* TinyFaces should now be running on [http://localhost:8080](http://localhost:8080)
* First time run [http://localhost:8080/seed/](http://localhost:8080/seed/) to seed the database tables with default data.

## 📖 Documentation

Visit the Vapor web framework's [documentation](http://docs.vapor.codes) for instructions on how to use this package.

## 💧 Community

Join the welcoming community of fellow Vapor developers in [Slack](http://vapor.team).

## 🔧 Compatibility

This package has been tested on macOS and Ubuntu.
