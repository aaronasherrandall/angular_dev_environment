# angular_dev_environment
Setting Up Your Machine For Angular Development
From: https://angularfirebase.com/lessons/basics-angular-cli/

**Step 1**

Open a browser type https://nodejs.org/en/  download, and install node js based on your window bit.

**Step 2**

After installing node js, open command prompt type ```node –v``` to check installed version of node js.

Type ```npm –v``` to check npm version. If both the commands show their respective versions it means node is installed successfully.

**Step 3**

Open browser type https://cli.angular.io/  check command to install Angular CLI.

**Step 4**

Open command prompt, type ```npm install –g @angular/cli```. It will install CLI globally where g represents globally. 
To check Angular CLI installed type ```ng version```

**Step 5**

Open command prompt type ```npm install –g typescript```, it will install TypeScript in your system. 
Now type ```tsc –version``` in command prompt to check the version of typescript installed.

**Step 6**

Open browser, type https://code.visualstudio.com/ download, and install visual code editor.

**Step 7**

Create the first application, click on view, select Terminal and click on it. It will open visual code console.

**Step 8**

In visual code console type ng new [Project Name]. It will take a few seconds and create a brand new project with required files.

**Step 9**

After creation of the project, type the following command in visual code console.

```cd [App Name / File Path]```
```ng serve```

**Step 10**

After successfully compiling project, open browser type http://localhost:4200/ hit enter

## Inside the Project

**Angular.json**

The CLI (Angular Command Line Interface) configuration options can be found in the angular.json file in the root of the project. It is possible to have multiple apps and libraries in a single CLI workspace. If necessary, you can edit values in this file to change the behavior of the CLI, but that’s usually only required for more advanced use cases.

**Generate**

The generate command is the most powerful feature of the CLI and you will use it to quickly scaffold boilerplate code. In addition, it will update your NgModule with the TypeScript import and declaration.

```ng generate component cool```

Make sure a new terminal is open and the commands are being run in the root folder.

```
CREATE src/app/cool/cool.component.html (19 bytes)
CREATE src/app/cool/cool.component.spec.ts (614 bytes)
CREATE src/app/cool/cool.component.ts (261 bytes)
CREATE src/app/cool/cool.component.css (0 bytes)
UPDATE src/app/app.module.ts (467 bytes)
```
This creates 4 different files and updates our existing app module.

**Generate a Component for a Feature Module**

As an Angular Developer, we should compartmentalize code into ng modules.
By default, the CLI will import a component that's generated into the root app module.
What if we are trying to import a component for a feature module?




