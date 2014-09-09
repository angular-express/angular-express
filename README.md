![AngularJS Express](http://i.imgur.com/nTj9QgN.png)

## Goal

Component driven AngularJS development using:

- *boilerplates* to kickstart new AngularJS projects
- *components* to add functionality to your AngularJS applications

where each boilerplate:

- provides the application directory structure
- takes care of boilerplate specific dependencies
- configures the build process
- can be customized once initialized

and each component:

- is plug-and-play
- is reusable
- contains its own scripts, styles, templates and documentation
- is hosted on GitHub
- can be customized once installed

while combining best practices of:

- the official [Google recommended AngularJS application structure](https://docs.google.com/document/d/1XXMvReO8-Awi1EZXAXS4PzDzdNvV6pGcuaF4Q9821Es/pub)
- the fantastic [AngularJS styleguide](https://github.com/toddmotto/angularjs-styleguide) by [Todd Motto](http://toddmotto.com/)
- the lovely [HarpJS](http://harpjs.com) web server

## Quick example

Install AngularJS Express:

```bash
$ npm install -g ngx-cli
```

Create an application using the [default boilerplate](https://github.com/ngx-boilerplates/default):

```bash
$ ngx init
```

Add components from the [ngx-components](https://github.com/ngx-components/default) directory:

```bash
$ ngx install homepage
$ ngx install header
$ ngx install footer
```

Or you can install your own boilerplate:

```bash
$ ngx init -b your-github-name/your-boilerplate-repo
```

And add your own components:

```bash
$ ngx install -b your-github-name/your-homepage-component-repo
$ ngx install -b your-github-name/your-header-component-repo
$ ngx install -b your-github-name/your-footer-component-repo
```
