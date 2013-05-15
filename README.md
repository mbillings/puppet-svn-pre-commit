puppet-svn-pre-commit
=====================

Check puppet syntax before committing to an svn repo.

There are a lot of puppet syntax pre-commit hooks for svn, but none I could find that supported multiple installs of puppet (for older puppet versions that didn't have the built in "puppet parser validate").

This supports a gem-installed puppet, and includes the environment. Still having issues with properly parsing .erb (looks like it has to do with the ruby environment not being properly sourced?), so it only does .pp for now.

