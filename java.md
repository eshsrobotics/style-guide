Java
====

This style guide will be finished later. For now, just format your code using [Artistic Style](http://astyle.sourceforge.net/) with `astylerc` found in the [dotfiles](https://github.com/eshsrobotics/dotfiles) repository.

Quality Code
------------

Make your code beautiful and eloquent as possible. Before committing code, ask yourself if it could be written any better. Your code is everyone's code, so make it good!


Braces
------

Braces should always go on the next line.

    public void myMethod()
    {
        if(1 < 2)
        {
        }
        
        for(int i = 0; i < 100; i++)
        {
        }
    }

not

    public void myBadMethod() {
        if(1 < 2) {
        }
        
        for(int i = 0; i < 100; i++) {
        }
    }


Indentation
-----------

Always use four spaces for indentation. Do NOT use tabs or any other amount of space.

        public void myMethod()
        {
        }
