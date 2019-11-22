# 42-comment README

This is the README for your extension "42-comment". After writing up a brief description, we recommend including the following sections.

## Examples:

#### Converting a multiple line comment
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

### Keybindings
You can bind these commands to a shortcut by adding something like this to your `keybindings.json`:
```
{ "key": "shift+alt+c", "command": "extension.42-comment", "when": "editorTextFocus"}
```