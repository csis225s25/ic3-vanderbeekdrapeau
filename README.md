# In Class Problem Set 3

I used ComboBoxDemo.java a few years ago.  It used to compile cleanly.  Even though the code has not changed, it now  will not compile without throwing warnings.

Doing everything from a command prompt or Git Bash (no IDEs allowed), your mission is to debug the code and find out why it stopped compiling cleanly.  When you have figured it out,  note what you changed and why it stopped working in the README.md file.

@author Max Vanderbeek, Greg Drapeau
**Changes to code**
Added <String> to the beggining of the contruction of the combobox object to fix it.

**What caused it to stop working?**
In a newer version of Java, they require you to define the type that you are going to use inside the combobox. All you need to do is cast the type so that the variable is checked before it gets inputted into the combobox.
