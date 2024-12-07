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
- Calinou/scoop-games
- ivaquero/scoopet
- ScoopInstaller/Java
- ScoopInstaller/Versions
- TheRandomLabs/Scoop-Spotify
- borger/scoop-galaxy-integrations
- TheCjw/scoop-retools
- arch3rPro/PST-Bucket
- kodybrown/scoop-nirsoft
- TheRandomLabs/scoop-nonportable
- littleli/scoop-clojure
- hoilc/scoop-lemon
- ScoopInstaller/Nirsoft
- scoopcn/scoopcn
- kkzzhizhou/scoop-zapps
- rasa/scoops
- kidonng/sushi
- ScoopInstaller/Nonportable
- Paxxs/Cluttered-bucket
- KNOXDEV/wsl
- ACooper81/scoop-apps
- echoiron/echo-scoop
- cderv/r-bucket
- hermanjustnu/scoop-emulators
- couleur-tweak-tips/utils
- dodorz/scoop
- borger/scoop-emulators
- ViCrack/scoop-bucket
- whoopscs/scoop-security
- everyx/scoop-bucket
- niheaven/scoop-sysinternals
- Qv2ray/mochi
- wangzq/scoop-bucket
- kiennq/scoop-misc
- TheRandomLabs/Scoop-Bucket
- akirco/aki-apps
- wzv5/ScoopBucket
- zhoujin7/tomato
- TheRandomLabs/Scoop-Python
- jonz94/scoop-sarasa-nerd-fonts
- DoveBoy/Apps
- charmbracelet/scoop-bucket
- amorphobia/siku
- naderi/scoop-bucket
- hu3rror/scoop-muggle
- NyaMisty/scoop_bucket_misty
- cmontage/scoopbucket-third
- noql-net/scoop
- ygguorun/scoop-bucket
- aliesbelik/poldi
- Velgus/Scoop-Portapps
- iquiw/scoop-bucket
- liaoya/scoop-bucket
- AStupidBear/scoop-bear
- batkiz/backit
- ChungZH/peach
- 42wim/scoop-bucket
- brian6932/dank-scoop
- jfut/scoop-jfut
- abgox/abgo_bucket
- kengwang/scoop-ctftools-bucket
- SayCV/scoop-cvp
- cc713/ownscoop
- starise/Scoop-Confetti
- aoisummer/scoop-bucket
- starise/Scoop-Gaming
- TianXiaTech/scoop-txt
- Weidows-projects/scoop-3rd
- seumsc/scoop-seu
- Darkatse/Scoop-Darkatse
- AkariiinMKII/Scoop4kariiin
- Darkatse/Scoop-KanColle
- rivy/scoop-bucket
- alextwothousand/scoop-bucket
- HUMORCE/nuke
- mo-san/scoop-bucket
- beer-psi/scoop-bucket
- littleli/Scoop-littleli
- BenjaminMichaelis/Config
- Toddli468/Pentest-Scoop-Bucket
- Small-Ku/turbo-bucket
- ShuguangSun/sgs-scoop-bucket
- WinApps-share/WinApps-bucket
- FlawlessCasual17/MyScoop
- KnotUntied/scoop-fonts
- babo4d/scoop-xrtools
- The-Simples/scoop-minecraft
- natecohen/scoop-av
- Deide/deide-bucket
- AkinoKaede/maple
- yuanying1199/scoopbucket
