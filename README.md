terminal-colors
===============

NPM doesn't have any library that support light colors. So I just made this `terminal-colors` for that reason. 
Please checkout http://en.wikipedia.org/wiki/ANSI_escape_code for more info about terminal colors.

# Install
```
npm install terminal-colors
```
## colors and styles!

- bold
- italic
- underline
- yellow
- lightYellow
- cyan
- lightCyan
- white
- lightWhite
- magenta
- lightMagenta
- green
- lightGreen
- red
- lightRed
- grey
- lightGrey
- blue
- lightBlue

# Usage

```
require('terminal-colors');


console.log('hello'.green); // outputs green text
console.log('i like cake and pies'.underline.red) // outputs red underlined text
console.log('hello world'.lightGreen) // outputs light green
```
