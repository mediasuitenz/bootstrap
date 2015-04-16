# Setting up sublime text editor

Add your favorite configuration and sublime tips here!
Save config files and snippets into your sublime package User folder (typically "/Users/you/Library/Application Support/Sublime Text 3/Packages/User")

## Useful Example Settings
(preferences > Settings - User)

```json
{
    "always_show_minimap_viewport": true,
    "binary_file_patterns":
    [
        "vendor/**", "node_modules/**", "bower_components/**", "*.min.*", "*.jpg", "*.jpeg", "*.png", "*.gif", "*.ttf", "*.tga", "*.dds", "*.ico", "*.eot", "*.pdf", "*.swf", "*.jar", "*.zip"
    ],
    "bold_folder_labels": true,
    "draw_white_space": "all",
    "enable_tab_scrolling": false,
    "ensure_newline_at_eof_on_save": true,
    "find_selected_text": true,
    "highlight_modified_tabs": true,
    "match_brackets_angle": true,
    "open_files_in_new_window": false,
    "shift_tab_unindent": true,
    "show_full_path": true,
    "trim_trailing_white_space_on_save": true
}
```

## Package Control
Install sublime package control so that:
shift + cmd + p > Package Control - Install Packages can be used to install
modules

## Sublime Text Modules
(install with sublime package control)

- Editorconfig      Shared project editor configuration management
- Sublime JSHint    JS Hint javascript linting
- Modific           Highlights git changes in the gutter
- Phpcs             PHP code sniffer (issue highlighting), [see here for configuration](https://github.com/mediasuitenz/php-code-standard)
- phpfmt            PHP auto-formatter, see sublime config example folder


- Puppet            Puppet syntax highlighting
- Doc​Blockr         Block comments for functions/methods
- Markdown Preview  Build html files to html
- Handlebars        Highlighting for handlebars files
- Dash Doc​          Dash doc lookup via cntl + h

## Commands

There are some useful key-bindings in the sublime-config-files folder in this repo

### Useful commands to remember

- shift+cmd+a           select all occurrences of current selected text (if the binding is setup)
- shift+cmd+space       expand selection to scope (word, brackets, etc)
- shift+cmd+l           split block selection into a cursor for each line
- cmd+l                 expand selection to line
- cmd+x                 cut entire current line
- ctrl+cmd+[up|down]    move current line(s) up/down
- hold alt when dragging for multiple cursors
- cmd+k, cmd+[u|l]      Upper/Lower casify current selection

## Snippets

- [PHP var_dump snippet](https://github.com/mediasuitenz/bootstrap/blob/master/sublime-config-files/php_var_dump.sublime-snippet)

## Language specific settings

If you want you can have context specific settings, such as when dealing with PHP the following will make double-clicking a word also select dollar signs i.e. select all of `$myVar` instead of just the `myVar` part:
```json
{
    "word_separators": "./\\()\"'-:,.;<>~!@#%^&*|+=[]{}`~?"
}
```
Save this file like `PHP.sublime-settings` in your `Packages/User` folder
