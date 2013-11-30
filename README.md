selenium_grid_setup_example
===========================

The setup we are using for our Selenium Grid talks

These are just 2 example config.json for hub and node just use the latest selenium standalone server 


## Hub Config
```
  java -jar selenium-server-standalone-2.34.0.jar -role hub -hubConfig hubConfig.json -DPOOL_MAX=512
```

## Node Config

```
  java -jar selenium-server-standalone-2.34.0.jar -role webdriver -nodeConfig nodeConfig.json 
```
