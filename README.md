TODO.TXT Extensions Meta Repository
===============================================================================

This is a repository collecting all of the [Todo.txt][] add ons that I make
regular usage including my [extended replace][] and [watch][] add ons.

Install
-------------------------------------------------------------------------------

Follow the [instructions][] for adding add ons to todo.xt, or to install the
combination of add ons you can simply type the following in the terminal from
the root of the repository:

`ln -s todo.actions.d $HOME/.todo.actions.d`

If you want to enable additional add ons, simply `cd` into the `todo.actions.d`
directory and then create a link to the appropriate add on in the repositories
directory, for example:

```
cd todo.actions.d
ln -s ../todo.repositories.d/todo.repositories.d/todo.txt-xp/xp
```

Adds the `xp` command to the available todo actions.

[Todo.txt]: http://todotxt.org/
[extended replace]: https://github.com/kynda/todo.txt-extended-replace
[watch]: https://github.com/kynda/todot.txt-watch
[instructions]: https://github.com/todotxt/todo.txt-cli/wiki/Todo.sh-Add-on-Directory#installation
