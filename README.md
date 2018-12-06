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

