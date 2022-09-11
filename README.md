```
$ cp .env.sample .env
$ make up
$ yarn turbo run build --team="team_myteam" --token="mytoken" --api="http://localhost:3000"
$ rm -rf node_modules/.cache/turbo
$ yarn turbo run build --team="team_myteam" --token="mytoken" --api="http://localhost:3000"
$ make down
```