---
date: 2019-01-11T14:46:19Z
title: "jx get teams"
slug: jx_get_teams
url: /commands/jx_get_teams/
---
## jx get teams

Display the Team or Teams the current user is a member of

### Synopsis

Display the Team or Teams a user is a member of.

```
jx get teams [flags]
```

### Examples

```
  # List the provisioned team or teams the current user is a member of
  jx get team
  
  # List the pending Teams which are not yet provisioned and available for use
  jx get team -p
```

### Options

```
  -h, --help            help for teams
  -o, --output string   The output format such as 'yaml'
  -p, --pending         Display only pending Teams which are not yet provisioned yet
```

### SEE ALSO

* [jx get](/commands/jx_get/)	 - Display one or more resources

###### Auto generated by spf13/cobra on 11-Jan-2019