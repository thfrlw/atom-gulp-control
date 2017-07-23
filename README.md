### 5.0.1

Implemented PR's:
- fixes error with node path by switching to atom's BufferedNodeProcess by [acburdine](https://github.com/acburdine)
- fixed some styles things by [acburdine](https://github.com/acburdine)
- Issue #45: Tiny fix for pane selection by [wandrewkeech](https://github.com/wandrewkeech)

My changes:
- removed menus
- removed start command
- tasks tiles horizontally
- pane is plist vertically

# Atom gulp-control

## What

Displays a list of gulp tasks and allows execution within Atom.

Tasks can be re-started, tracked and controlled from a central point. Open the control from the package menu and you are good to go.

![Gulp](https://raw.githubusercontent.com/jacogr/atom-gulp-control/master/screenshots/gulp-01.png)

## Why

Reasons why this might work for you

- Allows the ability to execute any gulp tasks directly within Atom
- Allows a single overview of all tasks available to you
- Gulpfile.[coffee|js] is automatically located, either withing the root project folder or a sub-folder

## Configuration

Because Gulp requires the node executable, there is a potential for it to break if you use [nvm](https://github.com/creationix/nvm) or [nodebrew](https://github.com/hokaccha/nodebrew). If it doesn't initally work, you can specify node's bin folder in the package settings.

*NOTE: if you type* `which node` *into the console you can get node's system path, but you need to remove "node" from the end of it for it to work.*

## Where

The Atom package can be found on the Atom registry, [https://atom.io/packages/gulp-control](https://atom.io/packages/gulp-control).

Pull requests, issues, feature requests are all welcome and encouraged via [https://github.com/jacogr/atom-gulp-control](https://github.com/jacogr/atom-gulp-control).
