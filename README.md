# CFEngine Build module template

You can use this template if you want to make your own modules.
See this guide for an explanation:

https://github.com/cfengine/build-index/blob/master/CONTRIBUTING.md

This module has a policy file which reports the following string:

```
Hello from CFEngine Build
```

The string is printed to the terminal and sent to the reporting hub as inventory information (in CFEngine Enterprise).

It is meant as an example / starting point.
Edit `cfbs.json` and `my_policy.cf` to experiment.
