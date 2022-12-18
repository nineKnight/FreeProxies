# TopFreeProxies
[![GitHub Workflow Status](https://github.com/alanbobs999/topfreeproxies/actions/workflows/get-proxies.yml/badge.svg)](https://github.com/alanbobs999/TopFreeProxies/actions/workflows/get-proxies.yml) 

![Watchers](https://img.shields.io/github/watchers/alanbobs999/topfreeproxies) ![Stars](https://img.shields.io/github/stars/alanbobs999/topfreeproxies) ![Forks](https://img.shields.io/github/forks/alanbobs999/topfreeproxies) ![Vistors](https://visitor-badge.laobi.icu/badge?page_id=alanbobs999.topfreeproxies) ![LICENSE](https://img.shields.io/badge/license-CC%20BY--SA%204.0-green.svg)

[仓库介绍](https://github.com/alanbobs999/TopFreeProxies#仓库介绍) | [使用方法](https://github.com/alanbobs999/TopFreeProxies#使用方法) | [节点信息](https://github.com/alanbobs999/TopFreeProxies#节点信息) | [仓库声明](https://github.com/alanbobs999/TopFreeProxies#仓库声明)

## 仓库介绍
本仓库自动化功能全部基于 `GitHub Actions` 实现，如有需要可以自行 Fork 实现个性化需求，功能配置在 `./utils/config.ini` 配置文件中。

对网络上各免费节点池及博主分享的节点进行测速筛选出较为稳定高速的节点，再导入到仓库中进行分享记录。所筛选的节点链接在仓库 `./sub/sub_list.json` 文件中，其中大部分为其他 `GitHub` 仓库链接，如果大家有好的订阅链接欢迎提交 PR ，这些链接包含的所有节点会合并在仓库 `./sub/sub_merge.txt` 中。

测速筛选后的节点订阅文件在仓库根目录 `Eterniy`(Base64) 和 `Eternity.yaml`(Clash)。同时在仓库的 `./update` 中保留了原始节点链接的的记录。

订阅转换使用 [subconverter](https://github.com/tindy2013/subconverter) 实现，测速功能使用 [LiteSpeedTest](https://github.com/xxf098/LiteSpeedTest) 在 `GitHub Actions` 环境下实现，所以美国节点较多，不能很好代表国内网络环境下节点可用性，目前正在解决这一问题。

虽然是测速筛选过后的节点，但仍然会出现部分节点不可用的情况，遇到这种情况建议选择`Clash`, `Shadowrocket`之类能自动切换低延迟节点的客户端。

## 使用方法
将以下订阅链接导入相应客户端即可。链接中大部分为 SS 协议节点，少量 Vmess, Trojan ,SSR 协议节点，建议选择协议支持完整的客户端。

- [多协议Base64编码](https://raw.githubusercontent.com/raysue/TopFreeProxies/master/Eternity)
- [Clash](https://raw.githubusercontent.com/raysue/TopFreeProxies/master/Eternity.yaml)

另有国内加速链接：

- [多协议Base64编码](https://fastly.jsdelivr.net/gh/raysue/TopFreeProxies@master/Eternity)
- [Clash](https://fastly.jsdelivr.net/gh/raysue/TopFreeProxies@master/Eternity.yaml)

>`Clash`链接所使用的配置在仓库`./update/provider/`中，有相应配置文件和以国家分类的`proxy-provider`。
>
>需要其它配置可使用订阅转换工具自行转换。
>自用在线订阅转换网址：[sub-web-modify](https://sub.v1.mk/)

## 节点信息
### 高速节点
高速节点数量: `85`
<details>
  <summary>展开复制节点</summary>

    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgW1ZNZXNzXSDwn4et8J+HsCBIS+OAkOS7mOi0ueaOqOiNkO+8mmdvby5ncy92aXDjgJEiLCJhZGQiOiI4LjIxOC4xMjIuMjQ2IiwicG9ydCI6IjUzNjE3IiwidHlwZSI6Im5vbmUiLCJpZCI6IjY4MjM3OGI4LTY0NjctNDk1OC04NjMwLWRiOTU4MWY0MjVlMSIsImFpZCI6IjAiLCJuZXQiOiJodHRwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://b26e31e5-eac1-45b0-9069-83830bd69521@20.187.85.198:443?allowInsecure=1&sni=hkt.iamnotagoodman.com#HK_AzadNet
    trojan://ceaea123-1b4b-469b-8358-bcd5f5529305@104.208.100.101:443?allowInsecure=1&sni=uk.liangyuandian.top#HK_AzadNet%281%29
    trojan://28d98f761aca9d636f44db62544628eb@45.66.134.219:443?allowInsecure=1#JP_AzadNet
    trojan://7x42LetRa0@106.180.225.69:1443?allowInsecure=1#JP_AzadNet%281%29
    trojan://4f7dc540-d244-4e64-af21-4b5bb300add3@132.226.5.246:443?allowInsecure=1&sni=www.tokyo2023.ga#JP_AzadNet%282%29
    trojan://d66013c645b93c5c@211.72.35.158:3389?allowInsecure=1#TW_AzadNet
    trojan://YWVzLTI1Ni1nY206eHBRd3lWNFc1RmRBNk5NQU5KSng3M1VT@2.58.242.43:443?allowInsecure=1#TW_AzadNet%281%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgQFNTUlNVQi3ml6XmnKxWMDgt5LuY6LS55o6o6I2QZGxqLnRmL3NzcnN1YiIsImFkZCI6Imh0dHAuZG93bmxvYWQueXVuemhvbmd6aHVhbi5jb20iLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiMGRiMGE0NzktODk5My00ZTViLWEwMDItNjI5ZTllMGI0MGU1IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcGkvdjMvZG93bmxvYWQuZ2V0RmlsZSIsImhvc3QiOiJvMDgudGdmYWthLmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMDEiLCJhZGQiOiIxMDQuMjkuNjQuMjQiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiM2Y0MjFlMjctNWJmOC00MGM5LTg2Y2ItN2I4YzQxZGRkZWEyIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9sWHZBMFZzZS8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMDUiLCJhZGQiOiJodHRwLmRvd25sb2FkLnl1bnpob25nemh1YW4uY29tIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjBkYjBhNDc5LTg5OTMtNGU1Yi1hMDAyLTYyOWU5ZTBiNDBlNSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvYXBpL3YzL2Rvd25sb2FkLmdldEZpbGUiLCJob3N0Ijoic3Nyc3ViLnYwMS5hc3VrYS5idXp6IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMDciLCJhZGQiOiIzMzF0dy5mYW5zOC54eXoiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiN2Y0ZmYyZTEtYzA4Zi0zNWJkLWFmZTctNGE2YTM4NjkwN2FhIiwiYWlkIjoiMiIsIm5ldCI6IndzIiwicGF0aCI6Ii9yYXkiLCJob3N0IjoiMzMxdHcuZmFuczgueHl6IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMDkiLCJhZGQiOiIyMjAuMTMwLjgwLjE3OSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiY2ViOGE3ZjQtYTQ1Yi00OGE3LThmOGUtY2E3MTI0YTVlYmVlIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9ob3dkeSIsImhvc3QiOiJ2MnJheTIudWRwZ3cuY29tIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMTAiLCJhZGQiOiIwMjE4dHcwMi5mYW5zOC54eXoiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNWM3MGRhNWQtZTY0MS0zYmY4LWI3ZGMtNWJhYmQ4NDNmZjNjIiwiYWlkIjoiMiIsIm5ldCI6IndzIiwicGF0aCI6Ii92MnJheSIsImhvc3QiOiIwMjE4dHcwMi5mYW5zOC54eXoiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMTEiLCJhZGQiOiIxNjUuMTU0LjIyNi40NSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJmYTA3MDJmNC04ZWM5LTQ4ZTUtOWI1My1hMGFmYjdjMzcxN2UiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMTIiLCJhZGQiOiIyMTEuNzIuMzUuMTEwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI1NDFjYTAyNi01OGQzLTQ4ZjEtZDZlZi0zYTA1NTQzZGRjYjciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJydS50emNjaWZxLmdhIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMTMiLCJhZGQiOiJhMDEtaGsxLm1vb250b2RheS51ayIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTQ1ZTIxYWMtYWIwYy00Zjg5LWI2OGMtZTYxMTQ5MDk1ZWYzIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9tb29udG9kYXkiLCJob3N0IjoiYTAxLWhrMS5tb29udG9kYXkudWsiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMTQiLCJhZGQiOiJhMDgtaGsxLm1vb250b2RheS51ayIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTQ1ZTIxYWMtYWIwYy00Zjg5LWI2OGMtZTYxMTQ5MDk1ZWYzIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9tb29udG9kYXkiLCJob3N0IjoiYTA4LWhrMS5tb29udG9kYXkudWsiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMTUiLCJhZGQiOiJhMTAta29yMS5tb29udG9kYXkudWsiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE0NWUyMWFjLWFiMGMtNGY4OS1iNjhjLWU2MTE0OTA5NWVmMyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvbW9vbnRvZGF5IiwiaG9zdCI6ImExMC1rb3IxLm1vb250b2RheS51ayIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMTYiLCJhZGQiOiJhMDMtanAxLm1vb250b2RheS51ayIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTQ1ZTIxYWMtYWIwYy00Zjg5LWI2OGMtZTYxMTQ5MDk1ZWYzIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9tb29udG9kYXkiLCJob3N0IjoiYTAzLWpwMS5tb29udG9kYXkudWsiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMTciLCJhZGQiOiI2MS4yMTYuODUuNjgiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjViYTczOGU3LTBhYmYtNDkzNS1iNjdlLWQ0MDRhMDgzZDZhNiIsImFpZCI6IjY0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3BhdGgvMjQzNTM1MzIyOTA2IiwiaG9zdCI6Ind3dy44ODYxMjg2MC54eXoiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMTgiLCJhZGQiOiJkZG5zMi5haXJ0Y3AudmlwIiwicG9ydCI6IjEwMDAxIiwidHlwZSI6Im5vbmUiLCJpZCI6IjdmNjdmYjExLTgzMmQtMzQ5Mi1hZGZlLTYzZTBjY2VhZmJlMCIsImFpZCI6IjIiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6ImRkbnMyLmFpcnRjcC52aXAiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMTkiLCJhZGQiOiJ0dzIucm92b2QudG9wIiwicG9ydCI6IjEwMDAwIiwidHlwZSI6Im5vbmUiLCJpZCI6ImFiNDJlYTFmLThlMmYtM2ZmZi04YTExLWQxMjRkNjJiODQ5ZSIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiJkZG5zMi5haXJ0Y3AudmlwIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMjAiLCJhZGQiOiIxNjUuMTU0LjI0Ni4xMDciLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiZmEwNzAyZjQtOGVjOS00OGU1LTliNTMtYTBhZmI3YzM3MTdlIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoidG1zLmRpbmd0YWxrLmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMjEiLCJhZGQiOiJ0d3RwMi5henpodWFuZ2FwaW5nLnR3IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjRjNGUwNjVmLTM2M2ItM2M5Yi04YTRkLTMxMmY2Yjk4NDBkMyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvYWRvYmUiLCJob3N0IjoidHd0cDIuYXp6aHVhbmdhcGluZy50dyIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMjIiLCJhZGQiOiJ4dDAwMS54bXJ0aG5vZGUuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhNmM3MjEwMy1iMmEwLTNlN2YtOWQ0OS1jZjM3ODIwOWU3M2IiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJ3cy1haWNkbi5jb20iLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMjMiLCJhZGQiOiJ0dzAyLm50dGtrLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiM2E5YzBkMGMtZTBmZC0zMTQ1LWE0MTQtZWMyNjVlNzAxMGI3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoidHcwMi5udHRray5jb20iLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMjQiLCJhZGQiOiJ0dzQuNTk0ODg4Lnh5eiIsInBvcnQiOiIxMTQ2MyIsInR5cGUiOiJub25lIiwiaWQiOiJkZDc2MzljZi02NmRkLTMwMzgtYWIwZS1jZWZlN2U5ZWY5ZmIiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3YycmF5IiwiaG9zdCI6InR3NC41OTQ4ODgueHl6IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMjUiLCJhZGQiOiJ0dzMuNTk0ODg4Lnh5eiIsInBvcnQiOiIyNTU1MSIsInR5cGUiOiJub25lIiwiaWQiOiJkZDc2MzljZi02NmRkLTMwMzgtYWIwZS1jZWZlN2U5ZWY5ZmIiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3YycmF5IiwiaG9zdCI6InR3My41OTQ4ODgueHl6IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgwMjYiLCJhZGQiOiJ0d3RwLmF6emh1YW5nYXBpbmcudHciLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNGM0ZTA2NWYtMzYzYi0zYzliLThhNGQtMzEyZjZiOTg0MGQzIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hZG9iZSIsImhvc3QiOiJ0d3RwLmF6emh1YW5nYXBpbmcudHciLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgyMzEiLCJhZGQiOiJjZG4uZ21wb3JhLm1lIiwicG9ydCI6IjgwODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNzQ5Njk2NGYtYjUzNS00MjY2LTkwM2UtODVjOTg2YTE1ODRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiaGsxLmdtcG9yYS5tZSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgyNDIiLCJhZGQiOiJ0dzIuY3pzMTAwMC5jb20iLCJwb3J0IjoiNDAxMSIsInR5cGUiOiJub25lIiwiaWQiOiJlOWEzZDZhZi03MThlLTRjZjctYWQ2Yy00MTczYmI4MjJiYTIiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiaGsxLmdtcG9yYS5tZSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgyNDUiLCJhZGQiOiIxOGMwMzVhNS1jZmEwLTZlMDctNjkwNi04MzRkZTNiM2ViNzMuY25uaWMucmlwIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjBiZDNkZGEyLTg4ZTgtNGU3Yy1hNDZlLTdkYjdkMWQzY2I0ZCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiJoazEuZ21wb3JhLm1lIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgyNDgiLCJhZGQiOiIyMTEuMjMuMTYwLjI0MyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDE4MDQ4YWYtYTI5My00Yjk5LTliMGMtOThjYTM1ODBkZDI0IiwiYWlkIjoiNjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvcGF0aC8yNDM1MzUzMjI5MDYiLCJob3N0Ijoid3d3LjMzMDYxMjIyLnh5eiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgyNTYiLCJhZGQiOiJkMDQxYTU4NS0wYzFlLWU5MjgtZGZiYi1jNWM0YmI3Zjk2ODUuY25uaWMucmlwIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjBiZDNkZGEyLTg4ZTgtNGU3Yy1hNDZlLTdkYjdkMWQzY2I0ZCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6InRtcy5kaW5ndGFsay5jb20iLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgyNjIiLCJhZGQiOiJ2MnNnMS43NDE3NDEueHl6IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjI2YzVmZGM3LWIzYmUtMzQ4Mi05YTQ1LWQ5N2I5NThhODg5YSIsImFpZCI6IjIiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6InYyc2cxLjc0MTc0MS54eXoiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7Mg5Y+w5rm+XzEyMTgyNjMiLCJhZGQiOiJ0d2lwdjQudXNlaXB2Nm5vdy5jb20iLCJwb3J0IjoiNjYxNyIsInR5cGUiOiJub25lIiwiaWQiOiI3MjVkMGRhNC1lNTQ3LTQ2MzItYWFhOS01ZGRjNzIzM2IwZjQiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJ0d2lwdjQudXNlaXB2Nm5vdy5jb20iLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzEyMTgwMDIiLCJhZGQiOiIxNTcuMjMwLjM2LjIzNSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJiNDg0ZDU3Ni1iM2UzLTRhYzUtYjEwOC04OGEzMDBkZmU3ZTMiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2dyYXBocWwiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzEyMTgwMDQiLCJhZGQiOiJnY29yZXNnLnN5bHUuY3lvdSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTJlMDgyNTYtZGE1ZC00YjFjLWFlY2EtOGM5NzNjY2NlZWY4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9GYWxsaW5nNDJnY29yZXNnbm9kZSIsImhvc3QiOiJnY29yZXNnLnN5bHUuY3lvdSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzEyMTgwMDgiLCJhZGQiOiJzZzAzLjE3MDIwMy54eXoiLCJwb3J0IjoiNDM1NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNjQxMmM3ZDgtZjNhNy00NzM5LTk1OTQtYjQ0Njg3Yjc4MTVmIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0Ijoic2cwMy4xNzAyMDMueHl6IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzEyMTgwMDkiLCJhZGQiOiJzZzAwMS4xNzAyMDMueHl6IiwicG9ydCI6IjQzNTQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjY0MTJjN2Q4LWYzYTctNDczOS05NTk0LWI0NDY4N2I3ODE1ZiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6InNnMDAxLjE3MDIwMy54eXoiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzEyMTgwMTIiLCJhZGQiOiI4LjIxOS4xNzEuMTE0IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIwNzY0YTU5OC04MmM0LTRiNDEtYmExMC01NTFhNjI1YmVlZDUiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3NzaG9jZWFuIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzEyMTgwMTMiLCJhZGQiOiIwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwNmEubm9kZS1mb3ItYmlnYWlycG9ydC53aW4iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjIxMDAyNzRlLTU1YWUtNDY4Ni1hMzgwLWE2NmFlOGIwZWYxYiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL3NzaG9jZWFuIiwiaG9zdCI6IjAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDAwMDA2YS5ub2RlLWZvci1iaWdhaXJwb3J0LndpbiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuPCfh6wg5paw5Yqg5Z2hXzEyMTgwMTQiLCJhZGQiOiJzZy1hLnRlbmNlbnQuY2ZkIiwicG9ydCI6IjY1NTI4IiwidHlwZSI6Im5vbmUiLCJpZCI6IjdhOGEyMTU4LWVkNjItNDM2NC04YmE5LTkzN2YwYWI5ZDZmMCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6InNnLWEudGVuY2VudC5jZmQiLCJ0bHMiOiIifQ==
    trojan://f42e1a2e-e650-44f4-8d17-bcb68663da18@150.230.201.192:443?allowInsecure=1&sni=www.seetheworldjp.ga#US_AzadNet%284%29
    trojan://b5fc9fa9-796d-4185-a316-395ecac04a85@150.230.249.20:443?allowInsecure=1&sni=www.gomacau.gq#US_AzadNet%285%29
    vmess://eyJ2IjoiMiIsInBzIjoiVVNfQXphZE5ldCg2KSIsImFkZCI6IjEwNy4xODkuMzEuNDEiLCJwb3J0IjoiMTIzNzgiLCJ0eXBlIjoibm9uZSIsImlkIjoiOWUzMTJlZjUtNmQ0MC00ZmNiLWNlYjMtNGM3YTY5YmJlMGIzIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9AQmFja2Rvcl9GaWx0ZXIiLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://c51d3975-a40c-4a5b-929b-c8595ed87850@15.168.28.231:443?allowInsecure=1&sni=wel-usgt.optage.moe#US_AzadNet%288%29
    trojan://WpfQAbO2wg@45.9.10.103:443?allowInsecure=1#US_AzadNet%289%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggQFNTUlNVQi3nvo7lm71WMDQt5LuY6LS55o6o6I2QZGxqLnRmL3NzcnN1YiIsImFkZCI6Ind3dy5kaWdpdGFsb2NlYW4uY29tIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjBkYjBhNDc5LTg5OTMtNGU1Yi1hMDAyLTYyOWU5ZTBiNDBlNSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvYXBpL3YzL2Rvd25sb2FkLmdldEZpbGUiLCJob3N0Ijoic3Nyc3ViLnYwMi5hc3VrYS5idXp6IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggQFNTUlNVQi3nvo7lm71WMDUt5LuY6LS55o6o6I2QZGxqLnRmL3NzcnN1YiIsImFkZCI6Imh0dHAuZG93bmxvYWQueXVuemhvbmd6aHVhbi5jb20iLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiMGRiMGE0NzktODk5My00ZTViLWEwMDItNjI5ZTllMGI0MGU1IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcGkvdjMvZG93bmxvYWQuZ2V0RmlsZSIsImhvc3QiOiJzc3JzdWIudjAyLmFzdWthLmJ1enoiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggQFNTUlNVQi3nvo7lm71WMDYt5LuY6LS55o6o6I2QZGxqLnRmL3NzcnN1YiIsImFkZCI6ImdnMS50YW5nbHUueHl6IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjBkYjBhNDc5LTg5OTMtNGU1Yi1hMDAyLTYyOWU5ZTBiNDBlNSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvYXBpL3YzL2Rvd25sb2FkLmdldEZpbGUiLCJob3N0Ijoic3Nyc3ViLnYwMi5hc3VrYS5idXp6IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggQFNTUlNVQi3nvo7lm71WMTEt5LuY6LS55o6o6I2QZGxqLnRmL3NzcnN1YiIsImFkZCI6Imh0dHAuZG93bmxvYWQueXVuemhvbmd6aHVhbi5jb20iLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiMGRiMGE0NzktODk5My00ZTViLWEwMDItNjI5ZTllMGI0MGU1IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcGkvdjMvZG93bmxvYWQuZ2V0RmlsZSIsImhvc3QiOiJvMDcudGdmYWthLmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh6Yg5Yqg5ou/5aSnXzEyMTgwMDMiLCJhZGQiOiJjYTAxLnYybmV0LnRvcCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNjFENTI3NjMtNDg3Ri00RkU0LUIwQUMtOEJCNkFENDdDOTE3IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9yYXkiLCJob3N0IjoiY2EwMS52Mm5ldC50b3AiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh6Yg5Yqg5ou/5aSnXzEyMTgwMDYiLCJhZGQiOiJ1cy5oZS4wMS5uZWtvY2xvdWQuY24iLCJwb3J0IjoiMTkwNDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNGVkMDljNTQtYzNjNi0zNWRjLTllOWQtZjAyMzcxNTU5MWIyIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9jYXRuZXQiLCJob3N0IjoidXMuaGUuMDEubmVrb2Nsb3VkLmNuIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh6Yg5Yqg5ou/5aSnXzEyMTgwMTgiLCJhZGQiOiIwMi5tb250cmVhbC5jYW4uYW5ydW4taXgudG9wIiwicG9ydCI6IjEzMDMwIiwidHlwZSI6Im5vbmUiLCJpZCI6ImRkODZhMTA1LTAwYzEtNDFiYS04OTljLWMzMWFhNzRmNDUzOSIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL2NhdG5ldCIsImhvc3QiOiJ1cy5oZS4wMS5uZWtvY2xvdWQuY24iLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh6Yg5Yqg5ou/5aSnXzEyMTgwMjAiLCJhZGQiOiJyaW9wLm1pYW9nZTExMC5jZiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDg5M2VkM2UtOGE1Zi00OGRjLWFhMWUtYmJjMmU2N2EwNjViIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9EYW5odWFuZy9KaWFuZyIsImhvc3QiOiJyaW9wLm1pYW9nZTExMC5jZiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh6Yg5Yqg5ou/5aSnXzEyMTgwMjEiLCJhZGQiOiIzNS4xODIuMTY1LjEyMCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiZDhjNWI0ODYtODRiYi0zODg3LWExZDktMDc0NTVlYTYwOGYyIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii92MnJheSIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh6Yg5Yqg5ou/5aSnXzEyMTgwMjIiLCJhZGQiOiI3MS4xOS4yNDguMTYxIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIzZDE3M2YwYS0xMzhiLTRiYWYtOWVjNi00ODQ4MjQzZTBhMTIiLCJhaWQiOiI2NCIsIm5ldCI6IndzIiwicGF0aCI6Ii9wYXRoLzI0MzUzNTMyMjkwNiIsImhvc3QiOiJ3d3cuNjM2NTcyNzQueHl6IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh6Yg5Yqg5ou/5aSnXzEyMTgwMjYiLCJhZGQiOiJjYTEuY3pzMTAwMC5jb20iLCJwb3J0IjoiMTEyMTciLCJ0eXBlIjoibm9uZSIsImlkIjoiODliZGU0NTktY2RiOS00NTk4LWJlZTctYTI4MjM5MTllOTBiIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9maWxlc3RyZWFtaW5nc2VydmljZS9maWxlcy8yMGY4MTNlMi0wMzZhLTQyYTgtOTJlMi1hM2E1NWEwYjIzOWIiLCJob3N0IjoidGx1LmRsLmRlbGl2ZXJ5Lm1wLm1pY3Jvc29mdC5jb20iLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi5LmM5YWL5YWwXzEyMTgwMDEiLCJhZGQiOiI1LjE4OC42LjIyMiIsInBvcnQiOiIyMDg0OSIsInR5cGUiOiJub25lIiwiaWQiOiI1NDNjZjVlNy1hNjc0LTQxMDEtZDk5Ny1jMjJlODczMmE4YWYiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoKSA4MyIsImFkZCI6IjUxLjc3LjE1OC4xNjkiLCJwb3J0IjoiMjA5NiIsInR5cGUiOiJub25lIiwiaWQiOiJjOTJmZDkwMi1iNWQzLTQyMDgtYmI0OC02MzBiMWM3YmFiZWEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiI1MS43Ny4xNTguMTY5IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiW1ZNZXNzXSDwn4ey8J+HtCBNT+OAkOS7mOi0ueaOqOiNkO+8mmdvby5ncy92aXDjgJEiLCJhZGQiOiI0NS42NC4yMi4yMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNGJkNzRjMjctZDIzYS00MDgzLWJlMmEtNWMyYzEzOWRhZGI0IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9QM2dqbSIsImhvc3QiOiJnLnBneXBneWttb2xqa2xqLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hs/Cfh7EgZ2l0aHViLmNvbS9mcmVlZnEgLSDojbflhbAgIDM0IiwiYWRkIjoiMTk1LjEyMy4yMTkuNzEiLCJwb3J0IjoiMTAwMDAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDVkODA2OTQtN2UxMS0xMWVkLTljZjEtODcwMTMyODc4OTMwIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii92cG5qYW50aXQiLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoKSA4MSIsImFkZCI6IjEwNC4xOS4zNi4xNjAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImFkODA2NDg3LTJkMjYtNDYzNi05OGI2LWFiODVjYzg1MjFmNyIsImFpZCI6IjY0IiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIxMDQuMTkuMzYuMTYwIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoKSA3OSIsImFkZCI6ImZyZWUtcnVzc2lhbjAxLWNkbi54aWFvaG91emkuY2x1YiIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiIzZDMxNzI4ZS0wNjRkLTQyYjgtYjk0NS1mNzljMDA4ZjczZmMiLCJhaWQiOiIyMzMiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6ImZyZWUtcnVzc2lhbjAxLWNkbi54aWFvaG91emkuY2x1YiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMiIsImFkZCI6InhqcC5tdnphaXhpYW4zLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNzc2MzUyYWMtMGE5MS0zZDcxLTg0NTAtZDNiM2EyYjQzYzczIiwiYWlkIjoiNjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZGFzMzIxOHNzeGMiLCJob3N0IjoieGpwLm12emFpeGlhbjMuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoKSA3OCIsImFkZCI6Ijg1LjExNy4yMzQuMTg0IiwicG9ydCI6IjE5MzAzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImMzODA2YWJmLWFmYWYtNGVkMS04ZjdlLTQxYTdlY2RiYjRlMyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL2RhczMyMThzc3hjIiwiaG9zdCI6InhqcC5tdnphaXhpYW4zLmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoKSA3NyIsImFkZCI6IjQ2LjE4Mi4xMDcuNDQiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImZlNWY2OWU3LWUxODMtNDM5Yi05NTBiLTgyMjFlZjA2NTFmMiIsImFpZCI6IjY0IiwibmV0Ijoid3MiLCJwYXRoIjoiL2Zvb3RlcnMiLCJob3N0IjoiNDYuMTgyLjEwNy40NCIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoKSA3NCIsImFkZCI6ImpwYXdzLmh1YXJlbmxpZmUudG9wIiwicG9ydCI6Ijg4ODgiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWU3NDg2ZjktZDdiNy00ZjI2LTk3YTAtZGM1YjA5M2RmYTg5IiwiYWlkIjoiMSIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoianBhd3MuaHVhcmVubGlmZS50b3AiLCJ0bHMiOiIifQ==
    trojan://idc117okt@103.176.78.153:443?allowInsecure=1#_AzadNet
    trojan://6f6ae34d-fe7f-4ca1-a912-ecc01386bdc4@103.173.155.72:28443?allowInsecure=1#_AzadNet%281%29
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoKSA3MiIsImFkZCI6ImNhY2VydHMuZGlnaWNlcnQuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI5Mzc5ZmVhMC0wMDZkLTRmZDMtOGUzNS1kNDVhNWFmNzJhYTIiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJjYWNlcnRzLmRpZ2ljZXJ0LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiREVfQXphZE5ldCIsImFkZCI6IjE4OC4zNC4xNTkuMTg2IiwicG9ydCI6IjM1ODU1IiwidHlwZSI6Im5vbmUiLCJpZCI6Ijk3ZThmYmE3LTMyN2EtNDc1Mi04YWNhLTA0Mzg1OGE3ZTUxOCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiREVfQXphZE5ldCgyKSIsImFkZCI6IjUuMTYxLjEzMy42NSIsInBvcnQiOiI1MjMxNyIsInR5cGUiOiJub25lIiwiaWQiOiJlOGRjZDUxZS0wOThkLTQxNTUtZDIzMi0xNDM4YzRmNDBkYzYiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoKSA2NyIsImFkZCI6IjEwNC4xOC42Mi4xNzkiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImZmZmZmZmZmLWZmZmYtZmZmZi1mZmZmLWZmZmZmZmZmZmZmZiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvdm1lc3MiLCJob3N0IjoiMTA0LjE4LjYyLjE3OSIsInRscyI6InRscyJ9
    trojan://8697fe6b-1lWNFc1RmRBNk5NQU5KSnga3fa58ac5a3ef0-b4ab-11eb-b65e-1239d0255272@185.44.76.188:443?allowInsecure=1#GB_AzadNet
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoKSA2NSIsImFkZCI6Imh1Y2xvdWQudGsiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjJkZjNlZDRhLTQzMTMtNDVmOS1iNzQyLTJmMDJjZTU5M2E2ZSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6Imh1Y2xvdWQudGsiLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1jZmI6S25KR2FkM0ZxVHZqcWJhWA@213.183.53.222:9014#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%29%2064
    trojan://67e200f1-4ff5-42ca-8425-3f16f7986c29@51.89.22.228:443?allowInsecure=1&sni=t1.samsung.bforward2.uk#GB_AzadNet%287%29
    ss://YWVzLTI1Ni1jZmI6VWtYUnNYdlI2YnVETUcyWQ@213.183.63.221:9001#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%29%2062
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpwcnloeXh5YQ@52.58.249.78:57824#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%29%2060
    ss://YWVzLTI1Ni1jZmI6OVh3WXlac0s4U056UUR0WQ@185.246.155.35:9059#NL_AzadNet
    ss://YWVzLTI1Ni1jZmI6Qk5tQVhYeEFIWXBUUmR6dQ@185.246.155.23:9020#NL_AzadNet%281%29
    

</details>

### 所有节点
合并节点总数: `2360`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `130`
- [Alvin9999/pac2](https://github.com/Alvin9999/pac2), 节点数量: `82`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `141`
- [freefq/free](https://github.com/freefq/free), 节点数量: `28`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `5`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `1`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `38`
- [AzadNetCH/Clash](https://github.com/AzadNetCH/Clash), 节点数量: `465`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `40`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `3989`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `1`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `47`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `28`
- [gfwglass 节点池](https://gfwglass.tk), 节点数量: `1`
- [Meteor-1337/Meteor](https://github.com/Meteor-1337/Meteor), 节点数量: `1`
- [ronghuaxueleng/get_v2](https://github.com/ronghuaxueleng/get_v2), 节点数量: `156`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `116`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `38`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `29`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `8`
- [kxswa/k](https://github.com/kxswa/k), 节点数量: `19`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `50`
- [Rokate/Proxy-Sub](https://github.com/Rokate/Proxy-Sub), 节点数量: `348`
- [mianfeifq/share](https://github.com/mianfeifq/share), 节点数量: `245`
- [peasoft/NoMoreWalls](https://github.com/peasoft/NoMoreWalls), 节点数量: `293`
- [ClashNode](https://clashnode.com/f/freenode), 节点数量: `1`

## 客户端选择
### 主流桌面客户端
|                            MacOS                             |                            Linux                             |                           Windows                            | 简易描述                                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------------------------------------------------- |
| [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW(Clash For Windows)](https://github.com/Fndroid/clash_for_windows_pkg/releases) | SS, SSR, Trojan, Vmess, VLESS协议支持，策略分流能力强。            |
|     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      | SS, SSR, Trojan, Vmess, VLESS, Trojan-Go协议支持（需安装相关插件）。 |
|                              ×                               |                              ×                               |      [V2rayN](https://github.com/2dust/v2rayN/releases)      | SS, Trojan, Vmess, VLESS协议支持，有测速，测延迟功能，支持订阅，二维码，剪贴板导入及手动配置。                 |
|                              ×                               |                              ×                               |    [WinXray](https://github.com/TheMRLL/winxray/releases)    | SS, SSR, Trojan, Vmess, VLESS协议支持，支持自动连接最快节点。            |
|                              ×                               |                              ×                               | [Shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows/releases) | SS协议支持， SS 专用客户端。                                       |
|                              ×                               |                              ×                               | [ShadowsocksR-windows](https://github.com/HMBSbige/ShadowsocksR-Windows/releases) | SSR协议支持，SSR 专用客户端。                                      |
|                [Surge](https://nssurge.com/)                 |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，著名网络调试工具，策略分流能力强大，需付费。                        |
|   [ClashX](https://github.com/yichengchen/clashX/releases)   |                              ×                               |                              ×                               | SS, SSR, Trojan, Vmess协议支持，占用资源较少。                   |
|      [V2rayU](https://github.com/yanue/V2rayU/releases)      |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，支持订阅，二维码，剪贴板导入，手动配置，二维码分享，与 V2RayN 类似。                        |

### 主流移动客户端
|                          iOS/iPadOS                          |                           Android                            | 简易描述                                                     |
| :----------------------------------------------------------: | :----------------------------------------------------------: | ------------------------------------------------------------ |
| [Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118) | [Shadowrocket](https://play.google.com/store/apps/details?id=com.v2cross.proxy) | SS, SSR, Trojan, Vmess, VLESS协议支持，iOS端需在非国区 App Store 购买，美区售价 $2.99；安卓端非与 iOS 端同一作者，不支持 SSR 协议，免费且内置免费节点。 |
|                [Surge](https://nssurge.com/)                 |                              ×                               | SS, Trojan, Vmess协议支持，iOS 端著名网络调试工具，需付费。                                  |
| [Quantumult X](https://apps.apple.com/us/app/quantumult-x/id1443988620) |                              ×                               | SS, SSR, Trojan, Vmess协议支持，需在非国区AppStore购买，美区售价$4.99。 |
| [Potatso Lite](https://apps.apple.com/us/app/potatso-lite/id1239860606) |                              ×                               | SS, SSR协议支持，需在非国区AppStore购买，免费。              |
|                              ×                               | [Surfboard](https://play.google.com/store/apps/details?id=com.getsurfboard) | SS, SSR, Vmess协议支持，安卓端网络调试软件，兼容 Surge 2 配置。 |
|                              ×                               | [CFA(Clash For Android)](https://github.com/Kr328/ClashForAndroid/releases) | SS, SSR, Trojan, Vmess协议支持。                             |
|                              ×                               |  [SagerNet](https://github.com/SagerNet/SagerNet/releases)   | SS, SSR, Trojan, Vmess, VLESS协议支持。                      |
|                              ×                               | [Shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android/releases) | SS协议支持，安卓专用 SS 客户端。                                                 |
|                              ×                               | [ShadowsocksR-android](https://github.com/HMBSbige/ShadowsocksR-Android/releases) | SSR协议支持，安卓专用 SSR 客户端。                                                |
|                              ×                               |     [V2rayNG](https://github.com/2dust/v2rayNG/releases)     | SS, Trojan, Vmess, VLESS协议支持，v2ray 内核。                           |
## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

## 星标统计
[![Star History Chart](https://api.star-history.com/svg?repos=raysue/TopFreeProxies&type=Date)](https://star-history.com/#raysue/TopFreeProxies&Date)
