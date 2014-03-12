Sublime Text 3 Primer
=====================

.. image:: http://upload.wikimedia.org/wikipedia/en/4/4c/Sublime_Text_Logo.png
    :width: 200

About Sublime Text 3
--------------------

`Sublime Text 3`_ is chosen as the standard code editor due to its
simplicity and ease of use.

.. _Sublime Text 3: http://sublimetext.com

This document contains guidelines and recommendations in using Sublime
Text 3 for development.


User Preferences
----------------

In order to maintain consistency with our Sublime Text 3 settings, the
following settings are recommended.

*These settings can be set by going to Preferences -> Settings -
User.*

.. code:: javascript

    {
        "auto_find_in_selection": true,
        "bold_folder_labels": true,
        "close_windows_when_empty": true,
        "color_scheme": "Packages/User/base16-eighties.dark (SL).tmTheme",
        "draw_white_space": "all",
        "ensure_newline_at_eof_on_save": true,
        "fade_fold_buttons": false,
        "font_face": "Source Code Pro",
        "font_size": 10,
        "highlight_line": true,
        "highlight_modified_tabs": true,
        "ignored_packages": [
            "Vintage"
        ],
        "indent_guide_options": [
            "draw_normal",
            "draw_active"
        ],
        "open_files_in_new_window": true,
        "preview_on_click": false,
        "rulers": [
            72,
            79,
            120
        ],
        "tab_size": 4,
        "theme": "Spacegray Eighties.sublime-theme",
        "translate_tabs_to_spaces": true,
        "trim_trailing_white_space_on_save": true,
        "wide_caret": true,
        "word_wrap": true,
        "wrap_width": 80
    }

Many of the above settings are subjective and can be changed according
to the personal preference of the developer. However, as an absolute
must, the following are mandatory:

.. code:: javascript

    "ensure_newline_at_eof_on_save": true

Many of coding standards that we follow require this so it is better
that we set *Sublime Text* to do it for us automatically.

.. code:: javascript

    "tab_size": 4,
    "translate_tabs_to_spaces": true,
    "trim_trailing_white_space_on_save": true

This will ensure consistency in our code and avoid complicating our
``git`` diffs. We use ``four spaces`` for indentation as a default
except in HTML markup where we set it at ``two spaces`` only.

Recommmended Packages
---------------------

Make sure *Package Control* is installed first. This will make the
installation of the other packages a lot easier.

-  `Package Control`_ - To install, please refer to the `following
   instructions`_.

.. _Package Control: https://sublime.wbond.net/docs/usage
.. _following instructions: https://sublime.wbond.net/installation

Once *Package Control* has already been installed, the procedure for
installing the rest of the packages is a lot simpler.

1. Press ``Ctrl+Shift+P``.
2. Choose (or type) ``Package Control: Install Package``.
3. Choose the package that you want to install.

Use the procedure above to install the following packages:

-  `Emmet`_
-  `Git`_
-  `GitGutter`_
-  `SideBarEnhancements`_
-  `SublimeLinter`_
-  `SublimeLinter-gjslint`_
-  `SublimeLinter-pep8`_
-  `Djaneiro`_

.. _Emmet: https://sublime.wbond.net/packages/Emmet
.. _Git: https://sublime.wbond.net/packages/Git
.. _GitGutter: https://sublime.wbond.net/packages/GitGutter
.. _SideBarEnhancements: https://sublime.wbond.net/packages/SideBarEnhancements
.. _SublimeLinter: https://sublime.wbond.net/packages/SublimeLinter
.. _SublimeLinter-gjslint: https://sublime.wbond.net/packages/SublimeLinter-gjslint
.. _SublimeLinter-pep8: https://sublime.wbond.net/packages/SublimeLinter-pep8
.. _Djaneiro: https://sublime.wbond.net/packages/Djaneiro


Aesthetic Recommendations
-------------------------

*TODO: Make these into hyperlinks. Give instructions in installing
these.*

-  Theme: `Spacegray Eighties`_
-  Color Scheme: `Spacegray Eighties`_
-  Font: `Adobe Source Code Pro`_

.. _Spacegray Eighties: https://sublime.wbond.net/packages/Theme%20-%20Spacegray
.. _Adobe Source Code Pro: https://sourceforge.net/projects/sourcecodepro.adobe/files/
