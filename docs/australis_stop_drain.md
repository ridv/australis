## australis stop drain

Stop maintenance on a host (move to NONE).

### Synopsis

Transition a list of hosts currently in a maintenance status out of it.

```
australis stop drain [space separated host list] [flags]
```

### Options

```
  -h, --help                help for drain
      --interval duration   Interval at which to poll scheduler. (default 5s)
      --timeout duration    Time after which the monitor will stop polling and throw an error. (default 1m0s)
```

### Options inherited from parent commands

```
  -a, --caCertsPath string      Path where CA certificates can be found.
  -c, --clientCert string       Client certificate to use to connect to Aurora.
  -k, --clientKey string        Client key to use to connect to Aurora.
      --config string           Config file to use. (default "/etc/aurora/australis.yml")
  -l, --logLevel string         Set logging level [panic fatal error warning info debug trace]. (default "info")
  -p, --password string         Password to use for API authentication
  -s, --scheduler_addr string   Aurora Scheduler's address.
  -i, --skipCertVerification    Skip CA certificate hostname verification.
      --toJSON                  Print output in JSON format.
  -u, --username string         Username to use for API authentication
  -z, --zookeeper string        Zookeeper node(s) where Aurora stores information. (comma separated list)
```

### SEE ALSO

* [australis stop](australis_stop.md)	 - Stop a service or maintenance on a host (DRAIN).

###### Auto generated by spf13/cobra on 21-Mar-2019