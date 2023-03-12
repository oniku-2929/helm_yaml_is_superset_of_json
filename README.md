# Usage
```
helm template . -f test.json  
helm install test . -f test.json  
or  
helm template . -f test.json -f values.yaml  
helm install test . -f test.json -f values.yaml  
or  
helm template . -f values.yaml -f test.json  
helm install test . -f values.yaml -f test.json  
```

# Requirements
Helm