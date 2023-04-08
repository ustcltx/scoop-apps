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
- ScoopInstaller/Java
- ivaquero/scoopet
- TheRandomLabs/Scoop-Spotify
- borger/scoop-galaxy-integrations
- TheRandomLabs/scoop-nonportable
- ScoopInstaller/Versions
- TheCjw/scoop-retools
- kodybrown/scoop-nirsoft
- littleli/scoop-clojure
- kidonng/sushi
- rasa/scoops
- kkzzhizhou/scoop-zapps
- ScoopInstaller/Nirsoft
- KNOXDEV/wsl
- hoilc/scoop-lemon
- echoiron/echo-scoop
- scoopcn/scoopcn
- hermanjustnu/scoop-emulators
- Paxxs/Cluttered-bucket
- cderv/r-bucket
- ACooper81/scoop-apps
- everyx/scoop-bucket
- dodorz/scoop
- borger/scoop-emulators
- TheRandomLabs/Scoop-Bucket
- ZvonimirSun/scoop-iszy
- Qv2ray/mochi
- kiennq/scoop-misc
- ScoopInstaller/Nonportable
- zhoujin7/tomato
- wangzq/scoop-bucket
- wzv5/ScoopBucket
- TheRandomLabs/Scoop-Python
- naderi/scoop-bucket
- akirco/aki-apps
- ChungZH/peach
- ygguorun/scoop-bucket
- ViCrack/scoop-bucket
- 42wim/scoop-bucket
- NyaMisty/scoop_bucket_misty
- niheaven/scoop-sysinternals
- batkiz/backit
- iquiw/scoop-bucket
- jonz94/scoop-sarasa-nerd-fonts
- amorphobia/siku
- cc713/ownscoop
- ChinLong/scoop-customize
- seumsc/scoop-seu
- Velgus/Scoop-Portapps
- rivy/scoop-bucket
- aoisummer/scoop-bucket
- yuusakuri/scoop-bucket
- hu3rror/scoop-muggle
- Darkatse/Scoop-KanColle
- starise/Scoop-Gaming
- Zliced13/MyScoop
- starise/Scoop-Confetti
- TheLastZombie/scoop-bucket
- hulucc/bucket
- jingyu9575/scoop-jingyu9575
- Deide/deide-bucket
