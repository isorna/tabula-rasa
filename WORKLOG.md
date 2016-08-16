# Work Log

# 16/08/2016

Fixed login bugs, and moved private firebase data connection information to the `/data/app-dataconfig.js` file, it won't be committed.

Added a [TO DO](TODO.md) file.

Login dialog completed.

## 12/08/2016

Some components were renamed, and the content architecture has been decided.

Added some icons from the [iron-icons component](https://elements.polymer-project.org/elements/iron-icons?view=demo:demo/index.html&active=iron-icons) to the app-icons component.

## 11/08/2016

Added Google login Auth.

App views are now reorganized, and they've been identified with icons.

## 09/08/2016

Set up project from [Polymer Project](h ttps://www.polymer-project.org/1.0/start/toolbox/set-up) page:

```
npm install -g polymer-cli

mkdir my-app
cd my-app

polymer init app-drawer-template

```

Added [polymerfire](bower install --save firebase/polymerfire) component.
Read polymerfire [documentation here](https://elements.polymer-project.org/elements/polymerfire).

How to [setup a firebase project](https://firebase.google.com/docs/web/setup).

Take a look at [firebase web samples](https://firebase.google.com/docs/samples/#web).

Remember to change data rules on the firebase console, or you won't be able to read your data!.
