# The Go generator

A [Yeoman](http://yeoman.io) generator for [Go](http://golang.org/).

See the [Golang documentation](https://golang.org/doc/) for more information.

## Why Go generator ?

The Go programming language is an open source project to make programmers more productive.

Golang team defines [guidelines](https://github.com/yeoman/yo) to organize your code and structure your application.

The generator builds a standard directory hierarchy for your new golang project.

## Usage

Install Yeoman:

    npm install -g yo


Install Go generator
    
    sudo git clone https://github.com/BenC-/generator-go.git /usr/local/generator-go
    cd /usr/local/generator-go
    sudo npm link

Run generator

     yo go 

![Alt text](/../pictures/pictures/go-generator.png?raw=true "yo go command")

It will generate a standard golang project plus a makefile and a .gitignore file.

![Alt text](/../pictures/pictures/go-generator1.png?raw=true "yo go tree result")

Build your project and run it with `make run`.

![Alt text](/../pictures/pictures/go-generator2.png?raw=true "yo go make run")

Start your project !

## Contributing

If you would like to submit pull requests, please feel free to apply.

## Dependencies

* Golang
* Make 
* [Yo](https://github.com/yeoman/yo) (the scaffolding tool from Yeoman)
