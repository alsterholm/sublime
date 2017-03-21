<p align="center"><img src="https://github.com/andreasindal/sublime/blob/master/sublime.png?raw=true"></p>
<p align="center"><h4>Personal Sublime Text 3 settings</h4></p>

***

## Preferences
```json
{
    "animation_enabled": false,
    "bold_folder_labels": false,
    "caret_extra_bottom": 14,
    "caret_extra_top": 14,
    "caret_extra_width": 2,
    "caret_style": "solid",
    "color_scheme": "Packages/User/SublimeLinter/InspiredGitHub (SL).tmTheme",
    "drag_text": false,
    "draw_indent_guides": false,
    "file_exclude_patterns":
    [
        "*.lock",
        ".DS_Store"
    ],
    "find_selected_text": true,
    "folder_exclude_patterns":
    [
        ".idea",
        ".svn",
        ".git",
        ".hg",
        "CVS",
        ".phpintel"
    ],
    "font_face": "OperatorMono-Book",
    "font_options":
    [
        "gray_antialias",
        "subpixel_antialias",
        "no_round"
    ],
    "font_size": 15,
    "gutter": true,
    "highlight_line": true,
    "hot_exit": false,
    "ignored_packages":
    [
    ],
    "line_numbers": false,
    "line_padding_bottom": 4,
    "line_padding_top": 4,
    "margin": 0,
    "material_theme_tree_headings": true,
    "overlay_scroll_bars": "enabled",
    "phpunit-sublime-terminal": "iTerm",
    "remember_full_screen": true,
    "scroll_past_end": true,
    "shift_tab_unindent": true,
    "tab_size": 4,
    "theme": "Soda Light.sublime-theme",
    "translate_tabs_to_spaces": true,
    "tree_animation_enabled": false,
    "use_simple_full_screen": true
}
```

## Keybindings

```json
[
  { "keys": ["super+i"], "command": "find_use" },
  { "keys": ["option+d"], "command": "goto_definition_scope" },
  { "keys": ["option+i"], "command": "expand_fqcn", "args": {"leading_separator": true} },
  { "keys": ["super+shift+a"], "command": "find_all_under" },
  { "keys": ["super+shift+,"], "command": "run_macro_file", "args": {"file": "Packages/User/SemiColon.sublime-macro"} },
  { "keys": ["option+shift+,"], "command": "run_macro_file", "args": {"file": "Packages/User/Comma.sublime-macro"} },
  { "keys": ["super+shift+9"], "command": "run_macro_file", "args": {"file": "Packages/User/LeftParens.sublime-macro"} },
  { "keys": ["shift+super+x"], "command": "deselect" },
  { "keys": ["shift+super+n"], "command": "deselect" },
  { "keys": ["option+1"], "command": "toggle_side_bar" },
  { "keys": ["ctrl+c"], "command": "insert_php_constructor_property" },
  { "keys": ["super+shift+l"], "command": "move_to", "args": { "to": "eol" } },
  { "keys": ["super+shift+h"], "command": "move_to", "args": { "to": "bol" } },
  { "keys": ["super+shift+j"], "command": "move_to", "args": { "to": "eof" } },
  { "keys": ["super+shift+k"], "command": "move_to", "args": { "to": "bof" } },
  { "keys": ["option+t"], "command": "run_phpunit_test" },
  { "keys": ["option+a"], "command": "run_all_phpunit_tests" },
  { "keys": ["option+s"], "command": "run_single_phpunit_test" },
  { "keys": ["super+l"], "command": "reveal_in_side_bar" },
  { "keys": ["shift+option+k"], "command": "select_lines", "args": {"forward": false} },
  { "keys": ["shift+option+j"], "command": "select_lines", "args": {"forward": true} },
]
```