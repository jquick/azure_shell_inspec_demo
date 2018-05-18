# Example InSpec Azure Shell Profile

This example shows the implementation of an InSpec profile for Azure shell.

commands:
```
inspec exec inspec-demo -t azure://SUBSCRIPTION_ID
inspec exec https://github.com/dev-sec/ssh-baseline -t ssh://IP_ADDRESS -i PATH_TO_KEY
```

