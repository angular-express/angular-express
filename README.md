![AngularJS Express](http://i.imgur.com/nTj9QgN.png)

## AngularJS Express

Component driven AngularJS development made easy!

Heavily inspired by:

- the official [Google recommended AngularJS application structure](https://docs.google.com/document/d/1XXMvReO8-Awi1EZXAXS4PzDzdNvV6pGcuaF4Q9821Es/pub)
- the fantastic [AngularJS styleguide](https://github.com/toddmotto/angularjs-styleguide) by [Todd Motto](http://toddmotto.com/)
- the awesome [AngularJS application structure guidelines](https://github.com/johnpapa/angularjs-styleguide) from [John Papa](http://www.johnpapa.net/).
- the lovely [HarpJS](http://harpjs.com) web server

AngularJS Express helps you kickstart your AngularJS applications in **seconds** using:

- **boilerplates** to generate new AngularJS application structures
- **components** to add features to existing applications

To make your life easy, it also comes with a CLI tool.

## Quick example

Lets dive straight into an example!

First install the AngularJS Express CLI tool:

```bash
$ npm install -g ngx-cli
```

The CLI tool is installed globally on your machine, so you only have to do this once.

Now lets create a directory for a new application:

```bash
$ mkdir myapp
$ cd myapp
```

You could now start adding code manually or run a Yeoman generator to scaffold your initial code.

AngularJS Express uses the concept of **boilerplates** to rapidly initialize entire application structures.

We will talk in detail about boilerplates later. For now, lets just initialize the default boilerplate:

```bash
$ ngx init
```

You now have a complete AngularJS application installed in your directory and you can start coding immediately and never look back.

However, AngularJS Express also offers you the ability to add individual components to your application using [`ngx install`](https://github.com/angular-express/ngx-cli):

```bash
# Add a custom exception handler
$ ngx install angular-exception-handler

# Add a Bootstrap compatible header with a navbar
$ ngx install bootstrap-header

# Add CSS padding helper classes
$ ngx install css-padding-helper-classes
```

You now have a complete AngularJS application with a custom exception handler and a set of CSS helper classes.

**In less then 60 seconds... without writing any code!**

## How it works

AngularJS Express consists of 2 core concepts:

- **boilerplates** to rapidly scaffold new applications
- **components** to quickly add features to an existing application.

where each **boilerplate**:

- scaffolds a new AngularJS Express application
- is hosted in its own Git repository
- is well documented

and each **component**:

- adds a certain feature to an existing AngularJS Express application
- is hosted in its own Git repository
- contains its own styles, scripts and templates
- is well documented
- contains its own unit tests


## Links

- [ngx-cli](https://github.com/angular-express/ngx-cli): the AngularJS Express CLI tool
- [ngx-boilerplates](https://github.com/ngx-boilerplates): directory of official boilerplates
- [ngx-components](https://github.com/ngx-components): directory of official components

## FAQ

**Why AngularJS Express?**

When working with clients I often found myself setting up the same boilerplate over and over again. Fullstack boilerplates are awesome, but in reality I found myself stripping or customizing a lot of the generated boilerplate.

I wanted something different that worked from the ground up: first initialize a boilerplate and then add small components on top of that.

**Why not use a Yeoman generator?**

I love Yeoman and use it often. However, when writing reusable components I found myself spending more time coding on the generator part than on the component part. And having to run the generator each time to see if the outcome was correct didn't really make my life easier either.

So while Yeoman is great for many things, it just didn't fit the requirements for AngularJS Express.
