# Express application generator

You can run the application generator with the npx command (available in Node.js 8.2.0).
```
$ npx express-generator
```
<br>

For earlier Node versions, install the application generator as a global npm package and then launch it.
```
$ npm install -g express-generator
$ express
```
<br>

Display the command options with the -h option:
```
$ express -h
```
<br>

The following creates an Express app named **myapp**. The app will be created in a folder named **myapp** in the current working directory and the view engine will be set to **Pug**:

```
$ express --view=pug myapp
```
<br>

Install dependencies:
```
$ npm install
```
<br>

On MacOS or Linux, run the app with this command:
```
$ DEBUG=myapp:* npm start
```

On Windows Command Prompt, use this command:
```
> set DEBUG=myapp:* & npm start
```

On Windows PowerShell, use this command:
```
PS> $env:DEBUG='myapp:*'; npm start
```
<br>

The generated app has the following directory structure:
```
.
├── app.js
├── bin
│   └── www
├── package.json
├── public
│   ├── images
│   ├── javascripts
│   └── stylesheets
│       └── style.css
├── routes
│   ├── index.js
│   └── users.js
└── views
    ├── error.pug
    ├── index.pug
    └── layout.pug

7 directories, 9 files
```
