# Problem statement
creates an azure app insights instance (if it doesn't already exist)

# Example usage

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

# Support

join us on [![Slack](https://opspec-slackin.herokuapp.com/badge.svg)](https://opspec-slackin.herokuapp.com/)
or [open an issue](https://github.com/opspec-pkgs/azure.app-insights.create/issues)
