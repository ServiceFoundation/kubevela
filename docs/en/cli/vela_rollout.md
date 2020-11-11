## vela rollout

Attach rollout trait to an app

### Synopsis

Attach rollout trait to an app

```
vela rollout <appname> [args]
```

### Examples

```
vela rollout frontend
```

### Options

```
      --detach            detach trait from service
  -h, --help              help for rollout
      --interval string    (default "30s")
      --replica int       total replica of the workload (default 5)
  -s, --staging           only save changes locally without real update application
      --step-weight int   weight percent of every step in rolling update (default 20)
      --svc string        specify one service belonging to the application
```

### Options inherited from parent commands

```
  -e, --env string   specify environment name for application
```

### SEE ALSO

* [vela](vela.md)	 - 

###### Auto generated by spf13/cobra on 10-Nov-2020