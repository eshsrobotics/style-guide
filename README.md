style-guide
===========

Official programming style guide of the ESHS Robotics team.


Artistic Style
--------------

For the love of all that is holy, use [Artistic Style](http://astyle.sourceforge.net/) to format your C-based code before committing. It'll make everyone's lives a thousand times easier. Use the `astylerc` in the [dotfiles](https://github.com/eshsrobotics/dotfiles) repository to configure Artistic Style. Just renamed the file to `.astylerc` and stick it into your home directory.

Running `astyle -R "*.extension"` will generally be enough to format your code before committing. If you want to be really neat, you could add a pre-commit to do it for you.
