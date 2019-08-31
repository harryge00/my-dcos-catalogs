# Deploy a master-slave redis cluster
```
curl -XPOST master.mesos:8080/v2/groups -d @redis-group.json
```

Write to the master while reading from slaves.