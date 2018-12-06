# GulpBasicDemo
Gulp Basic Demo

## Start project with below command

Create folder “GulpBasicDemo”
Open cmd and then execute below.
```markdown
> npm init
```

This command will request for below details.
```markdown
package name: (gulpbasicdemo) gulpdemo
version: (1.0.0)
description: gulp basic demo project (convert scss to css)
entry point: (index.js)
test command:
git repository: (https://github.com/kiran3490/GulpBasicDemo.git)
keywords: gulp, scss, css, npm, node
author: Kiran Chauhan
license: (ISC)
```

After providing all details.

```markdown
Is this OK? (yes)
```

Enter 
```markdown
yes
```

Magic …!!!!


There is one file generated in your project directory.
```markdown
package.json
```


With below content.
```markdown
{
  "name": "gulpdemo",
  "version": "1.0.0",
  "description": "gulp basic demo project (convert scss to css)",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/kiran3490/GulpBasicDemo.git"
  },
  "keywords": [
    "gulp",
    "scss",
    "css",
    "npm",
    "node"
  ],
  "author": "Kiran Chauhan",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/kiran3490/GulpBasicDemo/issues"
  },                                                                                                                                                                                            
  "homepage": "https://github.com/kiran3490/GulpBasicDemo#readme"
}                                                                                                                                       
```
## Execute below command to add gulp.
```markdown
npm install gulp --save-dev
```
Which will add below code to package.json file.
```markdown
"devDependencies": {
  "gulp": "^3.9.1"
}
```
## Now Add below file to root directory.
```markdown
gulpfile.js
```

Then paste below content to file.

```markdown
var gulp = require('gulp');

// where task1 is gulp task which will be excuted.
gulp.task('task1', function(){
    console.log('### Task 1 executed ###');
});
```

## Run below command.
```markdown
gulp task1
```

Incase it gives below error then we have to install gulp at machine level.

```markdown
The term 'gulp' is not recognized as the name of a cmdlet
```

To resolve above issue execute below command in cmd.
```markdown
npm install -g gulp
```

Now you are able to see below output after executing.
```markdown
gulp task1
```

## Output
```markdown
[18:32:31] Using gulpfile C:\GulpBasicDemo\gulpfile.js
[18:32:31] Starting 'task1'...
### Task 1 executed ###
[18:32:31] Finished 'task1' after 485 μs
```
