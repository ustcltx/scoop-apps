<p align="center">
  scoop-apps
</p>
<p align="center">
  <a href="https://github.com/kkzzhizhou/scoop-apps"><img alt="GitHub" src="https://img.shields.io/badge/Readme--Style-standard--repository-brightgreen?style=flat-square&color=f83500"/></a>
  <a href="https://github.com/kkzzhizhou/scoop-apps"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/kkzzhizhou/scoop-apps?style=flat-square"/></a>
  <a href="https://github.com/kkzzhizhou"><img alt="GitHub user" src="https://img.shields.io/badge/author-kkzzhizhou-brightgreen?style=flat-square"/></a>
</p>


## 介绍

此仓库每天自动合并其他scoop仓库的更新

## 特性

- 每天更新
- 仓库列表根据项目[scoop-directory](https://github.com/rasa/scoop-directory)动态生成
- 自动处理同名文件，并优先采用较新版本, 重名文件以"软件-贡献人ID"重命名
- 自动去重（基于md5)
- json格式检验
- 支持仓库推荐、不推荐列表

## 说明

- 可接受仓库推荐，提交pr至bucket-recommend.txt即可
- 可接受"不维护仓库清理”，需在pr中说明理由，提交pr至bucket-not-recommend.txt即可
- **未对仓库软件来源进行安全检验，请自行甄别恶意软件，或者使用杀毒软件**
- 如果有软件安装问题，请参考仓库根路径的app-contributor-list.csv到相应的仓库提交issues

## 使用方法

```
scoop bucket add apps https://github.com/kkzzhizhou/scoop-apps
```

### 安装部分软件Hash Check Failed



因描述文件更新有概率更新到错误的文件，所以安装时出现“Hash Check Failed”，可以使用`-s`忽略，比如`scoop install xxx -s`即可，不放心的话可以到官网校验，或者根据仓库根路径的app-contributor-list.csv到相应的仓库提交issues

## 感谢

- [scoop-directory](https://github.com/rasa/scoop-directory)

## 合并仓库列表

- kkzzhizhou/scoop-zapps
- HCLonely/my-scoop-bucket
- Weidows-projects/scoop-3rd
- echoiron/echo-scoop
- ScoopInstaller/Extras
- chawyehsu/dorado
- matthewjberger/scoop-nerd-fonts
- Scoopforge/Extras-CN
- Calinou/scoop-games
- ScoopInstaller/Java
- ScoopInstaller/Versions
- hoilc/scoop-lemon
- arch3rPro/PST-Bucket
- TheRandomLabs/Scoop-Spotify
- borger/scoop-galaxy-integrations
- TheCjw/scoop-retools
- ScoopInstaller/Nirsoft
- kodybrown/scoop-nirsoft
- TheRandomLabs/scoop-nonportable
- littleli/scoop-clojure
- scoopcn/scoopcn
- ScoopInstaller/Nonportable
- tldrw/scoop-security
- kkzzhizhou/scoop-zapps
- rasa/scoops
- Paxxs/Cluttered-bucket
- kidonng/sushi
- ACooper81/scoop-apps
- cderv/r-bucket
- KNOXDEV/wsl
- echoiron/echo-scoop
- ScoopInstaller/PHP
- dodorz/scoop
- hermanjustnu/scoop-emulators
- niheaven/scoop-sysinternals
- couleur-tweak-tips/utils
- borger/scoop-emulators
- ViCrack/scoop-bucket
- kiennq/scoop-misc
- xrgzs/sdoog
- wangzq/scoop-bucket
- akirco/aki-apps
- cmontage/scoopbucket-third
- TheRandomLabs/Scoop-Bucket
- charmbracelet/scoop-bucket
- everyx/scoop-bucket
- DoveBoy/Apps
- EFLKumo/jam
- zhoujin7/tomato
- wzv5/ScoopBucket
- hu3rror/scoop-muggle
- naderi/scoop-bucket
- TheRandomLabs/Scoop-Python
- amorphobia/siku
- jonz94/scoop-sarasa-nerd-fonts
- NyaMisty/scoop_bucket_misty
- Small-Ku/turbo-bucket
- WinApps-share/WinApps-bucket
- kengwang/scoop-ctftools-bucket
- noql-net/scoop
- brian6932/dank-scoop
- ygguorun/scoop-bucket
- aliesbelik/poldi
- Scoopforge/Extras-Plus
- Velgus/Scoop-Portapps
- asimov-platform/scoop-bucket
- batkiz/backit
- Weidows-projects/scoop-3rd
- ocodo/wezterm-alt-windows-icon-builds
- zirnc/peach
- seumsc/scoop-seu
- iquiw/scoop-bucket
- starise/Scoop-Confetti
- Darkatse/Scoop-Darkatse
- TianXiaTech/scoop-txt
- 42wim/scoop-bucket
- starise/Scoop-Gaming
- jfut/scoop-jfut
- babo4d/scoop-xrtools
- mo-san/scoop-bucket
- aoisummer/scoop-bucket
- AkariiinMKII/Scoop4kariiin
- cc713/ownscoop
- natecohen/scoop-av
- typst-community/scoop-bucket
- rivy/scoop-bucket
- AntonOks/scoop-aoks
- HUMORCE/nuke
- maboloshi/scoop-private
- 404NetworkError/scoop-bucket
- littleli/Scoop-littleli
- Deide/deide-bucket
- KnotUntied/scoop-fonts
- littleli/Scoop-AtariEmulators
- BenjaminMichaelis/Config
- p8rdev/scoop-portableapps
- beer-psi/scoop-bucket
- ChinLong/scoop-customize
- ShuguangSun/sgs-scoop-bucket
- Rinkerbel/scooped
- windedge/ladle-bucket
- The-Simples/scoop-minecraft
- younger-1/scoop-it
- LaelLuo/scoop
- jcwillox/scoop-python
- Apocalypsor/My-Scoop-Bucket
- se35710/scoop-ibm
