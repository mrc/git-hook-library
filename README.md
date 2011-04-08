# git-hook-library
An exceptionally small collection of git hooks.

## pre-commit hooks

* `pre-commit.no-tabs`

  Reject commits which contain tabs (based on git config
  hooks.allowtabs)

  Designed as
  [an answer to a StackOverflow question](http://stackoverflow.com/questions/5574195/make-git-highlight-tab-characters-in-a-diff/5574413#5574413).

  Since git 1.7.2 you can use core.whitespace=tab-in-indent to detect
  tabs used for indentation (though not tabs embedded in the
  line). See
  [stackoverflow](http://stackoverflow.com/questions/5574195/make-git-highlight-tab-characters-in-a-diff/5578165#5578165).
