# locize
## 发布
1. 推送到 test 分支，自动触发构建，不影响 prod  ,test 分支无缓存
2. 推送到 master 分支，自动触发构建，构建完成，自动刷新缓存

## Prod 访问
https://x/master/xx/zh/account.json?version=1

https://x/test/xx/zh/account.json?version=2


发布新版后，修改version ，即可到源站请求数据，自动刷新缓存


# lint

新增 pre-commit 插件, 提交前 eslint 验证 json 文件格式
