# 42-style block comments

## Features

``` c
int     main()
{
    return 0;
}
```
turns into:

``` c
/*
** int     main()
** {
**     return 0;
** }
*/
```

## Usage
Select the text that you want to transform, then call the command bar with:

`Ctrl+Shift+P`

And run the command:

`> 42-comment`

## Keybindings
You can bind these commands to a shortcut by adding something like this to your `keybindings.json`:
```
{ "key": "shift+cmd+*", "command": "extension.42-comment", "when": "editorTextFocus"}
```
or go to Preferences -> Keyboard Shortcuts, find 42-comment, add a shortcut

## Known Issues

Some known issues should be here.

## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial release of 42-comment
