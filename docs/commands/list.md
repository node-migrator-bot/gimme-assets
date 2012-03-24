gimme-list(1) -- List installed packages
========================================

    gimme list

This command will print to stdout all the packages that are available
with standard name + description, as well as allowing you to specify
which package property should be displayed.

It can take a a list of terms, in which case the list is filtered based
on these.

The `--limit` options let you switch to paginated list based on this
option.

When run as `ll` or `la`, it shows extended information by default.

## CONFIGURATION

### props

* Default: false
* Type: Array

Show extended information based on package properties. When turn to
true, then it shows  every package properties.

### limit

* Default: 0
* Type: Number

When set to other than `0`, switch the list to paginated list based on
`limit` value. [N]ext, [P]revious or [Q]uit key may be entered paginate
next, back or quit the program.
