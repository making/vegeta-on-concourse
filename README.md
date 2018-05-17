```
fly -t ci sp -p vegeta -c pipeline.yml -l credentials.yml
fly -t ci up -p vegeta
fly -t ci tj -j vegeta/perf-test --watch
```

![image](https://user-images.githubusercontent.com/106908/40155800-947859c6-59d0-11e8-9ce6-e8fb67620386.png)
