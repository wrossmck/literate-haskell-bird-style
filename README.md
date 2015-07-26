#Literate Haskell Bird Style
This .tmLanguage has been made mostly from David's answer on [this question in Stack Overflow](http://stackoverflow.com/a/14991061/2046648). Including a bit of digging about in sublime's folders.

This has now been merged with [SublimeHaskell](https://github.com/SublimeHaskell/SublimeHaskell) and should be installed via PackageManager in Sublime.


##Installation

1. Download the [`.tmLanguage`](https://bitbucket.org/wrossmck/literate-haskell-bird-style/downloads/Literate%20Haskell%20Bird%20Style.tmLanguage) file.
2. Move the `.tmLanguage` file from your Downloads location to `~/Library/Application Support/Sublime Text 2/Packages/Haskell/` or `~/Library/Application Support/Sublime Text 3/Packages/Haskell/` depending on your version of sublime

### Alternate Installation for Sublime Text 3

1. Download this [`modified .sublime-package`](https://bitbucket.org/wrossmck/literate-haskell-bird-style/downloads/Haskell.sublime-package)
2. Move it to `/Applications/Sublime Text.app/Contents/MacOS/Packages/` and replace the existing haskell.sublime-package

Sublime should load it up automatically _(no restart necessary)_, and it will be available as a syntax from the `View->Syntax->Haskell` menu or listed as `Literate Haskell Bird Style` in the menu. 

### Installation via [Package Control](http://wbond.net/sublime_packages/package_control/installation)

1. Get Sublime Text: http://www.sublimetext.com/
2. Install the Sublime Package Control package: http://wbond.net/sublime_packages/package_control/installation
3. Use Package Control to install the parent package, which includes this syntax (SublimeHaskell)

That's it! Happy coding!
