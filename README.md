fly -t ci sp -p vegeta -c pipeline.yml
fly -t ci up -p vegeta
fly -t ci tj -j vegeta/perf-test --watch