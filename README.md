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
高速节点数量: `92`
<details>
  <summary>展开复制节点</summary>

    vmess://eyJ2IjoiMiIsInBzIjoiU0dfQXphZE5ldCgxMykiLCJhZGQiOiIxOC4xNDMuMTIzLjM1IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjY4ZGY0ODM4LTQ2ZDAtNGI1Yi1jM2YwLWE0MGVjNzA2MzI0NSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh7MgW1ZNZXNzXSDwn4eo8J+HsyBUV+OAkOS7mOi0ueaOqOiNkO+8mmdvby5ncy92aXDjgJEiLCJhZGQiOiJ0d2Rucy5zeWx1LmN5b3UiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjEyZTA4MjU2LWRhNWQtNGIxYy1hZWNhLThjOTczY2NjZWVmOCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRmFsbGluZzQyZ2NvcmVoa25vZGUiLCJob3N0IjoiZ2NvcmVoay5zeWx1LmN5b3UiLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1jZmI6ZUlXMERuazY5NDU0ZTZuU3d1c3B2OURtUzIwMXRRMEQ@139.162.5.19:8099#SG_133
    trojan://18844%40zxcvbn@49.212.204.123:443?allowInsecure=1&sni=os-tr-5.cats22.net#JP_AzadNet%2816%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrfCfh7AgW1ZNZXNzXSDwn4et8J+HsCBIS+OAkOS7mOi0ueaOqOiNkO+8mmdvby5ncy92aXDjgJEgNCIsImFkZCI6Imdjb3JlaGtrLnN5bHUuY3lvdSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTJlMDgyNTYtZGE1ZC00YjFjLWFlY2EtOGM5NzNjY2NlZWY4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9GYWxsaW5nNDJnY29yZWhra25vZGUiLCJob3N0IjoiZ2NvcmVoa2suc3lsdS5jeW91IiwidGxzIjoidGxzIn0=
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@81.90.189.41:800#SG_AzadNet%2820%29
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.207.3.68:443#JP_AzadNet%2813%29
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.206.223.242:443#JP_AzadNet%2814%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@217.197.161.138:803#SG_AzadNet
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.201.59.236:443#KR_AzadNet%283%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@217.197.161.136:808#SG_AzadNet%287%29
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgxKSIsImFkZCI6IjguMjE4LjgxLjgxIiwicG9ydCI6IjM3MDAzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjYxZWY5NzMwLTA1ZDQtNDM1ZC1iZGFmLWExMGMxMmM3ZTVjNSIsImFpZCI6IjAiLCJuZXQiOiJodHRwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://hhvcwd@45.207.13.215:443?allowInsecure=1&sni=hn.playstone.info#HK_AzadNet%282%29
    trojan://500b1c7c-caf0-481c-8c7d-3eeb84e70ad4@20.205.35.26:443?allowInsecure=1&sni=hinet.mjt001.com#HK_AzadNet%283%29
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCg0KSIsImFkZCI6IjguMjE4Ljk0LjE4MiIsInBvcnQiOiIyNDUyMCIsInR5cGUiOiJub25lIiwiaWQiOiIzYWUyYTQ3Ni02OTI5LTQ1NDQtODAzNy0xYzc5ZjBkZmE3MDEiLCJhaWQiOiIwIiwibmV0IjoiaHR0cCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgxMikiLCJhZGQiOiI4LjIxOC43Mi4xMiIsInBvcnQiOiI2NDg2MiIsInR5cGUiOiJub25lIiwiaWQiOiJiOWFkYzllNS00ODIxLTRjOWMtYWMwNS00M2IzYThmYWQ0NDUiLCJhaWQiOiIwIiwibmV0IjoiaHR0cCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgxNikiLCJhZGQiOiIxNi4xNjMuMTI2LjE2MiIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI4YWU5OWQzMC02NWE2LTRmMzgtOGVjYy01NmMxYzNmNGQ2NzkiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2ltYWdlcyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    trojan://1bf16b43-0ad5-4512-a0e8-34bb8966278e@104.208.68.49:443?allowInsecure=1&sni=uk.stablize.top#HK_AzadNet%2817%29
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgxOCkiLCJhZGQiOiIxNjcuMTc5LjMyLjUzIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyY2M1NGRiZC1kNDQ4LTRjYzAtYjYxYy0xZDFiYTYzMTczMDciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzJjYzU0ZGJkIiwiaG9zdCI6IiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgxOSkiLCJhZGQiOiIxMDMuMTc3LjI0OC4yMDEiLCJwb3J0IjoiMTAwODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiZTRlNzI2NTEtNmZmMy00M2FkLThmMGMtNTE3Mjk5OTFmZjBhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://4f8c0e41-dbdb-40f1-99cb-2c2a0b909b52@20.187.112.140:443?allowInsecure=1&sni=de.iamnotagoodman.com#HK_AzadNet%2820%29
    trojan://53f20cd4-b381-4a80-8059-7bcd484bbb52@20.239.165.108:443?allowInsecure=1&sni=sg.liangyuandian.top#HK_AzadNet%2821%29
    trojan://1bf16b43-0ad5-4512-a0e8-34bb8966278e@ca.stablize.top:443?allowInsecure=1#HK_AzadNet%2822%29
    trojan://1bf16b43-0ad5-4512-a0e8-34bb8966278e@ap.stablize.top:443?allowInsecure=1#HK_AzadNet%2823%29
    trojan://4f8c0e41-dbdb-40f1-99cb-2c2a0b909b52@kh.iamnotagoodman.com:443?allowInsecure=1#HK_AzadNet%2824%29
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgyNSkiLCJhZGQiOiI4LjIxOC44Ni41OSIsInBvcnQiOiIzNjUzNiIsInR5cGUiOiJub25lIiwiaWQiOiJhZTNjNTZmMS1jMjQzLTQzNzMtYmQ2NS0wN2ZkMDU2OWM0NTUiLCJhaWQiOiIwIiwibmV0IjoiaHR0cCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgyOCkiLCJhZGQiOiIyMC4xODcuMTIyLjEzMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYjc0NGY1Y2MtZWFiMi1kMmNkLWY0NzctNzY2NDZkMTc5ODdmIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9wZXRhbHZ3cyIsImhvc3QiOiIiLCJ0bHMiOiJ0bHMifQ==
    trojan://d2727ecc-87bd-4bd0-b321-eb037b5d4cca@20.205.4.127:443?allowInsecure=1&sni=mzy.windowsupdate1.com#HK_AzadNet%2829%29
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgzMCkiLCJhZGQiOiJCaWEtdG8udm1lc3NvcmcuZnVuIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6ImE0NWM0ZWJkLThhMmYtNDhkZi1hZGZmLWEzYzkzZWRhYTM1NiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IkJpYS10by52bWVzc29yZy5mdW4iLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgzMSkiLCJhZGQiOiI0Ny4yNDIuMTcuMjQxIiwicG9ydCI6IjQ0MjA3IiwidHlwZSI6Im5vbmUiLCJpZCI6Ijc3YzZjNTIwLTJkMzctNDk1YS1hOTU0LWM4ZDA1NmU4OTA1MyIsImFpZCI6IjAiLCJuZXQiOiJodHRwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgzMikiLCJhZGQiOiI4LjIxMC4xMDQuMTAxIiwicG9ydCI6IjYxODk4IiwidHlwZSI6Im5vbmUiLCJpZCI6ImQxYjRjNTI1LWYyOTgtNGM4Yy05ZjhmLWRkODdkYzMyZGYwYiIsImFpZCI6IjAiLCJuZXQiOiJodHRwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgzMykiLCJhZGQiOiI0Ny4yNDIuMTQ2LjEyMyIsInBvcnQiOiIyNjIzNyIsInR5cGUiOiJub25lIiwiaWQiOiJjOGY1YTVmZC0wYTY5LTRjZjYtOGZhNi0yZWEwMjE3MWQ2YTMiLCJhaWQiOiIwIiwibmV0IjoiaHR0cCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgzNCkiLCJhZGQiOiI0Ny4yNDMuMzYuMzQiLCJwb3J0IjoiMjY5NTMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNmExZjAzNzMtZDQ0OS00MzA1LThlNDYtZTcyYTc4OTA3NmQ1IiwiYWlkIjoiMCIsIm5ldCI6Imh0dHAiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgzNSkiLCJhZGQiOiI0Ny4yNDIuMTc0LjExMiIsInBvcnQiOiI0OTU2NCIsInR5cGUiOiJub25lIiwiaWQiOiI2MWE1NzY2NS03ZGI4LTQyNGUtOGNiZi1iOTVmOWRjOWQ3OTkiLCJhaWQiOiIwIiwibmV0IjoiaHR0cCIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    trojan://1de78101-cc31-45eb-a8ac-41bd77578314@20.247.107.26:443?allowInsecure=1&sni=data-hk.efyunpan.com#HK_AzadNet%2836%29
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgzNykiLCJhZGQiOiIyNy4xMjYuMTkyLjIxMyIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJkYmI1NDg0OS0yNDgwLTRlMjAtYTFmZS1mN2YwYWI5ZmY1ZTkiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    trojan://4f7dc540-d244-4e64-af21-4b5bb300add3@132.226.5.246:443?allowInsecure=1&sni=www.tokyo2023.ga#JP_AzadNet%282%29
    trojan://18844%252540zxcvbn@49.212.182.164:443?allowInsecure=1&sni=os-tr-1.cats22.net#JP_AzadNet%283%29
    trojan://f42e1a2e-e650-44f4-8d17-bcb68663da18@150.230.201.192:443?allowInsecure=1&sni=www.seetheworldjp.ga#JP_AzadNet%285%29
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.206.224.222:443#JP_AzadNet%287%29
    trojan://b5c99730-d577-4709-934b-4ed42f0eb00b@3.114.110.209:50346?allowInsecure=1&sni=jp-tk-32.fuckjdieng.uk#JP_AzadNet%288%29
    trojan://18844%252540zxcvbn@49.212.203.7:443?allowInsecure=1&sni=os-tr-2.cats22.net#JP_AzadNet%2811%29
    trojan://28d98f761aca9d636f44db62544628eb@45.66.134.219:443?allowInsecure=1#JP_AzadNet%2812%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7UgQFNTUlNVQi3ml6XmnKxWMTAt5LuY6LS55o6o6I2QZGxqLnRmL3NzcnN1YiIsImFkZCI6Ind3dy5kaWdpdGFsb2NlYW4uY29tIiwicG9ydCI6IjgwODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiOTMwZWFhYjYtNWEwNC00OGZiLTljMTUtNzU0NWFiM2VjMGJkIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcGkvdjMvZG93bmxvYWQuZ2V0RmlsZSIsImhvc3QiOiJzc3JzdWIudjAyLmFzdWthLmJ1enoiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggW1ZNZXNzXSDwn4e68J+HsiBVU+OAkOS7mOi0ueaOqOiNkO+8mmdvby5ncy92aXDjgJEgMTkiLCJhZGQiOiIxNDEuMTAxLjExNC4xMTEiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjJiMjE0MTIyLTE5MDYtNDI4YS1iYmI3LWEwMzljYmI3Y2Q1YyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvOUpaRkRUS0UiLCJob3N0IjoiZnIxLnRydW1wMjAyMy5vcmciLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0yQ0ROIiwiYWRkIjoiMTg4LjExNC45OS4xMCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAxMDYwNTYiLCJhZGQiOiIxMjkuMTU5LjQxLjIzMyIsInBvcnQiOiIzMjU4NiIsInR5cGUiOiJub25lIiwiaWQiOiIzNDFhOTE4Mi1jNDIzLTQ5OWMtYzQ2ZS1kMTc4MzhiMjkwMzciLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggW1ZNZXNzXSDwn4e68J+HsiBVU+OAkOS7mOi0ueaOqOiNkO+8mmdvby5ncy92aXDjgJEgNCIsImFkZCI6IjE2Mi4xNTkuMTM1LjQyIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    trojan://xxoo@138.124.183.216:443?allowInsecure=1#US_AzadNet%28172%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggW1ZNZXNzXSDwn4e68J+HsiBVU+OAkOS7mOi0ueaOqOiNkO+8mmdvby5ncy92aXDjgJEgMyIsImFkZCI6IjE2Mi4xNTkuMTI4LjciLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjE3YjJhMzEzLTM3YTAtNDk0NS1hOGU0LWU2MzM3NTUwNmI0YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvQTJESk9QRlQiLCJob3N0IjoibGcxMC5jZmNkbjEueHl6IiwidGxzIjoidGxzIn0=
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@169.197.142.187:5001#US_AzadNet%2830%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xNENETiIsImFkZCI6IjE5MC45My4yNDYuMyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggW1ZNZXNzXSDwn4e68J+HsiBVU+OAkOS7mOi0ueaOqOiNkO+8mmdvby5ncy92aXDjgJEgMzAiLCJhZGQiOiJjYWNlcnRzLmRpZ2ljZXJ0LmNvbSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI4YjZkZDcwOS00ZDRlLTRiOTItZjU0Mi01NGE2NzZlZmJmZTQiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3NoYXJlcyIsImhvc3QiOiJsYS5hd3NiZXN0LmNvbSIsInRscyI6IiJ9
    ss://YWVzLTI1Ni1nY206ZTRGQ1dyZ3BramkzUVk@38.91.102.123:9101#US_AzadNet%28222%29
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@38.143.66.64:8888#US_AzadNet%2835%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@38.68.134.196:802#US_AzadNet%281%29
    ss://YWVzLTI1Ni1nY206VEV6amZBWXEySWp0dW9T@167.88.63.44:6679#US_AzadNet%28155%29
    ss://YWVzLTI1Ni1nY206ZzVNZUQ2RnQzQ1dsSklk@38.68.134.191:5004#US_AzadNet%2864%29
    ss://YWVzLTI1Ni1nY206Y2RCSURWNDJEQ3duZklO@167.88.61.50:8119#US_AzadNet%2839%29
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@38.91.101.159:8888#US_AzadNet%2895%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqPCfh6YgW1ZNZXNzXSBDQeOAkOS7mOi0ueaOqOiNkO+8mmdvby5ncy92aXDjgJEgMyIsImFkZCI6IjIzLjIyNy4zOC4xMDAiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjdiMWIyZmEzLWUzNjEtNDhjYy1iNzNkLTJjOTYzNmM3NmY0YiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvVU1XMzYyNjIiLCJob3N0IjoidjJyYXkxLnpodWppY24yLm9yZyIsInRscyI6InRscyJ9
    trojan://d1478689-439c-4590-b7ce-36e786a02dc3@107.181.161.163:443?allowInsecure=1&sni=youtube-bai-piao-wang-zhe-usa.98848.xyz#US_AzadNet%28214%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm70gIDE5IiwiYWRkIjoiMTYyLjE5LjIyNC4xNzYiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiMzgzODY4NjktYzA0Yi00NGZhLWEzY2UtNDc3ZmFhMzY2MzllIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii92bWVzcyIsImhvc3QiOiIxNjIuMTkuMjI0LjE3NiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggW1ZNZXNzXSDwn4e68J+HsiBVU+OAkOS7mOi0ueaOqOiNkO+8mmdvby5ncy92aXDjgJEgMjUiLCJhZGQiOiIxMDQuMTkuNDguOTIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjIwZTkyODgxLTVmYjQtNGIwNS1iYzc3LTU3OTI5NDc2ZGM2OSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvc2hpcmtlciIsImhvc3QiOiJoay5zaGFyZWNlbnRyZS5vbmxpbmUiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm71DbG91ZEZsYXJl6IqC54K5IDIxIiwiYWRkIjoiY2YtbHQuc2hhcmVjZW50cmUub25saW5lIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyMGU5Mjg4MS01ZmI0LTRiMDUtYmM3Ny01NzkyOTQ3NmRjNjkiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3NoaXJrZXIiLCJob3N0IjoiaGsuc2hhcmVjZW50cmUub25saW5lIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAxMDY0NDMiLCJhZGQiOiIyMTYuNDUuNTQuMTc1IiwicG9ydCI6IjM0MTUyIiwidHlwZSI6Im5vbmUiLCJpZCI6IjAyYjVhOTVmLTI0NTMtNDY0ZC1iYjk5LWVkZTQxY2FmOWI1YiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@5.181.234.254:804#US_AzadNet%28175%29
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.201.103.37:443#43.201.103.37443
    vmess://eyJ2IjoiMiIsInBzIjoiQFNTUlNVQi1WMTMt5LuY6LS55o6o6I2Qc3VvLnl0L3NzcnN1YiIsImFkZCI6ImNmLWx0LnNoYXJlY2VudHJlLm9ubGluZSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMjBlOTI4ODEtNWZiNC00YjA1LWJjNzctNTc5Mjk0NzZkYzY5IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9zaGlya2VyIiwiaG9zdCI6Im9wYy1qcC5zaGFyZWNlbnRyZS5vbmxpbmUiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiW1ZNZXNzXSBMVeOAkOS7mOi0ueaOqOiNkO+8mmdvby5ncy92aXDjgJEiLCJhZGQiOiJnY29yZXNnZy5zeWx1LmN5b3UiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjEyZTA4MjU2LWRhNWQtNGIxYy1hZWNhLThjOTczY2NjZWVmOCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRmFsbGluZzQyZ2NvcmVzZ2dub2RlIiwiaG9zdCI6Imdjb3Jlc2dnLnN5bHUuY3lvdSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDIg5rOV5Zu9Q0ROMS0xNSIsImFkZCI6IjE5MC45My4yNDYuMTk1IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0NjEyNjE4Yy0yNGNkLTQzNzktOTkyNC1jZmRmM2Q2MWZhNWEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0lZS0xENTNNIiwiaG9zdCI6Im9wZnIxLnYycmF5ZnJlZTEueHl6IiwidGxzIjoidGxzIn0=
    trojan://a2c8194b-fcfd-4c39-a6bd-31ea9f4ea671@5.135.235.160:443?allowInsecure=1&sni=upload.soft98.download#FR_AzadNet%2838%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTopMU4xRTZ2MFNVX3JHVHBn@ak1473.free.www.outline.network:1036#%F0%9F%87%B7%F0%9F%87%BA%20Relay_%F0%9F%87%B7%F0%9F%87%BARU-%F0%9F%87%B7%F0%9F%87%BARU_119
    vmess://eyJ2IjoiMiIsInBzIjoi5pyq55+lXzAxMDYyMTkiLCJhZGQiOiIxMDQuMTYuMTQ2LjExNiIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI3MzVmZjQzMC05ZDFhLTRmNTctZmI2Ni1lNDNhMjZhNzZmNzAiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2NjcHAiLCJob3N0IjoiY2NwcC45MXBhbi5vbmUiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiRlJfQXphZE5ldCgxOSkiLCJhZGQiOiI1MS43Ny4xNTguMTY5IiwicG9ydCI6IjIwOTYiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzkyZmQ5MDItYjVkMy00MjA4LWJiNDgtNjMwYjFjN2JhYmVhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.207.0.146:443#43.207.0.146443
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoKSA0OSIsImFkZCI6IjE1Mi42OS4xOTcuNjAiLCJwb3J0IjoiMTA2OSIsInR5cGUiOiJub25lIiwiaWQiOiJhYzhlMjZmZS04MTUwLTRiNjAtYWU2NC04MmZjNzdlYmEyY2YiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@212.38.189.174:2376#GB_AzadNet%289%29
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@195.154.200.150:2376#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%29%2063
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@172.99.190.61:8000#GB_AzadNet%2820%29
    ss://YWVzLTI1Ni1jZmI6ZDNiODMyMTk0NWMyNDEwNWFlNDg1NjYyMDI0NjIwZjY@134.209.158.149:28260#IN_AzadNet%282%29
    vmess://eyJ2IjoiMiIsInBzIjoiQUVfQXphZE5ldCgxMCkiLCJhZGQiOiI5NS4xNzQuNjguMjE4IiwicG9ydCI6IjMxOTkwIiwidHlwZSI6Im5vbmUiLCJpZCI6ImE2YTM3ZTA0LTVlODEtNDRjOS1iZTUzLWJhYTNmZjQ2ZWI4YiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@93.186.201.124:808#DE_AzadNet
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@107.150.94.26:989#TR_AzadNet%282%29
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.207.68.169:443#88
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDIg5rOV5Zu9Q0ROMS0yIiwiYWRkIjoiMTk4LjQxLjIwMy41IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0NjEyNjE4Yy0yNGNkLTQzNzktOTkyNC1jZmRmM2Q2MWZhNWEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0lZS0xENTNNIiwiaG9zdCI6Im9wZnIxLnYycmF5ZnJlZTEueHl6IiwidGxzIjoidGxzIn0=
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@123.253.34.235:989#%F0%9F%87%B2%F0%9F%87%BE%20MY_AzadNet
    ssr://c3NyZnJlZS56aHVqaWNuMi5uZXQ6MTAwMDU6YXV0aF9jaGFpbl9hOmFlcy0yNTYtY2ZiOnRsczEuMl90aWNrZXRfYXV0aDpaRzl1WjNSaGFYZGhibWN1WTI5dC8_Z3JvdXA9VTFOU1VISnZkbWxrWlhJJnJlbWFya3M9YzNOeVpuSmxaUzU2YUhWcWFXTnVNaTV1WlhReE1EQXdOUSZvYmZzcGFyYW09JnByb3RvcGFyYW09
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@190.120.231.45:989#CO_AzadNet
    ss://YWVzLTI1Ni1nY206aGc0OSRXSDg5NDNnMw@ak1377.free.www.outline.network:18760#IT_66
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HtfCfh7EgW1ZNZXNzXSBQTOOAkOS7mOi0ueaOqOiNkO+8mmdvby5ncy92aXDjgJEiLCJhZGQiOiJnY3NwbC5zeWx1LmN5b3UiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjEyZTA4MjU2LWRhNWQtNGIxYy1hZWNhLThjOTczY2NjZWVmOCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvRmFsbGluZzQyZ2NzcGxub2RlIiwiaG9zdCI6Imdjc3BsLnN5bHUuY3lvdSIsInRscyI6InRscyJ9
    

</details>

### 所有节点
合并节点总数: `3201`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `90`
- [Alvin9999/pac2](https://github.com/Alvin9999/pac2), 节点数量: `82`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `143`
- [freefq/free](https://github.com/freefq/free), 节点数量: `31`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `9`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `1`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `86`
- [AzadNetCH/Clash](https://github.com/AzadNetCH/Clash), 节点数量: `2553`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `241`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `8233`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `1`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `74`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `34`
- [gfwglass 节点池](https://gfwglass.tk), 节点数量: `1`
- [Meteor-1337/Meteor](https://github.com/Meteor-1337/Meteor), 节点数量: `1`
- [ronghuaxueleng/get_v2](https://github.com/ronghuaxueleng/get_v2), 节点数量: `89`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `135`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `86`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `33`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `5`
- [kxswa/k](https://github.com/kxswa/k), 节点数量: `83`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `50`
- [Rokate/Proxy-Sub](https://github.com/Rokate/Proxy-Sub), 节点数量: `464`
- [mianfeifq/share](https://github.com/mianfeifq/share), 节点数量: `230`
- [peasoft/NoMoreWalls](https://github.com/peasoft/NoMoreWalls), 节点数量: `295`
- [ClashNode](https://clashnode.com/f/freenode), 节点数量: `50`

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
