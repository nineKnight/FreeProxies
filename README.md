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
高速节点数量: `93`
<details>
  <summary>展开复制节点</summary>

    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hr/Cfh7Ug5pel5pysXzAxMDQwMTciLCJhZGQiOiJqcDEuNTM1ZWI1MjEtOWZlMC00NDc4LWIwOTAtMmE1Y2VlNGJiMDRhLm5idnBuLm9yZyIsInBvcnQiOiI3MzA0IiwidHlwZSI6Im5vbmUiLCJpZCI6IjhiNzcwYTNhLTdhZDktNDU3My1iZmQ2LTJiMTQ2YmY5M2FmNyIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiJqcDEuNTM1ZWI1MjEtOWZlMC00NDc4LWIwOTAtMmE1Y2VlNGJiMDRhLm5idnBuLm9yZyIsInRscyI6IiJ9
    ss://YWVzLTI1Ni1jZmI6ZUlXMERuazY5NDU0ZTZuU3d1c3B2OURtUzIwMXRRMEQ@139.162.41.174:8099#SG_127
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@13.215.173.2:443#SG_AzadNet%2815%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpYczlPUlQ0ajY1YjhIcmVacmcwcA@185.160.26.91:1661#JP_AzadNet%286%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@148.66.56.99:801#HK_AzadNet
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@81.90.189.41:800#SG_AzadNet%2820%29
    trojan://b5c99730-d577-4709-934b-4ed42f0eb00b@3.114.110.209:50346?allowInsecure=1&sni=jp-tk-32.fuckjdieng.uk#JP_AzadNet%288%29
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.201.59.236:443#KR_AzadNet%283%29
    trojan://8eb63951-0286-4d33-98cd-f46007afa74e@15.235.163.25:443?allowInsecure=1&sni=www.microsoft.com#SG_AzadNet%285%29
    trojan://hhvcwd@45.207.13.215:443?allowInsecure=1&sni=hn.playstone.info#HK_AzadNet%282%29
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@217.197.161.136:808#SG_AzadNet%287%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HsPCfh7cgW1ZNZXNzXSDwn4ew8J+HtyBLUuOAkOS7mOi0ueaOqOiNkO+8mmdvby5ncy92aXDjgJEiLCJhZGQiOiJzdXJvbmd3ZWkuZXUub3JnIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI2MDkzZWVmYi03YWI2LTQxZGYtYWJhMC1kNWZhNTgxNDdlMTAiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3JlZmZzN3kyNmcwdWEiLCJob3N0Ijoic3Vyb25nd2VpLmV1Lm9yZyIsInRscyI6InRscyJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@217.197.161.138:803#SG_AzadNet
    trojan://4f7dc540-d244-4e64-af21-4b5bb300add3@132.226.5.246:443?allowInsecure=1&sni=www.tokyo2023.ga#JP_AzadNet%282%29
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
    trojan://500b1c7c-caf0-481c-8c7d-3eeb84e70ad4@20.205.35.26:443?allowInsecure=1&sni=hinet.mjt001.com#HK_AzadNet%283%29
    trojan://18844%252540zxcvbn@49.212.182.164:443?allowInsecure=1&sni=os-tr-1.cats22.net#JP_AzadNet%283%29
    trojan://f42e1a2e-e650-44f4-8d17-bcb68663da18@150.230.201.192:443?allowInsecure=1&sni=www.seetheworldjp.ga#JP_AzadNet%285%29
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.206.224.222:443#JP_AzadNet%287%29
    vmess://eyJ2IjoiMiIsInBzIjoiSEtfQXphZE5ldCgxKSIsImFkZCI6IjguMjE4LjgxLjgxIiwicG9ydCI6IjM3MDAzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjYxZWY5NzMwLTA1ZDQtNDM1ZC1iZGFmLWExMGMxMmM3ZTVjNSIsImFpZCI6IjAiLCJuZXQiOiJodHRwIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://18844%252540zxcvbn@49.212.203.7:443?allowInsecure=1&sni=os-tr-2.cats22.net#JP_AzadNet%2811%29
    trojan://28d98f761aca9d636f44db62544628eb@45.66.134.219:443?allowInsecure=1#JP_AzadNet%2812%29
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.206.223.242:443#JP_AzadNet%2814%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzAxMDQ2MzAiLCJhZGQiOiIxMDQuMjUuMjUwLjE5OCIsInBvcnQiOiIyMDg2IiwidHlwZSI6Im5vbmUiLCJpZCI6ImRkY2Q2NmZkLWM3MTYtNDM5Yy05YWI4LTJhZGIxNDAwZmY0OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvYXJpZXMiLCJob3N0Ijoic2N3LmNsb3VkZmxhcmUucXVlc3QiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xQ0ROIiwiYWRkIjoiMjAzLjMwLjE5MS4xOTIiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjU2YTIxODhiLTJhYjctNDAyYy1iOWI4LTM0ODQ3ZmRmMDk1OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvNVFOUk9TUlYiLCJob3N0Ijoib3BsZzEuemh1amljbjIuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My04Q0ROIiwiYWRkIjoiNjYuMjM1LjIwMC4yMiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTdiMmEzMTMtMzdhMC00OTQ1LWE4ZTQtZTYzMzc1NTA2YjRhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9BMkRKT1BGVCIsImhvc3QiOiJsZzEwLmNmY2RuMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@134.195.196.231:2376#CA_AzadNet%288%29
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@38.68.134.48:8888#US_AzadNet%2897%29
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@134.195.196.19:8080#CA_AzadNet%281%29
    ss://YWVzLTI1Ni1nY206ZzVNZUQ2RnQzQ1dsSklk@38.91.107.216:5003#US_AzadNet%28266%29
    ss://YWVzLTI1Ni1nY206ZTRGQ1dyZ3BramkzUVk@134.195.196.230:9101#CA_AzadNet%2829%29
    ss://YWVzLTI1Ni1nY206ZzVNZUQ2RnQzQ1dsSklk@38.68.134.191:5004#US_AzadNet%2864%29
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@167.88.62.68:3306#US_AzadNet%2827%29
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@38.143.66.64:8888#US_AzadNet%2835%29
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@38.91.101.159:8888#US_AzadNet%2895%29
    ss://YWVzLTI1Ni1nY206Y2RCSURWNDJEQ3duZklO@167.88.61.50:8119#US_AzadNet%2839%29
    ss://YWVzLTI1Ni1nY206ZTRGQ1dyZ3BramkzUVk@38.91.102.123:9101#US_AzadNet%28222%29
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@38.91.107.72:5500#US_AzadNet%28259%29
    ss://YWVzLTI1Ni1nY206UmV4bkJnVTdFVjVBRHhH@38.91.107.37:7001#US_AzadNet%2892%29
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@38.114.114.49:8080#US_AzadNet%286%29
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@38.91.102.72:2376#US_AzadNet%28231%29
    ss://YWVzLTI1Ni1nY206VEV6amZBWXEySWp0dW9T@167.88.63.44:6679#US_AzadNet%28155%29
    ss://YWVzLTI1Ni1nY206Rm9PaUdsa0FBOXlQRUdQ@38.68.135.239:7307#US_AzadNet%283%29
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@167.88.63.99:2375#US_AzadNet%2849%29
    ss://YWVzLTI1Ni1nY206Rm9PaUdsa0FBOXlQRUdQ@38.75.137.9:7306#US_AzadNet%284%29
    ss://YWVzLTI1Ni1nY206WTZSOXBBdHZ4eHptR0M@38.143.66.20:5000#US_AzadNet%2834%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA0NCIsImFkZCI6Im5hbWVyLXVzLXNlYS0wMS1lZGdlY2FzdC5xZG5zLmxpdmUiLCJwb3J0IjoiMjA1MyIsInR5cGUiOiJub25lIiwiaWQiOiI5NDg5ODEyMi02ZjU3LTMyNzItOGNjZi04N2FiMzY2YjI5ZWQiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJuYW1lci11cy1zZWEtMDEtZWRnZWNhc3QucWRucy5saXZlIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi03Q0ROIiwiYWRkIjoiMjAzLjI0LjEwOC45IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI1NmEyMTg4Yi0yYWI3LTQwMmMtYjliOC0zNDg0N2ZkZjA5NTgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzVRTlJPU1JWIiwiaG9zdCI6Im9wbGcxLnpodWppY24yLmNvbSIsInRscyI6InRscyJ9
    trojan://a2c8194b-fcfd-4c39-a6bd-31ea9f4ea671@5.135.235.160:443?allowInsecure=1&sni=upload.soft98.download#FR_AzadNet%2838%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xQ0ROIDIiLCJhZGQiOiIyMDMuMzAuMTkxLjE5MiIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqfCfh6og5b635Zu9XzAxMDQxNDQiLCJhZGQiOiIzNS4xNTYuMTc3Ljc5IiwicG9ydCI6IjU1MTY0IiwidHlwZSI6Im5vbmUiLCJpZCI6IjhhMTZiYTRmLWYyMGQtNDlhMy05ODYxLWQ2OTM5MTVmZDA4ZCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2My04Q0ROIDIiLCJhZGQiOiI2Ni4yMzUuMjAwLjIyIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIxN2IyYTMxMy0zN2EwLTQ5NDUtYThlNC1lNjMzNzU1MDZiNGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0EyREpPUEZUIiwiaG9zdCI6ImxnMTAuY2ZjZG4xLnh5eiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0xM0NETiIsImFkZCI6IjE5MC45My4yNDUuMyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiNTZhMjE4OGItMmFiNy00MDJjLWI5YjgtMzQ4NDdmZGYwOTU4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii81UU5ST1NSViIsImhvc3QiOiJvcGxnMS56aHVqaWNuMi5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiUlVfQXphZE5ldCg4KSIsImFkZCI6IjkxLjE5My4xODEuMTkyIiwicG9ydCI6IjgwOTAiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDhiYzMwZTEtYmUzOS00ZWI0LWU4ODctZTY1NzliZTE1YTQ1IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@119.59.127.144:989#TH_AzadNet
    vmess://eyJ2IjoiMiIsInBzIjoi5pyq55+lXzAxMDQyMTciLCJhZGQiOiIxMDQuMTkuNTUuMTUyIiwicG9ydCI6IjIwODYiLCJ0eXBlIjoibm9uZSIsImlkIjoiZGRjZDY2ZmQtYzcxNi00MzljLTlhYjgtMmFkYjE0MDBmZjQ4IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hcmllcyIsImhvc3QiOiJzY3cuY2xvdWRmbGFyZS5xdWVzdCIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVpfQXphZE5ldCIsImFkZCI6IjE0Ni41OS45Mi4yMTkiLCJwb3J0IjoiMjA5NiIsInR5cGUiOiJub25lIiwiaWQiOiJhY2E3MWIxMy1lYzhhLTQ2NmQtYzI4Zi00MzUxNmQzY2YyNDYiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    ss://YWVzLTI1Ni1nY206ZTRGQ1dyZ3BramkzUVk@193.108.117.24:9101#DE_AzadNet%289%29
    trojan://e45b7759-6512-487b-ab20-22da1f46255f@141.95.61.209:1145?allowInsecure=1&sni=mci.ir#FR_AzadNet%2842%29
    vmess://eyJ2IjoiMiIsInBzIjoi5pyq55+lXzAxMDQ4MzEiLCJhZGQiOiIxMDQuMTcuMjA4LjE3OSIsInBvcnQiOiIyMDg2IiwidHlwZSI6Im5vbmUiLCJpZCI6ImRkY2Q2NmZkLWM3MTYtNDM5Yy05YWI4LTJhZGIxNDAwZmY0OCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvYXJpZXMiLCJob3N0Ijoic2N3LmNsb3VkZmxhcmUucXVlc3QiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDIg5rOV5Zu9Q0ROMS0xNCIsImFkZCI6IjE5MC45My4yNDUuMTcwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0NjEyNjE4Yy0yNGNkLTQzNzktOTkyNC1jZmRmM2Q2MWZhNWEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0lZS0xENTNNIiwiaG9zdCI6Im9wZnIxLnYycmF5ZnJlZTEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDEg5rSb5p2J55+2Mi0zQ0ROIiwiYWRkIjoiMjMuMjI3LjM4LjM5IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI1NmEyMTg4Yi0yYWI3LTQwMmMtYjliOC0zNDg0N2ZkZjA5NTgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzVRTlJPU1JWIiwiaG9zdCI6Im9wbGcxLnpodWppY24yLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiRlJfQXphZE5ldCgxOSkiLCJhZGQiOiI1MS43Ny4xNTguMTY5IiwicG9ydCI6IjIwOTYiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzkyZmQ5MDItYjVkMy00MjA4LWJiNDgtNjMwYjFjN2JhYmVhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDIg5rOV5Zu9Q0ROMS0xNSIsImFkZCI6IjE5MC45My4yNDYuMTk1IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0NjEyNjE4Yy0yNGNkLTQzNzktOTkyNC1jZmRmM2Q2MWZhNWEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0lZS0xENTNNIiwiaG9zdCI6Im9wZnIxLnYycmF5ZnJlZTEueHl6IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDIg5rOV5Zu9Q0ROMS0xIiwiYWRkIjoiMTk4LjQxLjIxMi4xMjMiLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQ2MTI2MThjLTI0Y2QtNDM3OS05OTI0LWNmZGYzZDYxZmE1YSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvSVlLTEQ1M00iLCJob3N0Ijoib3BmcjEudjJyYXlmcmVlMS54eXoiLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1nY206S2l4THZLendqZWtHMDBybQ@38.68.135.18:5500#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%29%2035
    vmess://eyJ2IjoiMiIsInBzIjoi8J+Hq/Cfh7cgaHR0cHMvL2dpdGh1Yi5jb20vQWx2aW45OTk5L25ldy1wYWMvd2lraSBjbGFzaCBpcDIg5rOV5Zu9Q0ROMS0xMyIsImFkZCI6IjE5MC45My4yNDQuMjAwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0NjEyNjE4Yy0yNGNkLTQzNzktOTkyNC1jZmRmM2Q2MWZhNWEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0lZS0xENTNNIiwiaG9zdCI6Im9wZnIxLnYycmF5ZnJlZTEueHl6IiwidGxzIjoidGxzIn0=
    ss://YWVzLTI1Ni1nY206ZmFCQW9ENTRrODdVSkc3@195.154.200.150:2376#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%29%2010
    vmess://eyJ2IjoiMiIsInBzIjoiRklfQXphZE5ldCgxNSkiLCJhZGQiOiIxMzUuMTgxLjIzNS4yMSIsInBvcnQiOiIxMjk1MSIsInR5cGUiOiJub25lIiwiaWQiOiIxODgyNzg5NS1iNjQ3LTQ1NzAtODFlMi1kZTNiZDc5NWZhMDQiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi5pyq55+lXzAxMDQwNzEiLCJhZGQiOiIxMDQuMjIuMjUuMTMxIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6Ijc4MWJlMDBlLTFlMDktNGUyNy1hNDY0LWUxNDE5NzQxOGM4ZiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6ImlkNS52MnJheXNlcnYuY29tIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1nY206VEV6amZBWXEySWp0dW9T@38.114.114.67:6697#%E8%BF%99%E4%BA%9B%E8%8A%82%E7%82%B9%E5%8F%AA%E8%83%BD%E5%A4%87%E7%94%A8%E6%88%96%E8%80%85%E9%98%B2%E6%AD%A2%E5%A4%B1%E8%81%94%EF%BC%8C%E8%99%BD%E7%84%B6%E8%B4%A8%E9%87%8F%E5%B9%B6%E4%B8%8D%E6%98%AF%E5%BE%88%E5%A5%BD%EF%BC%8C%E4%B9%9F%E8%AF%B7%E4%BD%8E%E8%B0%83%E4%BD%BF%E7%94%A8%29%20126
    

</details>

### 所有节点
合并节点总数: `3157`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `89`
- [Alvin9999/pac2](https://github.com/Alvin9999/pac2), 节点数量: `82`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `141`
- [freefq/free](https://github.com/freefq/free), 节点数量: `33`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `9`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `1`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `98`
- [AzadNetCH/Clash](https://github.com/AzadNetCH/Clash), 节点数量: `2553`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `242`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `7949`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `1`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `76`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `45`
- [gfwglass 节点池](https://gfwglass.tk), 节点数量: `1`
- [Meteor-1337/Meteor](https://github.com/Meteor-1337/Meteor), 节点数量: `1`
- [ronghuaxueleng/get_v2](https://github.com/ronghuaxueleng/get_v2), 节点数量: `13`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `146`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `98`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `31`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `5`
- [kxswa/k](https://github.com/kxswa/k), 节点数量: `43`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `50`
- [Rokate/Proxy-Sub](https://github.com/Rokate/Proxy-Sub), 节点数量: `429`
- [mianfeifq/share](https://github.com/mianfeifq/share), 节点数量: `234`
- [peasoft/NoMoreWalls](https://github.com/peasoft/NoMoreWalls), 节点数量: `287`
- [ClashNode](https://clashnode.com/f/freenode), 节点数量: `49`

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
