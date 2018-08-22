# First Application

Create through command

```bash
ng new FirstApp
```

## Folder structure

- e2e
  - End to end testing. Used for unit testing of anguler applications.
- mode_modules
  - Dependencies of the project. We never commit this folder and it must be listed in .gitignore file.
- src
  - Our source code. Most of the this, we code only in this folder.
- .editorconfig 
  - Nothing to do with angular. It is widely used format of defining editor configuration. With this, different users, using different editors, can follow same code structure like number of spaces used for indentation, indentation style (tab or space) etc. VS Code plugin `EditorConfig for VS Code` read this file and apply configurations in all new files.
- .gitignore
  -  Git file mentioning what should not be committed to git. We should list `node_modules` here.
- angular.json 
  - Used to configure angular application. We will discuss about this file later.
- package.json & package-lock.json
 -  Files used by `npm` to list our dependencies and their versions.
- tsconfig.json
  - Type script configuration. It defines for settings like what TS should be compiled into (Default- ES5), output (compiled files) directory etc. We should not be changing anything there, angular cli configures it for us.
- tslint
  -  Lint configuration for Type Script. Used to define some coding styles so that all developers in a project follow same basic coding style.


## How angular app works?

main.ts > app.module.ts > app.component.ts > Get selector info > replace selector in index.html

