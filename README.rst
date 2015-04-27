******
README
******

sublim-user-confg
=================

Follow the instruction on this page:

    https://sublime.wbond.net/docs/syncing


Quick How To
============

Note: it is advised to fork this projec to save your own settings

* Clone in your ``Package/User`` directory::

  $ cd ~/.config/sublime-text-3/Packages/User
  $ git clone https://github.com/Stibbons/sublime-user-config.git

* Install Package Control. See:

    https://packagecontrol.io/installation

* Restart sublime.

* Sublime will automatically install new plugins.

* Sublime might look ugly. This is because the file preference refers to a theme that is not installed yet. Just let Sublime install missing themes and plugins automatically.

* Several crashes or hangs might occurs. Just keep on restarting sublime when frozen.

* settings files might be rewritten. Execute git reset to reset to the latest version commited
  and restart sublime. It will retry again and again to install all missing plugins.

    git reset --hard HEAD

* do this until sublime works!


Advice: Commit your change in the settings like you would when developing a software. It will
be very useful in case of plugin crash, freeze, etc. Settings are software too!!!
