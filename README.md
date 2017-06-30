# problem statement
creates an azure app insights instance (if it doesn't already exist)

# example usage

> note: in examples, VERSION represents a version of the azure.app-insights.create pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/azure.app-insights.create#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/azure.app-insights.create#VERSION
```

## compose

```yaml
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/azure.app-insights.create#VERSION }
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
