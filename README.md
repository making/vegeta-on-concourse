```
fly -t ci sp -p vegeta -c pipeline.yml -l credentials.yml
fly -t ci up -p vegeta
fly -t ci tj -j vegeta/perf-test --watch
```

![image](https://user-images.githubusercontent.com/106908/40160798-aed1430a-59e9-11e8-92a5-049c8bab200f.png)
