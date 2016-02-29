Pomodoro-Tracker localization files
===================================

The project contains translations for https://pomodoro-tracker.com

I actually know only Russian and English (little bit) so I need your help with
other languages.

-----

Current status (languages are supported):

* [English](https://github.com/klen/pomodoro-tracker-locales/tree/master/ru/LC_MESSAGES) (fully translated)
* [Russian](https://github.com/klen/pomodoro-tracker-locales/tree/master/ru/LC_MESSAGES) (fully translated)
* [German](https://github.com/klen/pomodoro-tracker-locales/tree/master/de/LC_MESSAGES) (not started)
* [French](https://github.com/klen/pomodoro-tracker-locales/tree/master/fr/LC_MESSAGES) (not started)
* [Italian](https://github.com/klen/pomodoro-tracker-locales/tree/master/it/LC_MESSAGES) (not started)

If you want to add a new language to Pomodoro-tracker please [open an
issue](https://github.com/klen/pomodoro-tracker-locales/issues/new). 


How to translate
----------------

Open your language files use links above and edit `message.po`, `static.po` files.

By example (russian):

    # Before editing
    #: templates/base.j2:91
    msgid "Sign Up / Login"
    msgstr ""


    # After editing
    #: templates/base.j2:91
    msgid "Sign Up / Login"
    msgstr "Зарегистрироваться / Войти"

Save your work.
