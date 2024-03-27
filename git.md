# 打包仓库

```sh
git archive --format=tar HEAD -o chat.tar 
```

# PUSH需要认证

    remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.

- 首先，获得`access token`
- settings–>Developer settings–>Personal access tokens–>Generate new token
- 再次push,需要`password`时填入`access token`
