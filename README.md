dfst-git-commit-hooks
=====================

DITA for Small Teams-specific commit hook scripts for use with git to support

To use the hooks:

1. Copy or symlink the common/ directory into the .git/hooks directory in your repository
2. Copy or symlink the files in the client-side/ directory into the .git/hooks directory.

After this your .git/hooks directory should look like this:

~~~~
applypatch-msg.sample
commit-msg.sample
common/
post-checkout
post-commit
post-merge
post-update.sample
pre-applypatch.sample
pre-commit.sample
pre-push.sample
pre-rebase.sample
prepare-commit-msg.sample
update.sample
~~~

The hooks rely on the basexclient command, so you must have at least that command in your PATH.