# NEOPlayGround
Code playground for HUAWEI

---

## 在任何地方拉取
以网吧为例，要用gitee下载steam++，同时开一个ubuntu codespace或者上开一个Ubuntu。若有必要则换源。

```
eval "$(curl https://get.x-cmd.com)"
```

---

## Git|Github|LazyGit

本仓库存在GitHub，默认网络环境正常且懂得基本使用。这里引入Lazygit作为TUI，方便识别和观察。

```
x env use lazygit
lazygit --config | grep "lang"                                      # 查看 lazygit 当前使用的自然语言
lazygit -cd                                                         # 获取 lazygit 的配置文件目录
printf "gui:\n  language: zh-CN\n" > "$(lazygit -cd)/config.yml"    # 修改 lazygit 配置文件，如将语言设置为中文
```
