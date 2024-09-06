## Logs from a local run

```
DEBUG: Combined config
       "config": {
         "token": "***********",
         "repositories": ["Rahul-renovate-testing/repro-31199"],
         "hostRules": [{"matchHost": "somehost", "token": "{{secrets.HAHA}}"}],
         "secrets": {"HAHA": "***********"},
         "prHourlyLimit": 10,
         "repositoryCache": "disabled",
         "binarySource": "global"
       }
```
