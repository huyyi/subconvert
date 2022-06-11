# subconvert
使用 workflow 将 subconverter 部署到 okteto。

## 部署
1. 开通 okteto 账号并和 github 关联
2. 生成 okteto token 并将其添加到 github secret 命名为 `OKTETO_TOKEN`
3. 添加 secret `OKTETO_NAMESPACE`
4. 按官方 base 目录下的结构添加要替换的文件

## 常用操作
### 添加自定义 rule
1. 在 `base/rules/` 下添加规则文件
2. 在 `base/snippets/rulesets.txt` 中引用该文件
