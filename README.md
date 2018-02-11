# sublime-inform6-syntax
Basic Sublime Text 3 syntax highlighting file for the Inform 6 language

## Requirements

Sublime Text 3 or later. Note that this file's content would probably work with a ".tmLanguage" file for Sublime Text 2 and earlier, but I haven't verified this.

Inform 6 source files. Note that this syntax file will not work with Inform 7, as the grammar has changed significantly. My personal preference is Inform 6, so I wrote this to support my development work.

## Install

To install, copy the inform6.sublime-syntax file to your Sublime 3 user packages directory. On Mac OS X, the location should be something like:

```
/Users/<USERNAME>/Library/Application Support/Sublime Text 3/Packages/User
```

Restart Sublime Text.

## Use

"Inform6" should be available as a syntax option under View -> Syntax. Also, this syntax should be used by default when opening ".inf" files (unless you have another syntax plugin that already gets applied to .inf files).

## Development Notes

This syntax file is far from complete. I just hacked this together in an hour or so to highlight the most common things I run into when editing Inform 6 source files. The regex for matching a function name is particularly hacky.

Feel free to contribute or suggest additional syntax contexts.

## Other Resources

[Inform 6 Designer's Manual](http://inform-fiction.org/manual/html/contents.html)

[Sublime Text Syntax Definitions](http://www.sublimetext.com/docs/3/syntax.html)

[Textmate scope naming conventions, used in syntax definitions](http://manual.macromates.com/en/language_grammars#naming_conventions.html)
