# GithubActions

```
curl \
  -X POST \
  -H "Accept: application/vnd.github.v3+json" \
  https://api.github.com/repos/octocat/hello-world/dispatches \
  -d '{"event_type":"event_type"}'
  ```
  
  ```
  on:
  repository_dispatch:
    types: [opened, deleted]
  ```
  
  
