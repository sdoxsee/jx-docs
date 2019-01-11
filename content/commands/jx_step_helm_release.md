---
date: 2019-01-11T14:46:19Z
title: "jx step helm release"
slug: jx_step_helm_release
url: /commands/jx_step_helm_release/
---
## jx step helm release

Releases the helm chart in the current directory

### Synopsis

This pipeline step releases the Helm chart in the current directory

```
jx step helm release [flags]
```

### Examples

```
  jx step helm release
```

### Options

```
      --clone-https git@foo/bar.git   Clone the environment Git repo over https rather than ssh which uses git@foo/bar.git (default true)
  -d, --dir string                    The directory containing the helm chart to apply (default ".")
      --git-provider string           The Git provider for the environment Git repository (default "github.com")
  -h, --help                          help for release
```

### SEE ALSO

* [jx step helm](/commands/jx_step_helm/)	 - helm [command]

###### Auto generated by spf13/cobra on 11-Jan-2019