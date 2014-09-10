![AngularJS Express](http://i.imgur.com/nTj9QgN.png)

## AngularJS Express

Component driven AngularJS development heavily inspired by:

- the official [Google recommended AngularJS application structure](https://docs.google.com/document/d/1XXMvReO8-Awi1EZXAXS4PzDzdNvV6pGcuaF4Q9821Es/pub)
- the fantastic [AngularJS styleguide](https://github.com/toddmotto/angularjs-styleguide) by [Todd Motto](http://toddmotto.com/)
- the awesome [AngularJS application structure guidelines](https://github.com/johnpapa/angularjs-styleguide) from [John Papa](http://www.johnpapa.net/).
- the lovely [HarpJS](http://harpjs.com) web server

## Quick example

Install AngularJS Express:

```bash
$ npm install -g ngx-cli
```

Initialize a new application with [`ngx init`](https://github.com/angular-express/ngx-cli):

```bash
$ ngx init
```

Add components to your application with [`ngx install`](https://github.com/angular-express/ngx-cli):

```bash
$ ngx install angular-exception-handler
$ ngx install bootstrap-header
```

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