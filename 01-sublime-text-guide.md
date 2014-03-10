# Sublime Text 3 Primer

[Sublime Text 3](http://sublimetext.com) is chosen as the standard code editor due to its simplicity and ease of use.

This document contains guidelines and recommendations in using Sublime Text 3 for development.

## User Preferences

In order to maintain consistency with our Sublime Text 3 settings, the following settings are recommended.

*These settings can be set by going to **Preferences** -> **Settings - User**.*

```javascript
{
    "close_windows_when_empty": true,
    "color_scheme": "Packages/User/base16-eighties.dark (SL).tmTheme",
    "draw_white_space": "selection",
    "detect_indentation": false,
    "ensure_newline_at_eof_on_save": true,
    "fade_fold_buttons": false,
    "font_face": "Source Code Pro",
    "font_size": 10,
    "highlight_line": true,
    "highlight_modified_tabs": true,
    "ignored_packages":
    [
        "Vintage"
    ],
    "indent_guide_options":
    [
        "draw_normal",
        "draw_active"
    ],
    "open_files_in_new_window": false,
    "preview_on_click": false,
    "rulers":
    [
        72,
        79,
        120
    ],
    "show_full_path": true,
    "tab_size": 4,
    "theme": "Spacegray Eighties.sublime-theme",
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true,
    "wide_caret": true,
    "wrap_width": 80
}
```

Many of the above settings are subjective and can be changed according to the personal preference of the developer. However, as an absolute must, the following are mandatory:

```javascript
"ensure_newline_at_eof_on_save": true
```

Many of coding standards that we follow require this so it is better that we set *Sublime Text* to do it for us automatically.

```javascript
"tab_size": 4,
"translate_tabs_to_spaces": true,
"trim_trailing_white_space_on_save": true
```

This will ensure consistency in our code and avoid complicating our `git` diffs. We use `four spaces` for indentation as a default except in HTML markup where we set it at `two spaces` only.

## Recommmended Packages

*TODO: Make these into hyperlinks. Give instructions in installing these.*

1. Package Control
2. Emmet
3. Git
4. GitGutter
5. SideBarEnchanceMents
6. SublimeLinter
7. SublimeLinter-gjslint
8. SublimeLinter-pep8
9. Djaneiro

## Aesthetic Recommendations

*TODO: Make these into hyperlinks. Give instructions in installing these.*

* Theme: *Spacegray Eighties*
* Color Scheme: *Spacegray Eighties*
* Font: *Adobe Source Code Pro*
