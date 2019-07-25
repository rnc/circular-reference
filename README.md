
# Maven Circular Reference Demonstration

Contains two projects; compile and deploy the parent first and then the second one. Use the following Command line:

```
    mvn -DaltDeploymentRepository=local::default::file://$HOME/tmp/deploy-mead clean deploy
```
