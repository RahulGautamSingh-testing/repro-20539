## Debug Log

```log
DEBUG: Repository config (repository=RahulGautamSingh-testing/repro-20539)
       "fileName": "renovate.json",
       "config": {
         "$schema": "https://docs.renovatebot.com/renovate-schema.json",
         "hostRules": [
           {
             "hostType": "nuget",
             "hostName": "nuget.org",
             "matchHost": "nuget.org",
             "username": "root",
             "password": "***********"
           }
         ]
       }
DEBUG: migrateAndValidate() (repository=RahulGautamSingh-testing/repro-20539)
DEBUG: Config migration necessary (repository=RahulGautamSingh-testing/repro-20539)
       "oldConfig": {
         "$schema": "https://docs.renovatebot.com/renovate-schema.json",
         "hostRules": [
           {
             "hostType": "nuget",
             "hostName": "nuget.org",
             "matchHost": "nuget.org",
             "username": "root",
             "password": "***********"
           }
         ]
       },
       "newConfig": {
         "$schema": "https://docs.renovatebot.com/renovate-schema.json",
         "hostRules": [
           {
             "hostType": "nuget",
             "matchHost": "nuget.org",
             "username": "root",
             "password": "***********"
           }
         ]
       }
```
