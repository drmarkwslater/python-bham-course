---
layout: page
title: Setup
permalink: /setup/
root: ..
---

### Obtain lesson materials

1. Download [python-novice-inflammation-data.zip][zipfile1]
        and [python-novice-inflammation-code.zip][zipfile2].
2. Create a folder called `swc-python` on your Desktop.
3. Move downloaded files into this newly created folder.
4. Unzip the files.

You should now see two new folders called `data` and `code` in your `swc-python` directory on your
Desktop.

### Running Python

Assuming you have installed Anaconda3, you should run the Anaconda Navigator (for macOS, this is installed in 
`/Users/<username>/anaconda3/bin` by default unless you've moved it to `Applications`) and then go to 
Environments -> base(root) 'Play' button -> 'Open Terminal'. This gives you a terminal (or command prompt in Windows) that will allow
you to run `python` and `ipython`:

<img src="../fig/shell-anaconda.png" alt="drawing" width="40%"/>

If you're using Windows and wish to have access to Python from a different command prompt, e.g. `git-bash`, you should
 enter the following commands:

```
export PATH="$PATH:/c/Users/$USERNAME/AppData/Local/Continuum/anaconda3/Scripts/:/c/Users/$USERNAME/AppData/Local/Continuum/anaconda3/"
```

### Navigate to the `swc-python` folder

Whether you are on macOS or Windows you should now be at a Shell prompt that is capable of running
Python. You should now navigate to your `swc-python` directory:

~~~
$ cd ~/Desktop/swc-python/data
~~~
{: .source}

### Start IPython interpreter

IPython is an alternative interpreter to the vanilla `python` interpreter. It provides an interactive command-line based interpreter with
various convenience features and commands.  You should have IPython on your system if you installed
[Anaconda Distribution](http://carpentries.github.io/workshop-template/#python).

To start using IPython from the prompt, execute:
~~~
$ ipython
~~~
{: .source}

[zipfile1]: {{ page.root }}/data/python-novice-inflammation-data.zip
[zipfile2]: {{ page.root }}/code/python-novice-inflammation-code.zip
