## mbt build commit

Build all modules in the specified commit

### Synopsis


Build all modules in the specified commit

	If --content flag is specified, this command will build just the modules
	impacted by the specified commit.
	

```
mbt build commit <sha> [flags]
```

### Options

```
  -c, --content       Build the modules impacted by the content of the commit
  -f, --fuzzy         Use fuzzy match when filtering
  -h, --help          help for commit
  -n, --name string   Build modules with a name that matches this value. Multiple names can be specified as a comma separated string.
```

### Options inherited from parent commands

```
      --debug       Enable debugging
      --in string   Path to repo
```

### SEE ALSO
* [mbt build](mbt_build.md)	 - Main command for building the repository

###### Auto generated by spf13/cobra on 30-Apr-2018
