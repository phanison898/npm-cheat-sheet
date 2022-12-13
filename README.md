![node](https://www.vectorlogo.zone/logos/nodejs/nodejs-ar21.svg)

### Usefull npm commands

#### 1. Install _package.json_ dependencies

```nodejs
npm install
```

#### 2. Installing node modules

```nodejs
# install
npm i <name-of-the-package>
or
npm install <name-of-the-package>

# uninstall
npm un <name-of-the-package>
or
npm uninstall <name-of-the-package>

# update
npm up <name-of-the-package>
or
npm update <name-of-the-package>
```

#### 3. Flags

```nodejs

-S is the same as --save
-D is the same as --save-dev
```

#### 4. List globally installed packages

```
npm list -g --depth=0
```

#### 5. Uninstall global package

```
npm -g uninstall <name>

```

#### 6. Update global packages

To see which packages need updating, use:

```
npm outdated -g --depth=0

```

#### 7. To update global packages individually you can use:

```
npm update -g <package> <package> <package>
```

#### 8. list available scripts to run

```
npm run
```

#### 9. Update npm

```
npm install -g npm@latest
```

#### 10. Installed version

```
npm list # for local packages
```

#### 11. Install another node version and use it instead default version

```nodejs
npm install 12
```

If you have multiple versions of Node.js installed on your workspace, you can switch to a specific version by writing:

```nodejs
nvm use 10.19.0
```

#### 12. Make a Node version default

In order to set a default version of Node for your workspace, just type:

```nodejs
nvm alias default 12
```

#### 13. Update npm

If you use Node installed through nvm, it's good practice to update your version of npm with this command:

```nodejs
nvm install-latest-npm
```
