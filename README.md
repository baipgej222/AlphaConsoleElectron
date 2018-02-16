# AlphaConsoleElectron

## Run the app

Running a simple dev version of the app. Navigate to the root of the project using a terminal (GitBash).

```
npm run test
```

## Build an .exe 

To build the current dev version in /source use

```
npm run package-win
```

You will find a built version of the code inside /build/dev/AlphaConsole-win32-ia32

## Compile Styles

If you make any changes to the styles you will need to run 

```
grunt sass
```

This will auto build all the style files, make sure the gruntfile is pointing to the correct files you want to compile & if you have any issues make sure you have Ruby installed on your PC.

To install sass on your computer globally then follow the steps [here](https://sass-lang.com/install) 

---

> [alphaconsole.net](http://www.alphaconsole.net/) &nbsp;&middot;&nbsp;
> Twitter [@alphaconsole](https://twitter.com/alphaconsole)