# load-test-demo
# K6 for load testing
 
## Installations:
- k6 (https://grafana.com/docs/k6/latest/set-up/install-k6/
 
https://dl.k6.io/msi/k6-latest-amd64.msi) - for windows installation.
 - Go package manager (https://go.dev/doc/install)
 - k6 Dashboard (https://github.com/grafana/xk6-dashboard/blob/master/cmd/k6-web-dashboard/README.md)
 - go install github.com/grafana/xk6-dashboard/cmd/k6-web-dashboard@latest

## Commands
```k6 new``` 

```k6 run script.js```

```k6 run --vus 10 --duration 30s script.js```

## Resources:
- https://grafana.com/docs/k6/latest/get-started/running-k6/
- https://test.k6.io/ 

## Run performance test with K6 including live report dashboard
- To Run performance test with k6 including report dashboard

  ```k6 run --out web-dashboard=record=test_result.ndjson script2.js```
- Live Report while executing load/performance test:
http://127.0.0.1:5665/ui/?endpoint=/
 