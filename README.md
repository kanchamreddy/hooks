Precomit Hooks
=====
Hooks are a great way to enforce code quality standards and other checks or enforce rules well before someone commits the code.

For more details check  http://git-scm.com/book/en/Customizing-Git-Git-Hooks

This is a simple shell script to run Findbugs,  jshint  before you commit your code. 
The good thing with this is it runs jshint and findbugs on run on only the files you are committing 
