---
title: Command - devspace list available-components
sidebar_label: available-components
id: version-v4.4.0-devspace_list_available-components
original_id: devspace_list_available-components
---


Lists all available components

## Synopsis


```
devspace list available-components [flags]
```

```
#######################################################
######### devspace list available-components ##########
#######################################################
Lists all the available components that can be used
in devspace
#######################################################
```
## Options

```
  -h, --help   help for available-components
```

### Options inherited from parent commands

```
      --config string         The devspace config file to use
      --debug                 Prints the stack trace if an error occurs
      --kube-context string   The kubernetes context to use
  -n, --namespace string      The kubernetes namespace to use
      --no-warn               If true does not show any warning when deploying into a different namespace or kube-context than before
  -p, --profile string        The devspace profile to use (if there is any)
      --silent                Run in silent mode and prevents any devspace log output except panics & fatals
  -s, --switch-context        Switches and uses the last kube context and namespace that was used to deploy the DevSpace project
      --var strings           Variables to override during execution (e.g. --var=MYVAR=MYVALUE)
```

## See Also

* [devspace list](../../cli/commands/devspace_list)	 - Lists configuration
