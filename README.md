ruby-syntax-checker
===================

simple script to check for ruby syntax errors in a couple of ways, including a git pre-commit hook.

Use hook by symlinking or copying "pre-commit" file to .git/hooks/

*Never commit syntax errors, like from wrongly fixed merge conflicts, again!*

Usage when not via the commit hook:
-----------------------------------

    $ ./check_syntax.sh --help

	    supported parameters
	     -c : to only check files with unstaged changes
	     -s : to only check staged files
       else check all files (in parallel for speed!)
