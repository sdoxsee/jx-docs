---
date: 2019-01-14T09:35:13Z
title: "jx step post install"
slug: jx_step_post_install
url: /commands/jx_step_post_install/
---
## jx step post install

Runs any post install actions

### Synopsis

This pipeline step ensures that all the necessary jobs are imported and the webhooks set up - e.g. for the current Environments. 

It is designed to work with GitOps based development environments where the permanent Environments like Staging and Production are defined in a git repository. This step is used to ensure that all the 'Environment' resources have their associated CI+CD jobs setup in Jenkins or Prow with the necessary webhooks in place.

```
jx step post install [flags]
```

### Examples

```
  jx step post install
```

### Options

```
  -b, --batch-mode                   In batch mode the command never prompts for user input
      --env-job-credentials string   The Jenkins credentials used by the GitOps Job for this environment
      --headless                     Enable headless operation if using browser automation
  -h, --help                         help for install
      --install-dependencies         Should any required dependencies be installed automatically
      --log-level string             Logging level. Possible values - panic, fatal, error, warning, info, debug. (default "info")
      --no-brew                      Disables the use of brew on macOS to install or upgrade command line dependencies
      --pull-secrets string          The pull secrets the service account created should have (useful when deploying to your own private registry): provide multiple pull secrets by providing them in a singular block of quotes e.g. --pull-secrets "foo, bar, baz"
      --skip-auth-secrets-merge      Skips merging a local git auth yaml file with any pipeline secrets that are found
      --verbose                      Enable verbose logging
```

### SEE ALSO

* [jx step post](/commands/jx_step_post/)	 - post step actions

###### Auto generated by spf13/cobra on 14-Jan-2019