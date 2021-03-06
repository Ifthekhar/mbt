## mbt run-in

Main command for running user defined commands

### Synopsis


Main command for running user defined commands

Execute a user defined command according to the specified sub command.
See sub command help for more information.


### Options

```
  -m, --command string   Command to execute
  -h, --help             help for run-in
```

### Options inherited from parent commands

```
      --debug       Enable debugging
      --in string   Path to repo
```

### SEE ALSO
* [mbt](mbt.md)	 - Monorepo Build Tool
* [mbt run-in branch](mbt_run-in_branch.md)	 - Run command in all modules at the tip of the specified branch
* [mbt run-in commit](mbt_run-in_commit.md)	 - Run command in all modules in the specified commit
* [mbt run-in diff](mbt_run-in_diff.md)	 - Run command in modules changed between from and to commits
* [mbt run-in head](mbt_run-in_head.md)	 - Run command in all modules in the commit pointed at current head
* [mbt run-in local](mbt_run-in_local.md)	 - Run command in all modules in uncommitted changes in current workspace
* [mbt run-in pr](mbt_run-in_pr.md)	 - Run command in modules changed in dst branch relatively to src branch

###### Auto generated by spf13/cobra on 30-Apr-2018
