Windows system PATH editor
==========================

Simple "editor" for the Windows PATH environment variable. Converts semi-colons to newlines and vice-versa.

As a software developer you can frequently install (and uninstall) all kinds of software tools that are usually run from the command-line, so they need to be added to the PATH environment variable.
But Windows offers by default no helper dialog to make it easy to edit the PATH, except for the "one\single\line\editing;of\the\extremely\long;path\environment\variable".

So if you are annoyed of having to scroll through this one single long line in order to add a new directory to the path, or simply to see what directories are already in the path, then it might help you to be able to quickly split the PATH into multiple lines (one directory per line), edit it as you wish, and then join it back into one long line.  
For this I have written this extremely short html+js helper page, where you can paste your PATH in the top textarea and it will be automatically split into multiple lines in the bottom textarea. (or vice-versa!)

To use it, follow these simple steps:

1. Follow the usual steps to get the value of the PATH environment variable (for example: press Windows+Pause/Break -> Advanced -> Environment variables)
2. Copy the value of the PATH environment variable and paste it in this webpage, in the top textarea
3. In the bottom textarea you will automatically have your PATH split into multiple lines, and you can edit it as you like
4. While editing, any changes that you make to either of the two textareas will be automatically reflected in the other textarea
5. When you are finished editing, copy again the value from the top textarea and paste it in the Windows->Advanced->Environment variables->PATH

That's it !

I hope you enjoy this simple tool.
