GANGLIA-ACTIVEMQ
================

 * Github: https://github.com/jbuchbinder/ganglia-activemq
 * Twitter: https://twitter.com/jbuchbinder

Allows ActiveMQ monitoring stats to be pulled into Ganglia.

BUILDING
--------

```
go get github.com/jbuchbinder/go-gmetric/gmetric
go install github.com/jbuchbinder/go-gmetric/gmetric
go build
```

USAGE
-----

```
Usage of ganglia-activemq:
  -activeMqHost="localhost": ActiveMQ host
  -activeMqPort=8161: ActiveMQ port
  -gangliaGroup="activemq": Ganglia group name
  -gangliaHost="localhost": Ganglia host name/IP
  -gangliaInterval=300: Ganglia polling interval/metric TTL
  -gangliaPort=8469: Ganglia port
  -gangliaSpoof="": Ganglia spoof string (IP:host)
  -ignoreQueues="": Substring to ignore in queue names
  -verbose=false: Verbose
```

