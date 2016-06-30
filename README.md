# mocha_cheat_sheet

1. list of optional parameters (options) that the $ mocha [options] command takes:

* -h or --help: print help information for the Mocha command
* -V or --version: print the version number that’s being used
* -r or --require <name>: require a module with the name provided
* -R or --reporter <name>: use a reporter with the name provided
* -u or --ui <name>: use the stipulated reporting user interface (such as bdd, tdd)
* -g or --grep <pattern>: run tests exclusively with a matching pattern
* -i or --invert: invert the --grep match pattern
* -t or --timeout <ms>: set the test case time out in milliseconds (for example, 5000)
* -s or --slow <ms>: set the test threshold in milliseconds (for example, 100)
* -w or --watch: watch test files for changes while hanging on the terminal
* -c or --colors: enable colors
* -C or --no-colors: disable colors
* -G or --growl: enable Mac OS X Growl notifications
* -d or --debug: enable the Node.js debugger— $ node --debug
* --debug-brk: enable the Node.js debugger breaking on the first line— $ node --debug-brk
* -b or --bail: exit after the first test failure
* -A or --async-only: set all tests in asynchronous mode
* --recursive: use tests in subfolders
* --globals <names>: provide comma-delimited global names
* --check-leaks: check for leaks in global variables
* --interfaces: print available interfaces
* --reporters: print available reporters
* --compilers <ext>:<module>,...: provide compiler to use
