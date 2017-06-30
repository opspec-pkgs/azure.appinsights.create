# problem statement
creates an azure application insights instance (if it doesn't already exist)

# example usage

> note: in examples, VERSION represents a version of the azure.application.insights.create pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/azure.application.insights.create#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/azure.application.insights.create#VERSION
```

## compose

```yaml
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/azure.application.insights.create#VERSION }
    inputs: 
      subscriptionId:
      loginId:
      loginSecret:
      name:
      resourceGroup:
      # begin optional args
      location:
      type:
      hockeyAppToken:
      hockeyAppId:
      requestSource:
      loginTenantId:
      loginType:
      # end optional args
```
