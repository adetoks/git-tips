To check whether or not you have Node.js installed, visit your console / command line and type:
```
> node -v
```

If this command goes unrecognized, you need to install Node.js.

1. Visit the Node.js download page and choose either the Windows or Mac installer based on your OS.
1. Accept the agreement, choose an installation folder, and hit Next on the Custom Setup page. By default, it will install the npm package manager which we will need.

To install the Angular-CLI. This tool allows you to create Angular projects as well as help you with various development tasks.

At the console, type:
```
> npm install -g @angular/cli
```
Then:
```
> ng -v
```

When we run ng -v while inside an Angular project folder, it will also provide us with which version of Angular that particular project is using. 

To start a new ng4 project, at the console, type:
```
> ng new my-project-name
// let it install

> cd my-project-name
```

After about a minute or so, you'll be all set!
